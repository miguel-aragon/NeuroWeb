# Data description (cosmic web)

For this project I am using the Bolshoi simulation, a very large simulation of a significant volume of the Universe. This is the website of the simulation, it is not relevant for the discussion but if you are interested (there are some nice images/videos showing various aspects of the simulation):

http://hipacc.ucsc.edu/Bolshoi.html

We already have density fields and the network of filaments/walls from an old project. 

Note that the data is 3D (data cubes). For clarity I will be showing projections over a part of the simulation box.

## Density
The figure below shows a projection of the density field. Bright areas are dense clusters of galaxies. Note how the clusters are interconnected by a network of filaments.

![picture](images/bolshoi_test_0_density.png)


## Clusters / soma
Here I applied a density threshold to highlight the dense clusters of galaxies. Clusters are the nodes of the network of filaments. So they are similar to the "soma" of a neuron.

![picture](images/bolshoi_test_0_density_delta_GE_300.png)

## Filaments / dentrites
The next image shows the network of filaments connecting clusters. Filaments are, in our context, equivalent to the dentrites (there is no functional equivalent to an axon I think). The filaments were computed using the Spine algorithm (only for reference):

http://adsabs.harvard.edu/abs/2010ApJ...723..364A

![picture](images/bolshoi_test_0_filaments.png)

## Cosmic neurons
Here we see the clusters and filaments together

![picture](images/bolshoi_test_0_neurons.png)
