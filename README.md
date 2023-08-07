# Pokemon_DCGANModel
LOG:\
DCGAN based pokemon generator 20230803\
epoch around 1000\
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/1f53ccb8-61be-4a0e-8bbc-a7d15953aac6)
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/eb733139-ebb4-4959-9aec-fa9141c4d83d)\
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/aab172f8-0b14-4a5e-920d-3a4e0c540b13)
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/60ed077f-f6f5-4d75-b782-1e3a8c24de35)

DCGAN based pokemon generator 20230804\
--pokemon dataset splited to training& validation\
--added data augmentation

When added dynamic dataset, which generate random dataset each training epoch, the model collapse\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/7d20cd16-0600-4c63-bba8-b4d319ba54ab)\
Generator: ReLU for each, last layer use tanh\
Discriminator: LeakyReLU for each, last use sigmoid

Removed sigmoid\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/04c9361e-14a8-4403-b7c0-c643ac2a832f)
