Questions I explored this summer: 
1. Can we create a more efficient, simplified model for a complex system that still accurately captures the physics of the system?
2. How can we make decisions when we have limited and sparse data?
3. A simplified model isn't perfect, so how confident can we be in our model, if we want to make better decisions?

I explored these questions through Bayesian calibration and uncertainty quantification of a Cahn-Hilliard surrogate model.  
This model is based on the Cahn-Hilliard partial differential equation that models the evolution of self-assembling nanoscale block copolymers.  
We investigated calibrating the unknown parameters of this equation to Molecular Dynamics data, of which we only had 5 simulations.  Therefore, we also wanted to quantify uncertainty about the calibration. 
We accomplished this through Bayesian calibration and Markov Chain Monte Carlo techniques.  


The Multifaceted Mathematics for Digital Twins (M2dt) collaboration aims to research and design hierarchies of digital twins for various systems. Nanoscale block copolymers (BCP) specifically are important for making templates and membranes in chip lithography, battery membranes, viral-filtration membranes, and more.  BCP self-assembly have an overwhelmingly complex design space.  We want to predict BCP behavior at different fidelities and computational expense, which can be used to inform decisions in an optimal experimental design framework.  


This repo contains
- Report
- Poster
- Ensemble of simulations from the Cahn-Hilliard surrogate model (Spectral solver implemented in C++)
- List view of simulation final states.  
- A sample pairs plot (information about correlation between parameters)
- Sample posterior chains over one parameter.  


Brookhaven National Laboratory:  https://www.bnl.gov/compsci/mathematics/applied/m2dt.php 

Sandia National Laboratory:  https://www.sandia.gov/app/uploads/sites/127/2024/09/M2dt_poster_sept_2024.pdf 

University of Texas:  https://m2dt.oden.utexas.edu/ 
