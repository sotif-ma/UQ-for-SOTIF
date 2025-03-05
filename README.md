# Uncertainty-Quantification-Methods-and-Datasets-for-SOTIF
This repository contains some of the uncertainty quantification methods mentioned and relevant datasets in the field of autonomous driving.
# Abstract

![fig1](https://github.com/user-attachments/assets/9219c69c-73a1-4bf2-9e53-3141b75f3127)

# SOTIF terminology framework

![fig2](https://github.com/user-attachments/assets/65fdd7b8-af07-4b05-928a-b58ff1409afe)

# Source of uncertainty
(1)	Errors caused by unknown data

(2) Errors caused by unknown data

(3) Errors and noise in the measurement system

(4) Overfitting and underfitting

(5) Inadequate model training

![fig3](https://github.com/user-attachments/assets/8eca9ba6-3bad-4a54-9859-4e12cb6d7390)

# New metrics for SOTIF perceptual tasks
We evaluate and analyze the methods involved in this paper according to the evaluation metrics

![fig444](https://github.com/user-attachments/assets/98d0e571-140c-48cf-bb51-4822b7a256fe)

# Various uncertainty methods
(1)	Bayesian method
![fig6](https://github.com/user-attachments/assets/20d671df-b170-4fa0-88ce-af8f42fca67a)

(2) Single deterministic method
![fig7](https://github.com/user-attachments/assets/8a445641-1b10-43a4-a162-3fc2ea3cade6)

(3) Spatial feature
![fig8](https://github.com/user-attachments/assets/042f3784-fdd6-43c2-beea-5a00cd673474)

(4) Distance method
![fig9](https://github.com/user-attachments/assets/a5488f37-a9e6-48a0-84c8-af3d4828b729)

(5) Dirichlet decomposition
![fig10](https://github.com/user-attachments/assets/6eb9a8e8-80c0-4540-95e8-0440adec3996)
![fig11](https://github.com/user-attachments/assets/cfc3a912-05f5-4a71-a89b-d725e886b581)

# Experimental results of various uncertainty methods under SOTIF evaluation system
The application of uncertainty quantification in complex scene detection is extensive and multi-dimensional. It can be used not only as a single perception detection method but also to optimize some OOD detection strategies to be practically applied to the perception field required by the SOTIF standard. The uncertainty quantification method has certain performance advantages compared with other methods, which benefit from the excellent representation ability of the distribution uncertainty to the input distribution, and some methods perform well in computational cost and real-time detection speed, which can well meet the requirements of the SOTIF standard. 

![fig333](https://github.com/user-attachments/assets/0beea30d-d63c-4137-9a9c-2ca5b8debd71)


# Datasets for autonomous driving
We split the SOTIF dataset into the id dataset, OOD dataset, and auxiliary dataset. The id data set was used for neural network training to improve the perception model's detection ability and enhance the expected function's security. OOD dataset is a test dataset with different distributions of training and data, which is used to evaluate the robustness and reliability of machine learning models, and test the ability of the model to detect unknown scenes and judge whether the intended function is safe enough. Auxiliary datasets are introduced to aid model training, and using them can produce better training results than only using ID data, and the prior distribution of the auxiliary data can fit the ID data within the long tail. In addition, the outlier exposure method will decrease detection performance due to the difference between auxiliary data and OOD data, so the study of auxiliary data sets is also very important.

![fig555](https://github.com/user-attachments/assets/e0d871a5-b807-4a08-a8ae-41077f8cac89)

