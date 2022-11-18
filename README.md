# MiceMapper

This project is under the supervision of Tim Murphy lab at UBC: https://murphylab.med.ubc.ca/

To develop a method that extract fully dense, high-dimensional representation of mice behaviour and unified them in the same scale, we develop this project that perform dense tracking on mice's body based on the GAN-supervised spatial transformation network from https://github.com/wpeebles/gangealing 

Our model can spatially transform the uncongealed mice to a general mice's representation. Using this information, we can densly map each individual pixel back to the uncongealed mice's body in each video frames.

This method allows analysis of dense-pose and highly fine-detailed motion on mice's body

Some sample will be demonstrated below. Due to credentials reason, trainin method, model checkpoints and analysis code is provided only by request of permission

# Dense-tracking of mice

![ezgif-4-06b7536978](https://user-images.githubusercontent.com/87956324/202588677-adf7e82c-fae8-4803-9b4f-b01bd5c047e8.gif)

# Spatial-temporal representation of mice's body part motion

![ae6bb4e782e3646b29165948c265051](https://user-images.githubusercontent.com/87956324/202588897-35f5a8b2-0d74-4088-8411-0a0a95dcde2e.jpg)




Activation heatmap of motion on general mice template

![image](https://user-images.githubusercontent.com/87956324/202589116-868a5589-e8a1-49d8-a756-892a0d1099b8.png)
