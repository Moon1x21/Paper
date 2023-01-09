
# NeRF:Representing Scenes as Neural Radiance Fields for View Synthesis
# author: Ben Mildenhall* Pratul P. Srinivasan* Matthew Tancik* Jonathan T. Barron Ravi Ramamoorthi Ren Ng
## url: https://arxiv.org/pdf/2003.08934.pdf#page=16&zoom=100,45,564


## Summary of paper:

* Using a MLP, which input is a single 5D coordinate (x,y,z, view direction) and output is the density and view-dependent color. 
* Mapping the input to a higher dimensional space to let the model easily approximate a higher frequnecy function. 
* Optimize two network "corase" and "fine" simultaneoulsy to evaluate only meaningful raddiance field.
