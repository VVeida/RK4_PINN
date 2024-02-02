# Parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network
This repository contains codes and data for the following publication:
* Zhai, W., Tao, D. & Bao, Y. [Parameter estimation and modeling of nonlinear dynamical systems based on Runge–Kutta physics-informed neural network](https://doi.org/10.1007/s11071-023-08933-6). Nonlinear Dyn 111, 21117–21130 (2023). 
## Abstract
The repository contains the Python implementation using the PyTorch framework to parameter estimation and modeling of nonlinear dynamical systems based on Runge-Kutta Physics-Informed Neural Network approach. The method, referred to as the Runge–Kutta Physics-Informed Neural Network (RK-PINN) based on the combination of the Physics-Informed Neural Network (PINN) and Runge-Kutta algorithm. Drawing inspiration from classical numerical integration solution rules for differential equations, a new recurrent neural network architecture is designed for modeling. PINN cells are embedded as the basic integration units of the architecture to introduce prior physics-based biases. The methodology is depicted in the figure below.  
[Flowchart of RK4-PINN](Figures/Figure1.png)



## Contains
***RK4PINN_for_Duffing_SDOF.ipynb*** contains SDOF Duffing code for jupyternotebook <br>
***EL_Duffing_SDOF_noise1.npy*** contains the SDOF Duffing dataset used for training <br>

***RK4PINN_for_Lorenz.ipynb*** contains Lorenz code for jupyternotebook <br>
***Lorenz_data_train_noise1.npy*** contains the Lorenz dataset used for training <br>


## Citation
Please cite the following paper if you find the work relevant and useful in your research:
```
@article{zhai2023parameter,
  title={Parameter estimation and modeling of nonlinear dynamical systems based on Runge--Kutta physics-informed neural network},
  author={Zhai, Weida and Tao, Dongwang and Bao, Yuequan},
  journal={Nonlinear Dynamics},
  volume={111},
  number={22},
  pages={21117--21130},
  year={2023},
  publisher={Springer}
}
```
