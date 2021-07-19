# Manual Material Handling Dataset for Biomechanical and Ergonomics Analysis.

Interactive guide to download, import, and process the data included in the dataset available on Zenodo at the following link: https://zenodo.org/deposit/4633087 

The live script contains 7 steps:
  1.	The first step allows the user to select the data to download from the Zenodo link. To use the dataset the user must select at least the “EMG_Data”, the “EMG_Labels”, the         “mvnx_files”, and the “mvnx_Labels” zipped files.
  2.	The second step extracts the contents of the zipped files downloaded.
  3.	The third step allows the user to select the subject(s) to process.
  4.	The fourth step allows the user to select the trial(s) of the selected subject(s) to process.
  5.	The fifth step imports the motion data and labels of the selected trials and subjects in the MATLAB workspace.
  6.	The sixth step imports and process the EMG data and labels of the selected trials and subjects in the MATLAB workspace.
  7.	The seventh step plots the sEMG signal acquired from the Biceps brachii and shoulder flexion angle to provide an example of visualization of the EMG and motion data present       on the dataset.

The user is free to add processing functions for both motion and EMG data to achieve the desired goals.

In the procedure, the user is required to download the 7-Zip software in the system path to fulfill the second step and the MATLAB function provided by Xsens (load_mvnx.m) to import the mvnx (motion) files in the MATLAB workspace (step 5). 
