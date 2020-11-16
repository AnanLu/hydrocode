# hydrocode
PHYS643 PS5 numerical assignment that studies advection, diffusion and 1D hydrocode

Name: Anan Lu

ID: 260467054

Written in Google Colab, should be in python3.6

All code files are uploaded in two formates: .py and .ipynb. In case that .py codes doesn't work, please run .ipynb code instead. 
There should be an option to open it in Google Colab.
The end products for each question are also submitted in format of mp4 videos.

List of Python code files:

* Folder: Q1
- "1_advection.py" & "1_advection.ipynb" solves the advection equation, and compares FTC and Lax-Friedrich methods.
- "1_advection.mp4" is the animated video of the solution

* Folder: Q2
- "2_advection_diffusion.py" & "2_advection_diffusion.ipynb" solves the advection-Diffusion equation, and compares 2 diffusion coefficients: 0.5 and 0.05. Both explicit and implicit methods are included. There could be some problem with implicit method. Results from explicit method look more reasonable.
- "2_advection_diffusion_explicit.mp4" is the animated video of the solution from explicit method.
- "2_advection_diffusion_implicit.mp4" is the animated video of the solution from implicit method.

* Folder: Q3
- "3_1D_hydro_solver.py" & "3_1D_hydro_solve.ipynb" solves the 1D hydro euqations, and compares the effect of perterbation amplitude, width and sound speed. I followed the equations closely. The only doubts are I have are around how to update the boundary of velocity and flux. 
- "3_1D_hydro_solver.mp4" is the animated video of the solution

Answer to question 3:
The impact of perterbation strength and sound speed is shown in code files "3_1D_hydro_solver.py" & "3_1D_hydro_solve.ipynb" and the video "1D_hydro_solver.mp4". 
The blob is smeared by the pressure gradient, and form some waves that move both right-ward and left-ward. 
Both walls reflect the wave back, which eventually meet somewhere between mid-point and left end, and form something like a shock.
The perturbation blob can be strengthened by both amplitude and width. It seems that both increase the strength of waves and peak and width of the shock.
Sound speed affects the pace of the event

I got some help from Constanza Echiburu, without comparing codes.
