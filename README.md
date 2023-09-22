# Parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network
## Abstract
The repository contains the Python implementation using the PyTorch framework to parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network approach. The method, referred to as the Runge–Kutta Physics-Informed Neural Network (RK-PINN) based on the combination of the Physics-Informed Neural Network (PINN) and Runge-Kutta algorithm. Drawing inspiration from classical numerical integration solution rules for differential equations, a new recurrent neural network architecture is designed for modeling. PINN cells are embedded as the basic integration units of the architecture to introduce prior physics-based biases. The methodology is depicted in the figure below.  
 !!!!! ![alt text](.png)





If you find this work useful in your research, you can cite our paper !!!!!!www  or  as per the following:  !!!!!bib
## Contains
***Lorenz_RK4PINN.ipynb*** contains code for jupyternotebook 

***R28_Lorenz_data_train_noise1.npy*** contains the Lorenz dataset used for training

***models*** folder contains the trained model and the output images from the training process：

Estimation process for the parameters of the Lorenz system  !!!!!! ![alt text](.png)
