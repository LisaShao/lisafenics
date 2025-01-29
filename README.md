# Diffusion in Non-Homogeneous Medium 
## Overview:
This project computationally designs a heterogeneous medium to exhibit a desired diffusion pattern. It focuses on solving diffusion Partial Differential Equations (PDEs) using FEniCS tool.
## Table of Contents:
### 1-D Diffusion Problem
### 2-D Diffusion in Homogeneous Medium
#### 1. Constant diffusion coefficient
### 2-D Diffusion in Heterogeneous Medium
#### 1. Circle domain diffusion coefficient
#### 2. Gaussian Random Field (GRF) diffusion coefficient

## 1D Diffusion Problem 
<div align="center">
<img src="https://github.com/user-attachments/assets/45469eee-f017-4563-aeea-436320319cf9" alt="Image Description" width="500"/>
</div>

(Follow the instructions by youtube video: https://www.youtube.com/watch?v=QpA7E4YHbyU&list=PLISXH-iEM4Jl0-G1CpvG-mhrV0233tG_D)
The results is like:
<div align="center">
  <img src="https://github.com/user-attachments/assets/57bb29a0-7796-41eb-8c28-1735c5c1a0d9" alt="Image Description" width="300"/>
</div>

## 2D Diffusion Problem
### 1. Constant diffusion coefficient:
Problem setup here:
<div align="center">
<img src="https://github.com/user-attachments/assets/ef2789eb-cd35-4400-a3ea-99105107ecc5" alt="Image Description" width="500"/>
</div>
The FEniCS simulation result is like: 

https://github.com/user-attachments/assets/52ab9e48-b447-442f-ac98-9e71158bd11d

## 2-D Diffusion in Heterogeneous Medium
### 1. Circle domain diffusion coefficient
Problem setup here: 
<div align="center">
<img src="https://github.com/user-attachments/assets/aa47db0f-90db-4676-b2c5-307132bf85c8" alt="Image Description" width="600"/>
</div>
The initial condition is like:
<div align="center">
<img src="https://github.com/user-attachments/assets/4da30007-6fed-463a-982b-8735c3c99d5b" alt="Image Description" width="500"/>
</div>
The FEniCS simulation result is like:

https://github.com/user-attachments/assets/0dcc05c8-758c-4d83-9e06-742f8599cdb8

### 2. Gaussian Random Field (GRF) diffusion coefficient
First setup the gaussian random field
(The gaussian random field generation code is reference to this website: https://colab.research.google.com/drive/1_ncib8xKnmhdi1dkyr9MjJePDOxAcygQ?usp=sharing#scrollTo=8aStvt52u5Jd)
<div align="center">
<img src="https://github.com/user-attachments/assets/45b5eb92-ee8d-41cb-803c-e6bced2677ee" alt="Image Description" width="500"/>
</div>
The IBVP is:
<div align="center">
<img src="https://github.com/user-attachments/assets/c61016c2-c9d5-4b2e-ac9d-f744d7275fe5" alt="Image Description" width="500"/>
</div>
When the initial condition is like this:
<div align="center">
<img src="https://github.com/user-attachments/assets/70be1de0-fd49-4f0b-ac9d-e74ec1f6d6e7" alt="Image Description" width="500"/>
</div>
The FEniCS simulation result is like(time step is 0.001s, start from 0.001s):

https://github.com/user-attachments/assets/20b19cc4-7732-4095-af2f-a4d146155d47

When the initial condition is like this:
<div align="center">
<img src="https://github.com/user-attachments/assets/fbb622aa-480e-43f6-8e31-9693f36c37a3" alt="Image Description" width="500"/>
</div>
The FEniCS simulation result is like(time step is 0.001s, start from 0.001s):

https://github.com/user-attachments/assets/a2cd954c-28e9-4c90-8cdd-b7635baa7eb8


## Inverse Problem:






