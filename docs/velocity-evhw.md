# Enhanced Van Holde-Weischet
MS: &#x2717;
<br>
BD: &#x2717;

The method of Van Holde and Weischet (vHW) is a versitile, model-indepedent approach to determine sedimentation coefficient distributions by graphically analayzing sedimentation velocity experimental data.

!!! danger ""

    ![](img/nav-us/us-velocity-evhw.png)
  

<span style="color:#00008B";>Distribution Plot</span> Click here for a plot dialog that will show a vHW distribution plot illustrating sedimentation coefficeint power related to seperate species.

??? quote "<span style="color:#90030C";>van Holde-Weischet Distribution/Histogram Plots Dialog</span>"

    !!! danger ""
        
        The following plots show the clusting of data around several sedimention coefficient points, indicating the presence of multiple species in the solution.

        ![](img/nav-us/us-velocity-vhwdp.png){width="800"} <br>
    
        This is the distribution plot option. It is plotted as the boundary fraction as a function of the sedimentation coefficient. In this particular plot, we see ~15% of our species at ~2S, and ~45% at ~5.2S.
     
        ![](img/nav-us/us-velocity-vhwh.png){width="800"}<br>
    
        This is the histogram plot option. It is plotted as the relative concentration as a function of the sedimentation coefficient. Again, we see the same data as in the distribution plot. 

        <span style="color:#00008B";>Sensitivity</span> Change the sensitivity factor up or down to affect the nature of the histogram.
    
        <span style="color:#00008B";>Smoothing</span> Change the smoothing factor up or down to affect the nature of the envelope.

<span style="color:#00008B";>Select Groups</span> Click on this utton to begin a session of choosing vHW Extrapolatino Plot division groups. Multiple groups can be chosen, with division line overlap between groups.

<span style="color:#00008B";>Use FE Data</span>
 
<span style="color:#00008B";>Plateaus from 2DSA</span> Check this box to have plateau values calculated from a model associated with any loaded noise values. If this box is unchecked, each scan's plateau value is determined by a series of fits to initally designated plateaus.

<span style="color:#00008B";>Manual-only Replot</span> Check this box to supress automatic re-plotting with each parameter change. 

<span style="color:#00008B";>Use Enhanced vHW</span>

<span style="font-size:16px";>Analysis Controls</span>

<span style="color:#00008B";>Back Diffusion Tolerance</span> Select a tolerance value to fine tune exclusion of points affected by back diffusion.

<span style="color:#00008B";>Divisions</span> Choose the number of divisions to use in vHW analysis.

<span style="color:#00008B";>Data Smoothing</span> Choose the number of points to use for any smoothing of raw input data.

<span style="color:#00008B";>% of Boundary</span> Choose the percentage of the range from concentration baseline to plateau that is used for analysis.

<span style="color:#00008B";>Boundary Position (%)</span> Choose the percent of the plateau-baseline range that is to be added to the baseline to form the beginning of the analysis span.

