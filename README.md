# RAWS2012
This repository contains the codes for data analysis of voltage data from Ooty Radio Telescope and Giant Metrewave Radio Telescope (GMRT). This analysis was a part of Radio Astronomy Winter School, 2021 organised by National Centre for Radio Astrophysics (NCRA), Pune and Inter-University Centre for Astronomy and Astrophysics (IUCAA), Pune, India.

## Analysis of voltage data

### Pulsar signal 
This code analysis the voltage data of Vela pulsar from Ooty radio telescope. 

* Data: file containing 2 columns of integer values separated by a space, corresponding to the voltage readings from North (column 1) and South (Column 2) apertures at Ooty Radio Telescope.
  
The integrated pulse profile of the Vela pulsar is obtained using the De-dispersed dynamic spectrum for north and south apertures. The obtained time period of the pulsar is 89 ms.

Following digrams show dynamics spectrum and the integrated pulse profile of Vela pulsar repectively.

![Power_spectrum](https://github.com/user-attachments/assets/c65cc995-3b5b-4d11-8018-32d4875d46b2)

![integrated_pulse_profile](https://github.com/user-attachments/assets/56348870-a2cf-4938-b483-13cc5d3221d5)


### identifying RFI channels
This code uses the power spectrum to identify RFI channels involtage data from Giant Metrewave Radio Telescope (GMRT).

* Data: files corresponding to the voltage recorded by antennas C11 and C12 observed at band 3 (300 - 500 MHz) and band 5 (1050 - 1450 MHz) at each (voltage time-series data).
