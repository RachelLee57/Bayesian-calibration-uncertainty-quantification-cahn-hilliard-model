Questions I explored this summer: 
1. Can we create a more efficient, simplified model for a complex system that still accurately captures the physics of the system?
2. How can we make decisions when we have limited and sparse data?
3. A simplified model isn't perfect, so how confident can we be in our model, if we want to make better decisions?

I explored these questions through Bayesian calibration and uncertainty quantification of a Cahn-Hilliard surrogate model.  
This model is based on the Cahn-Hilliard partial differential equation that models the evolution of self-assembling nanoscale block copolymers.  
We investigated calibrating the unknown parameters of this equation to Molecular Dynamics data, of which we only had 5 simulations.  Therefore, we also wanted to quantify uncertainty about the calibration. 
We accomplished this through Bayesian calibration and Markov Chain Monte Carlo techniques.  


This repo contains
- Report
- Poster
- Ensemble of simulations from the Cahn-Hilliard surrogate model (Spectral solver implemented in C++)
- List view of simulation final states.  
- A sample pairs plot (information about correlation between parameters)
- Sample posterior chains over one parameter.  
