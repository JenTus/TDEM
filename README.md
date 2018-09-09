# TDEM: Two-Phase Diversity Exposure Maximization Algorithm

* Contact author: cigdem.aslay@aalto.fi

---

*  **Citation information:** Aslay, C., Galbrun, E., Matakos, A., Gionis, A. (2018). Maximizing the diversity of exposure in a social network. IEEE International Conference on Data Mining (ICDM). 


* Redistribution and use in source and binary forms, with or without modifications, are permitted for academic purposes, provided that the proper acknowledgements are done.


# Compilation  

**make -f Makefile_tdem**


# Input configuration file 

**config.txt:** sample configuration file that needs to be edited and passed as a command line arguement to TDEM. 
It contains the necessary information on parameters and location of input files as required by TDEM.   


# Running from command line

**./main_TDEM -c config.txt**


**Note:** The implementation also contains the code for baselines used. Comment out line 60-62 of allocator.cc to receive also the results for baselines. 


