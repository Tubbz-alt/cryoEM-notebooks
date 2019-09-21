# cryoEM-notebooks

This repo contains information that we deem useful in understanding the end-to-end computational problems of cryoEM and cryoET. Specifically, we develop jupyter notebooks that walks us through the mathematical and computational operations required to reconstruct density maps from micrographs. Work in progress...

## Image formation model 
see notebook on [(github)](notebooks/ImageFormationModel/Image%20Formation%20Model.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/ImageFormationModel/Image%20Formation%20Model.ipynb)
### Microscope Architecture
#### Electron Gun (shot-noise, coherence, ...)
#### Sample delivery
#### Detector (DQE, MTF, ...)
### Theoretical Limits
#### CTF
#### Origin of Noise
#### Beam Induced Motion
### Simulations
#### Simulate particles 
see notebook on [(github)](notebooks/ImageFormationModel/Projection.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/ImageFormationModel/Projection.ipynb)
#### Simulate micrographs 
see notebook on [(github)](notebooks/Simulating%20data.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/Simulating%20data.ipynb)
#### Tilt Series for Tomo

## Micrographs: movies to picture
### Beam Induction Motion Correction

## Particles
### Particle Picking
### 2D Classification and Particle Rejection

## 3D Reconstruction - Inverse Problem
### Pose Estimation
### Denoising Images
### Denoising Volumes
### Deconvolution
#### Wiener filtering
### Volume Reconstruction

## Heterogeneity
### Multibody Refinement with RELION - prepare input 
see notebook on [(github)](notebooks/VolumeHeterogeneity/Automated%20Body%20Definition.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/VolumeHeterogeneity/Automated%20Body%20Definition.ipynb)
### 3D Variability with cryoSPARC
### Visualization
### Heterogeneity Analysis

## Tomograms vs SPA (2d vs 3d)
### Tomogram Reconstruction Methods

## Interfaces and Pipelines
### Image formats and IO 
see notebook on [(github)](notebooks/Interfaces/Simple%20IO%20and%20Visualisation.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/Interfaces/Simple%20IO%20and%20Visualisation.ipynb)
### Create particle stacks 
see notebook on [(github)](notebooks/Interfaces/Create%20Particle%20Stacks.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/Interfaces/Create%20Particle%20Stacks.ipynb)
### Interfacing with OSF 
see notebook on [(github)](notebooks/Interfaces/Using%20OSF%20to%20retrieve%20and%20store%20datasets.ipynb) [(colab)](https://colab.research.google.com/github/slaclab/cryoEM-notebooks/blob/master/notebooks/Interfaces/Using%20OSF%20to%20retrieve%20and%20store%20datasets.ipynb)

