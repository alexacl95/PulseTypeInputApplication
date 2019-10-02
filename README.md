# The pulse-type inputs application for a dengue spread model

The pulse-type inputs application for a dengue spread model (*PulseTypeInputApplication.mlx*) is a live script built to study a spread dengue model using different methodologies implemented in [GSUA-CSB Toolbox](https://la.mathworks.com/matlabcentral/fileexchange/72637-gsua-csb) for Matlab:  parameter and confidence intervals estimation(see the CSB [Theory](https://arxiv.org/abs/1909.09603)), uncertainty and sensitivity analyses, simulation, among other.  This live script allows analyzing the control of vector-borne disease through these mathematical tools and real information of several dengue outbreaks; in this case, those outbreaks occurred in the municipality of Bello (Colombia) between 2009 and 2010. Also, this live script is built to encourage and replicate mathematical methodologies for dengue control using Matlab tools.

In this script, we present the implemented dengue model and some of its modifications, including pulse-type inputs that represent extrinsic phenomena as chemical control or decrease in mosquitoes mortality because of climatic conditions. We present three cases of dengue model in our live script: adding (A) zero inputs, (B) one input, and (C) four inputs to the dengue.

## About real data

For the application of the dengue model using the GSUA_CSB Toolbox, we implemented as real data the number of cases of dengue reported every week between 2009 and 2014 in Bello (Colombia). We present the raw data (*RawDataDengueCases.csv*), showing information about each person diagnosticated with dengue: the reporting date (*NotificationDate*), initial symptoms date (*InitialSymptomDate*), the corresponding epidemiological week and year. From this file, we processed the data into *Data_Bello_2010_2014.mat*, which is the sum of the number of cases per epidemiological week reported in the raw data file.

## Getting Started

The live scripts in Matlab are interactive documents similar to notebooks as Jupyter. These combine the Matlab code with text, equations, and images in the same editor; also, these scripts store and display the output alongside the run code.

According to the above, the images and information presented in *PulseTypeInputApplication.mlx*([see here](https://alexacl95.github.io/PulseTypeInputApplication/PulseTypeInputApplication.html)) correspond to an example of running case B (one pulse input). It is possible to recreate these results or perform other experiments with cases A and C by following the instructions presented in the live script, by using both Simulink and symbolic math from Matlab. 

### Prerequisites

[Matlab](https://la.mathworks.com/downloads/web_downloads?s_tid=srctitle) supports live script in versions R2016a and above.

The [GSUA-CSB Toolbox](https://la.mathworks.com/matlabcentral/fileexchange/72637-gsua-csb) is supported by R2017a and above.

If you want to run *PulseTypeInputApplication.mlx* as a normal script, copy the corresponding codes from here see [here](https://alexacl95.github.io/PulseTypeInputApplication/PulseTypeInputApplication.html) and, for more information, see the [user guide](https://drojasd.github.io/GSUA-CSB/gsua_userguide) from GSUA-CSB Toolbox. 
