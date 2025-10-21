This repository contains the code associated with the results shown in the paper ***"First time delay observation between two mid-infrared channels in solar***

***flare footpoints"***



The code is structured as follows



**-DESCRIPTION OF OBSERVATIONS**

Contains code to visualize intensity variations in each of the infrared channels during the flare. It is based on the files: intensity\_data\_05um.csv and intensity\_data\_10um.csv.

Additionally, soft X-ray observations using GOES are included, which can be found in the file: goes\_data.



**-ANALYSIS AND RESULTS**

* Lag estimation using the Cross-correlation (CCF) and Local CCF for a known signal

Contains the code to generate the results shown in Appendix 1 of the paper, where the lag is calculated for two flare-like signals.



* Lag estimation using the Cross-correlation (CCF) and Local CCF for a flare signal in mid infrared.



* Time delay between 5.2 and  8.2μm  channels.



* Infrared emission during a solar flare



* Infrared emission during a solar flare from a RADYN output



It contains the code necessary to calculate infrared emission for a particular wavelength based on atmospheric conditions obtained from the RADYN FChroma Grid outputs. This requires obtaining the values ​​for time, electron temperature, electron, proton, and hydrogen density at each instant in time (t) and at each position in the solar atmosphere (z). These values ​​can be obtained directly from the simulation outputs, which can be found here: https://star.pst.qub.ac.uk/wiki/public/solarmodels/start.html For the purposes of this paper, these parameters have been saved in .pkl files located in the folder: RADYN\_Outputs\_FChromaGrid



* Different RADYN scenarios



**-ANIMATIONS** 



Additionally, three animations are included in MP4 format.

For one of the RADYN outputs, an animation is included showing the variation in electron temperature and density of hydrogen, protons, and electrons.

An animation is also included showing the variation of the Contribution Function (CF) over time, on a linear and logarithmic scale.



The file names are:

-density\_animation.mp4

-cf\_animation\_linear\_scale.mp4

-cf\_animation\_log\_scale.mp4





