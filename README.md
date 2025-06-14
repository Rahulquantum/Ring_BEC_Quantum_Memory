MIT License (see License file)

Copyright (c) 2025 Nilamoni Daloi, Rahul Gupta, Aritra Ghosh, Pardeep Kumar, Himadri Shekhar Dhar, and M. Bhattacharya

**This repository contains programs to calculate Fidelity for the storage and retrieval of superposition and entangled OAM photon states into the Ring BEC**

The primary governing equation which we simulate here is:

![equation](https://latex.codecogs.com/png.image?%5CLARGE%20%5Cdpi%7B110%7D%5Cbg%7Bwhite%7D%5Cbegin%7Bequation%7DH/%5Chbar=-%5Ctilde%7B%5CDelta%7Da%5E%5Cdagger%20a&plus;%5Comega_c%20c%5E%5Cdagger%20c&plus;%5Comega_d%20d%5E%5Cdagger%20d&plus;G(X_c&plus;X_d)a%5E%5Cdagger%20a&plus;i(%5Cvarepsilon_ca%5E%5Cdagger-%5Cvarepsilon%5E*_c%20a)&plus;i(%5Cvarepsilon_p%20a%5E%5Cdagger%20e%5E%7B-i%5Cdelta%20t%7D-%5Cvarepsilon%5E*_p%20a%20e%5E%7Bi%5Cdelta%20t%7D)&plus;4%5Ctilde%7Bg%7DN(c%5E%5Cdagger%20c&plus;d%5E%5Cdagger%20d)&plus;2%5Ctilde%7Bg%7DN(c%20d&plus;c%5E%5Cdagger%20d%5E%5Cdagger).%5Cend%7Bequation%7D
)

This describes the interaction of RING BEC sideband modes c and d interacting with cavity photon mode a, driven with a signal pulse and a probe pulse

Authors: [Nilamoni Daloi](mailto:nilamoni123@gmail.com), [Rahul Gupta](mailto:rahul.quantumfield@gmail.com), [Aritra Ghosh](mailto:ag34@iitbbs.ac.in), [Pardeep Kumar](mailto:pardeep.kumar@mpl.mpg.de), [Himadri S. Dhar](mailto:himadri.dhar@iitb.ac.in) and [M. Bhattacharya](mailto:mb6154@gmail.com)

Research Article: Cavity Optomechanical Quantum Memory for Twisted Photons Using Ring BEC, Nilamoni Daloi, Rahul Gupta, Aritra Ghosh, Pardeep Kumar, Himadri S. Dhar and M. Bhattacharya, 	[arXiv:2506.06651](https://doi.org/10.48550/arXiv.2506.06651).

How to run?
You will need to [install Qutip and the Scipy, Numpy](https://qutip.org/docs/4.7/installation.html) packages to run the Jupyter Notebook ("*.ipynb").

You also need [Jupyter](https://jupyter.org/install) to open the notebook, but you can also use [VS Code](https://code.visualstudio.com/download) instead.

Each notebook in main_text_figures folder can create a specific plot, similar to as it appears in our main research article, the file parameters.ipynb contains all relevant parameters there.
Figures/plots that appear in the supplemental part of our research article can be obtained by codes in folder named supplemental_figures.
