# Active Nematic Fluids on Riemannian 2-Manifolds
This repository contains the implementation and supplemental movies for the paper:

**Active Nematic Fluids on Riemannian 2-Manifolds**

*Cuncheng Zhu, David Saintillan, and Albert Chern*

## Installation of Houdini
The implementation is created using SideFX Houdini, utilizing its VEX and Python programming capabilities.
* **VEX**: A C-like shader language in Houdini that operates in a vectorized and multithreaded manner.
* **Python**: We use `numpy` and `scipy` within Houdini’s Python module to access standard numerical linear algebra tools.

### Getting Started
Houdini is freely accessible through its Apprentice license. 
For Houdini installation details and tutorials, please refer to the following resources:
* [Houdini Download](https://www.sidefx.com/download/)
* [Introduction to Houdini](https://cseweb.ucsd.edu/~alchern/teaching/houdini/)
* [Scipy installation](http://wordpress.discretization.de/houdini/home/advanced-2/installing-and-using-scipy-in-houdini/)

## Running the Project
1. Launch `nematic.hipnc` in Houdini (ensure digial asset `nmeatic.hdanc` is available).
2. Toggle a visualization node.
3. Press play &#9654; to start the simulation.

## Attribution

If you use this code in your academic projects, please cite our paper:

```bibtex
@article{zhu2024active,
  title={Active nematic fluids on Riemannian 2-manifolds},
  author={Zhu, Cuncheng and Saintillan, David and Chern, Albert},
  journal={arXiv preprint arXiv:2405.06044},
  year={2024}
}
