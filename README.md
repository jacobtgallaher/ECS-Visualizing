# Eddy Covariance System (ECS) O2 Flux Visualization

*Some files were too large to be uploaded to GitHub so they have been put on Google Drive.*
Data Access Link (Google Drive): https://drive.google.com/drive/folders/1EZanGBpJ14C3uFRTrY5880ObZweiRVly?usp=sharing
*Access is permitted as a commentor and viewer, not as an editor.*
To use files, simply download them into a folder and direct them to the correct path, using the 2nd block of code in "ECS_#_O2_Flux_Visualization.ipynb".

ECS and Hammerhead Project READ ME File:

The data collected for this project was collected in August 2026 in South Bay, Virginia just inshore of Wreck Island using eddy covariance and Hammerhead systems. Sites were South Bay Site #3, SB03 (Seagrass meadow), and waypoint 135 (WP135) (Bare sand). ECS #1 and the Hammerhead were placed at South Bay 3, while ECS #2 was placed at the bare sand site. Data within this project contains data from FireSting O2 sensors, Nortek Acoustic Doppler Velocimeter (ADV), and internal sensors of pressure, temperature, etc. The goal of this project is to visualize this mass of raw data collected over 3 days containing millions of datapoints. I want to make a figure similar to Long et al., 2015 (Figure 2), showing directional velocities (cm/s), O2 Concentration (umol/L), cumulative flux (mmol/m^2), and the average flux (mmol m^-2 d^-1) over the 72 hours the instruments were deployed for. In addition, I also would like to make a Geographical figure mapping the study sites and the meadow extent identified by the closest date that could be mapped using remote sensing.

This folder contains a CODE, DATA folders, and a README.md file.
	- DATA folder holds the raw data files for the ECS system (This is replaced by the data folder in Google Drive)
		- The .hdr file for each instrument lays out the headers for each column in all the other individual files (This file can be found in RAW_DATA)
		- There are raw and adjusted data in each folder for each respective instrument we collected data with
		- Adjusted data includes that that has been calibrated and this will mostly be the data that I use for processing
	- CODE folder contains a notebook for EDA of the raw data files
	- README.md (This file) contains descriptive information 

The environment that runs with this code is the "ECS_Visualizing (Python 3.14.7)".

This folder has been added as a separate repository on GitHub.

Additional files/folders such as figures, adjusted data files, etc. will be added as needed.

Many of these figures will be modeled after those found in Berger et al., 2020 (https://doi.org/10.1002/lno.11397) & Long et al., 2015 (https://doi.org/10.3354/meps11314).