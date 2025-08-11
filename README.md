This repository contains the MATLAB implementation described in our paper _"AINR: Automated Intrinsic Non-Rigid Registration for Accuracy Qualification of Complex Freeform Products in 3D Printing
"_ (accepted in IISE Transactions).

**Repository Structure**

**Toolbox/** – Please create a folder and store the core functions for mesh processing, including:
- Geometry Processing Toolbox https://github.com/alecjacobson/gptoolbox
- The toolbox from Bounded distortion matching of Gaussian Process Landmarks https://github.com/shaharkov/GPLmkBDMatch

**myfunction/** – Functions for deviation-aware shape segmentation and diffeomorphic registration.

**Data/** – Design and actual scan triangular meshes of a dental model (human data; use only for demonstration/visualization).

**Demo_Example.m** – Test script using the dental model; results match the pipeline in the paper.


**Citation**

The paper is accepted for publication in IISE Transactions and will be released online soon. Please cite it if you use this code. Citation details will be added upon release.

**Contact**

For questions or assistance, please contact weizhi.lin@sjsu.edu
