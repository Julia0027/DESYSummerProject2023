# DESYSummerProject2023
Júlia Laguna- DESY Summer School project 2023.  <br>
<br>
This project aims to accomplish two goals:<br>
- (Science verification) Study CTAO's expected performance at different construction stages.<br>
- (Monitoring layouts) Monitoring of different variable sources using sub-arrays. <br>
<br>
This repository is organised in three folders.<br>
<br>
- The first folder, named IRFsobtention, contains the code to obtain the IRFs from the Monte Carlo Simulations results. <br>
At the beginning of the file we provide the instructions to run it, stating what to change depending on the sub-array configurations we want to test.<br>
<br>
- The second folder, called IRFsplots, contains the code to plot the IRFs and differential sensitivity comparison (alongside the PPUT values) between different configurations. <br>
 At the beginning of the file we provide the instructions on how to run it, which is usually done using the IRFs obtained with the code from the first folder. <br>
 <br>
- The third folder, named MLayouts, contains the code that takes the IRFs from different configurations and:<br>
    · Simulates a variable source.<br>
    · Extracts the light curves for the variable source and expected detection with the tested configurations.<br>
    · Fits the expected detection data to regain the original spectra.<br>
    <br>
As a remark, the code is written so that the notebooks from the second and third folder can access the IRFs obtained and stored in the first folder.  <br>
The report resulting from this summer project, using the code provided in this repository, is also provided in the pdf file in this repository. <br>
Thank you!
