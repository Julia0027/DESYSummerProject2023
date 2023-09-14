# DESYSummerProject2023
Júlia Laguna- DESY Summer Internship project 2023:  \\
This project aims to accomplish two goals:
- (Science verification) Study CTAO's expected performance at different construction stages.
- (Monitoring layouts) Monitoring of different variable sources using sub-arrays. 
It is organised in the four folders.
- The first folder, named IRFsobtainment,  contains the code to obtain the IRFs from the Monte Carlo Simulations results and a text file with the instructions on how to run it and what to change depending on the sub-array configurations for which we want to compare their performances.\\
- The second folder, called IRFsplots, contains the code to plot the IRFs and differential sensitivity (alongside the PPUT values obtaintion) comparison between the configurations for which we have obtained the IRFs using the contents IRFsobtainment. A text file is also provided with the instructions stating what to change for each case.
- The third folder, named MLayouts, contains the code that takes the IRFs from different configurations and:
    - Simulates a variable source
    - Extracts the light curves for the variable source and expected detection, that we expect we would obtain with each configuration
    - Fits the expected detection data to regian the original spectra.
As a remark, the code is written so that the notebooks from the second and third folder can access the IRFs obtained and stored in the first folder. To run this code on a local computer, the details on the paths that need to be changed are specified at the beginning of each notebook or .py file. \\
- In the fourth and last folder, there is the Summer Internship report, and the additional code to obtain the last plot shown on it.
