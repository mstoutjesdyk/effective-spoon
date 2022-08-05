# 2-D Spectrum Analysis

MS: &#x2717;
<br>
BD: &#x2717;

This module enables you to perform 2DSA on a chosen experimental data set. Upon completion of an analysis fit, there are several plots available: experiment, simulation, overlayed experiment and simulation, residuals, time-invariant noise, radially-invariant noise, and 3-D model. 

The 2DSA method is used for composition analysis of sedimentation velocity experiments. It can generate sedimentation coefficient, diffusion coefficient, frictional coefficient, $f/f_{0}$ ratio, and molecular weight distributions. The distributions can be plotted as 3-D plots, with the third dimension representing the concentration of the solute found in the composition analysis. The set of all such final calculated solutes for a model which are used to generate a simulation via Lamm equations. This simulation is then plotted overlaying a plot of the experimental data. 

Each 2DSA pass can be repeated for a specified number of refinement iterations These iterations, in turn, can be repeated for a specified number of meniscus points or Monte Carlo iterations. 

Each refinement iteration proceeds over a defined grid of $s$ and $f/f_{0}$ values. That grid is divided into sub-grids as defined by a number of grid refinements in each direction.

!!! danger ""

    ![](img/nav-us/us-velocity-2dsa.png){width="1000"}

<span style="color:#00008B";>3-D Plot</span> Open a control window for a 3-D dimensional plot of the final computed model. 

<span style="color:#00008B";>Residual Plot</span> Open a plot dialog for a far more detailed set of results plots. 

<span style="color:#00008B";>Status Info</span> This text window displays continually updated summaries of computational activity and results.

<span style="color:#00008B";>Fit Control</span> 

??? quote "<span style="color: #90030C;">2DSA Fit Control Dialogue</span>"

    !!! danger ""

        The parameters of this dialog define and control an analysis run to find the set of solutes that best fits experimental data. 

        ![](img/nav-us/us-velocity-2dsafit.png){width="1000"}
    
        <span style = "font-size:16px";>Fitting Controls</span>
    
        <span style="color:#00008B";>Lower/Upper Limit (s)</span> Set a lower/upper limit of sedimentation coefficient values to scan.
    
        <span style="color:#00008B";>Number Grid Points (s)</span> Set the total grid count of sedimentation coefficient points.
      
        <span style="color:#00008B";>Lower/Upper Limit (f/f0)</span> Set a lower/upper limit of frictional ratio values to scan.
    
        <span style="color:#00008B";>Number Grid Points (f/f0)</span> Set the total grid count of frictional ratio points.

        <span style="color:#00008B";>Thread Count</span> Specify by counter the number of threads to use for computations. This value is the total number of worker threads used at one time. 

        <span style="color:#00008B";>Fit Time-Invariant Noise</span> Check this box if you want to calculate time-invariant noise.

        <span style="color:#00008B";>Fit Radially-Invariant Noise</span> Check this box if you want to calculate radially-invariant noise.

        <span style="color:#00008B";>Automatically Plot</span> Check this box if you want plot dialogues to automatically open at the completion of all calculations.

        <span style="color:#00008B";>Vary Vbar with Constant f/f0</span> Check this box if you want to vary vbar while holding f/f0 constant.
    
        <span style = "font-size:16px";>Optimization Methods</span>
        
        <span style="color:#00008B";>Uniform Grid</span> Check this box if Uniform Grid is your preferred optimization method.

        <span style="color:#00008B";>Custom Grid</span> Check this box if you wish to have a custom grid as your preferred optimization method.
    
        <span style="color:#00008B";>Float Meniscus/Bottom</span> Check this box if you wish to wrap the refinement iterations in outer interactions of meniscus/bottom scans. Checking this option means that Monte Carlo may not be chosen.
    
        <span style="color:#00008B";>Load Model</span>

        <span style="color:#00008B";>Fit Range</span>

        <span style="color:#00008B";>Fit Grid Points</span>
      
        <span style="color:#00008B";>Monte Carlo Iterations</span> Select a number of Monte Carlo interactions to perform. A separate model is produced from each iteration.

        <span style="color:#00008B";>Advanced Analysis Controls</span>

        <span style="color:#00008B";>Use Iterative Method</span> Check this box if you want to refine analysis fits with multiple refinement interactions.

        <span style="color:#00008B";>Maximum Iterations</span> Select the number of maximum number of refinement iterations. This number may not be reached if subsequent iterations achieve the same set of computed solutes or if their variances differ by a very small amount.

        <span style="color:#00008B";>Plot Norm Grid</span>

        <span style="color:#00008B";>Norm Tolerance</span>

        <span style = "font-size:16px";>Status Information</span>

        <span style="color:#00008B";>Estimated Memory</span> Text showing a memory use estimate based on chosen parameters.
    
        <span style="color:#00008B";>Completed Iteration</span> Display of the last completed refinement iteration completed.

        <span style="color:#00008B";>Old Variance</span> The variance value of the previous iteration.

        <span style="color:#00008B";>New Variance</span> The variance value of the last completed iteration.

        <span style="color:#00008B";>Improvement</span> The difference between the variance value from the last iteration and the one preceeding it.
<br>