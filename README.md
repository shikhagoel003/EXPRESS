# EXPRESS

Train and Test Data

quad_1.csv is train data for the model 

quad_2_3_4.csv is test data for the model.

support_vector.ipynb is the python script used to train and test the model.

![Screenshot 2024-09-21 200617](https://github.com/user-attachments/assets/5d004361-bd97-48b7-a6e0-7482d79f1c79)

For EXPRESS-2.0, we consider various combinations of CNNs to create a diverse dataset. These combinations include --- (i) Same CNN on all DPUs, (ii) all different CNNs on all DPUs, (iii) combinations of different number of CNNs, where the number of DPUs determines the selection of CNN combinations, and (iv) a few random combinations of CNNs. Each CNN is mapped to a unique DPU. 
To prevent a large increase in the design space, we consider only the best bus configuration for EXPRESS-2.0 

