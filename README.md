# Comp_Stat
This is a repository where I have saved the code I used and wrote for my project on PINNs.

I chose to work on a project on Python to gain some experience reading and writing Python code. Unfortunately, my experience with Python before this was rather limited and so this meant that it took me a long time to write even the shortest snippets of code. 

I was able to run all the code present in the xPINNs folder. Once it came to expanding the project, I wanted to use PINNs with both the Lotka-Volterra Equations and also the Lorenz Equations. However, the code from the paper was hard-coded for a 1D problem. I did try and modify it to model the Lotka-Volterra problem, ie a 2D problem, but I was unable to do so successfully as the code was quite complicated and not very flexible. I therefore did some research online and came across the Deep XDE library (https://deepxde.readthedocs.io/en/latest/) which is used for PINNs. There were some problems here as well, but overall I managed better with this library. 

The folder called '''lorenz''' contains a notebook where I successfully used PINNs to model the Lorenz System. 

The folders called "lotka_volterra" and "oscillator" contain notebooks where I tried to use PINNs to model the Lotka-Volterra and 1D Oscillator respectively. Unfortunately, these attempts were not as successful and I could not get the PINN parameter estimation to converge to the correct values. I spent a lot of time on this, but ultimately it was not working and so I decided not to bring this to the presentation. 

The folder called "oscillator-paper" is the code where I tried to extend the xPINN 1D harmonic oscillator to a 2D paper, but again, given the fact that the code was hard-coded for a 1D problem and my inexperience in Python, I was unable to do this. 

The file "oscillator_PINN_COVID_daily_share.ipynb" is the file from the xPINN folder that I modified the most and thus I have included it separately. I changed the graphs for the plots and used it to run some different experiments. 

Finally, the xPINN folder contains all the other code from the paper. 


