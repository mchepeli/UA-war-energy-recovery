This readme file accompanies a paper entitled "Can Ukraine Go ‘Green’ on the Post-war Recovery Path?" submitted to the Joule journal.

Discussion below provides the step-by-step instructions for replicating the results reported in the paper. An implementation assumes that the user has installed GAMS and Veda-TIMES software. Corresponding installation instructions are available here:  https://veda-documentation.readthedocs.io/en/latest/pages/Getting%20started.html Results were generated using a first version of the Veda software. Simulations have not been tested with the latest version of Veda 2.0. 

The following steps need to be implemented assuming that the software referenced above is installed and activated.

1. Both folders from the provided archive must be pasted to the root folder of the VEDA_FE (VEDA Front-End).

2. Folder "Gams_Wrk_N_BLS_M0LSEA-v05" contains all files neccesary to simulate the pre-war baseline scenario,
which can be started by opening the "VTRUN_N_BLS_M0LSEA-v05.CMD" file.

3. Folder "Gams_Wrk_W&W2_M0LSEA-v05" contains all files neccesary to run the 
past-war baseline Reference 1 and Reference 2 scenarios, as well as mitigation pathways. The latter can be done by opening the corresponding "VTRUN_*_M0LSEA-v05.CMD" file.

4. All calculations are performed with author's original cplex and control panel setup options regardless of user's current ones. 
VEDA_FE doesn't need to be launched.

5. After the calculations are completed, the results could then be imported into VEDA_BE database. In order to implement this, the user would need to make sure that folders "Gams_Wrk_N_BLS_M0LSEA-v05" and "Gams_Wrk_W&W2_M0LSEA-v05" are selected as Input Files Locations. The latter can be done by checking the "Import/Archive"->"Manage Input Files Locations" settings in VEDA_BE.
   