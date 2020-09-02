# Description:
Numerical simulation platform to evaluate the perfomances of a 480 Gb/s optical coherent communication system using different advanced technologies deployed in optical networks, including MIMO equalization techniques.

**Owners:**

Sagi Shtainman - Linkedin https://www.linkedin.com/in/sagi-shtainman

Sagi Radiano - Linkedin https://www.linkedin.com/in/sagi-radiano


## Installation:
Unzip and Drag all Matlab files to the same path and run 'DP16QAM_Optic_Main'.

**In order to get the code you need to ask permission.** 

*Change in the system parameters will lead to different results.*


## Usage:
Please read the notes written in the matlab codes.


## Contributing:
N/A


*The Optic Channel was divided to 50 sections in order to simulate the Maxwellian distribution effect of the PMD*

## Optical Channel Model
**Optical Channel:**

![](Optical%20Channel.jpg)

![](Optical%20Channel%20Dynamic.jpg)

## System and Results
**System Diagram:**

![](System%20Diagram.jpg)

*The X&Y polarizations after the CDC component marked as a 1 line for esthetics only*

**Results:**

**16QAM Constellation Before entering the Optical Channel**

![](16qam%20constellation.bmp)


**16QAM Constellation with Optical Channel Distorions and the CMA and RDE Equalization**

![](CMA&RDE%20Constellation.bmp)


**16QAM Constellation with Optical Channel Distorions and the LMS Equalization**

![](LMS%20Constellation.bmp)









### References
[1] S. J. Savory, “Digital filters for coherent optical receivers,” Optics Express, vol. 16, no. 2, p. 804, 2008.

[2] S. Ten, M. Edwards, “Introduction: Importance of PMD for High Data Rate Transmission Systems,” pp. 1–12, 2006.

[3] M. S. Faruk and S. J. Savory, “Digital Signal Processing for Coherent Transceivers Employing Multilevel Formats,” Journal of Lightwave Technology, vol. 35, no. 5, pp. 1125–1141, 2017.

[4] D. Lavery, M. Paskov, R. Maher, S. J. Savory, and P. Bayvel, “Modified Radius Directed Equaliser for High Order QAM.”,2015.

[5] K. Kikuchi, “Fundamentals of coherent optical fiber communications,” Journal of Lightwave Technology, vol. 34, no. 1. Institute of Electrical and Electronics Engineers Inc., pp. 157–179, 01-Jan-2016.

[6] T. Fehenberger, N. Hanik, T. A. Eriksson, P. Johannisson, and M. Karlsson, “On the impact of carrier phase estimation on phase correlations in coherent fiber transmission,” 2015 Tyrrhenian Int. Work. Digit. Commun. TIWDC 2015, pp. 35–38, 2015.

[7] I. Fatadin, D. Ives, and S. J. Savory, “Blind equalization and carrier phase recovery in a 16-QAM optical coherent system,” J. Light. Technol., vol. 27, no. 15, pp. 3042–3049, 2009.

[8] O. Zia-Chahabi, R. Le Bidan, M. Morvan, and C. Laot, “Efficient frequency-domain implementation of block-LMS/CMA fractionally spaced equalization for coherent optical communications,” IEEE Photonics Technol. Lett., vol. 23, no. 22, pp. 1697–1699, 2011.

