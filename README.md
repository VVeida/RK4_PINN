# Parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network
## Abstract
The repository contains the Python implementation using the PyTorch framework to parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network approach. The method, referred to as the Runge–Kutta Physics-Informed Neural Network (RK-PINN) based on the combination of the Physics-Informed Neural Network (PINN) and Runge-Kutta algorithm. Drawing inspiration from classical numerical integration solution rules for differential equations, a new recurrent neural network architecture is designed for modeling. PINN cells are embedded as the basic integration units of the architecture to introduce prior physics-based biases. The methodology is depicted in the figure below.  
 !!!!! ![alt text](.png)





If you find this work useful in your research, you can cite our paper !!!!!!www  or  as per the following:  !!!!!bib
## Contains
***RK4PINN_for_Duffing_SDOF.ipynb*** contains code for jupyternotebook 

***EL_Duffing_SDOF_noise1.npy*** contains the SDOF Duffing dataset used for training

Estimation process for the parameters of the SDOF Duffing system  !!!!!! ![alt text](.png)
