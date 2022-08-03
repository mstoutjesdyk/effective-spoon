<br> 
MS: &#x2717; 
<br> 
BD: &#x2717; 

<span style="font-size:26px";>Multiwavelength Optics</span>

!!! danger ""

    For more information, see:
    
    Practical aspects of MWL AUC. Pearson, Coelfen. 2019.
    
# <span style="font-size:20px";>MWL Detector Calibration</span>
    
<span style="font-size:16px";>Alignment Test and Calibrations</span>

1. Angle Calibration: ensures the sliding stage scanning vector is aligned with the radial vector of the rotor.

An angular scan of an empty sample cell is taken at radial positions near the top and bottom of the cell at 3,000 RPM. Map the angular position of the sample and reference sector positions. The difference between the top and bottom angles should be less than 0.25-degrees. If the angle is greater, the detector arm may be rotated until the result is satisfactory. 

This calibration is executed to determine the synchronization timing of the flash lamp for all possible rotor speeds. The cell sector angular position is selected for scans at incremental rotor speed settings in the calibration routine, and the results are fitted to a linear function internally in the software.

2. Radial Calibration: scans the radial dimension of the counterbaance while the rotor is at a low speed such as 3,000 RPM. The edges of the counterbalance mask, on the reference sector side, are set to be 5.85 mm and 7.15 mm while int he rotor. These edges serve as reference points from which a radial calibration conversio of the stepper motor increments are generated.

<span style="font-size:16px";> Final Checks</span>

Note that the fiber optic coupling to the flash lamp can affect the signal-to-noise (SNR) ratio, which can be explained by the non-uniformity in the arc generated across the electrodes of the flash lamp. To find the position of highest SNR, observe the noise structure of the recorded signal while adjusting the coupling of the fiber optical cable to the flash lamp. 

Additionally, the DC supply voltage to the flash lamps can influence the noise of the lamps, but the recent 20 W L12745 Xenon flash lamp from Hamamatsu provides significantly reduced signal noise. 

To assume optimal data quality, collect test scans of the system prior to expereimentation. A sharp meniscus and steep counterbaance edges in test scans are indicative of good alignment and focus. 

The most revealing test of data quality is to perform an experiment on well-characterized samples such as BSA. Using the 2DSA model in UltraScan provides particularly sensitive indications of data quality over relavent spectral ranges, and the evaulation of BSA should yeild S-Spectra of sharp monomer, dimer, and trimer peaks.