# Time Derivative

MS: &#x2717;
<br>
BD: &#x2717;

This module will calculte g(s) differential sedimentation profiles by subtracting consectutive scan pairs from each other and mapping the resulting difference curves to the S domain to obtain dc/dt curves. 

The advantage of this method is its ability to nicely subtract out time invariant noise. Unlike the [van Holde-Weischet module](velocity-evhw), the Time Derivative method does not correct for diffusion. In order to obtain accurate results, it is important to use only a small scan range over which diffusion has not change significantly.

!!! danger ""

    ![](img/nav-us/velocity-time.png)
    
    Time Derivative (dC/dt). Average g*(s) vs. Sedimentation Coefficient (Svedberg)
    
    Velocity Data. Intensity at Wavelength (nm) vs. Radius (cm)
 
<span style="font-size:16px";>Analysis Controls</span>

<span style="color:#00008B";>Data Smoothing</span> Choose the number of points to use for any smoothing of raw input data. 

<span style="color:#00008B";>Boundary Pos. (%)</span> Choose the percent of the plateau-baseline range that is to be added to the baseline to form the beginning of analysis span. 

<span style="color:#00008B";>S-value Cutoff</span> Choose the sedimentation coefficient value to form the maximum X value of the Time Derivative plot. 

<span style="font-size:16px";>Graph Selection</span>

<span style="color:#00008B";>x:radius</span> Select this radio button to choose a g*(S) versus radius dC/dt plot. 

<span style="color:#00008B";>x:S</span> Select this radio button to choose a g*(S) versus sedimentation coefficient dC/dt plot. 

<span style="color:#00008B";>Average S</span> Select this radio button to choose an Average g*(S) versus sedimentation coefficient dC/dt plot. 