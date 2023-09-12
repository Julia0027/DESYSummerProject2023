# DESYSummerProject2023
Júlia Laguna- DESY Summer Internship project 2023: CTA monitoring arrays performance study. \
This project contains a folder with the code to obtain the IRFs from the Monte Carlo Simulations, named IRFsobtainment. Inside the folder there is the required code, and a text file with the instructions on how to run it and what to change for each case.
(Science verification) The project also contains a folder with the code to plot and compare the IRFs  between different configurations from the results obtained using the IRFsobtainment file code. The code file name is ??? and it also comes with a text file with the instructions on what to change\
(Monitoring layouts) There is a third folder containing the code that takes the IRFs from different configurations and:
- Simulates a variable source
- Extracts the light curves for the variable source and expected detection, that we expect we would obtain with each configuration
- Fits the expected detection data to regian the original spectra.\
As a remark, the code is written so that the notebooks from the second and third folder can access the IRFs obtained and stored in the first folder. To run this code on a local computer, the details on the paths that need to be changed are specified at the beginning of each notebook or .py file. \
In the fourth and last folder, there is the Summer Internship report, and the code to obtain the last plot shown on it.
