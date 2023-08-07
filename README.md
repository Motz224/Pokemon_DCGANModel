# Pokemon_DCGANModel
LOG:\
DCGAN based pokemon generator 20230803\
Result: epoch around 1000\
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/1f53ccb8-61be-4a0e-8bbc-a7d15953aac6)
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/eb733139-ebb4-4959-9aec-fa9141c4d83d)\
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/aab172f8-0b14-4a5e-920d-3a4e0c540b13)
![圖片](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/60ed077f-f6f5-4d75-b782-1e3a8c24de35)

Generator:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/01135d67-1a76-4f24-a846-1c84432630be)\
Discriminator:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/6eb2605b-64e2-4954-9151-c704d95a1911)

DCGAN based pokemon generator 20230804\
--pokemon dataset splited to training& validation\
--added data augmentation

When added dynamic dataset, which do data augmentation each training epoch, the model collapse\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/7d20cd16-0600-4c63-bba8-b4d319ba54ab)\
Generator: ReLU for each, last layer use tanh\
Discriminator: LeakyReLU for each, last use sigmoid

Removed sigmoid\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/04c9361e-14a8-4403-b7c0-c643ac2a832f)

DCGAN based pokemon generator 20230807\
Include:\
--data augmentation
--trainging class& validation class

Generator:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/4aa3f655-6b62-4eeb-a324-96169ea823ad)\
Discriminator:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/a3cd285c-4e99-49db-9057-fc649c36b564)

TrainingGIF:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/3cb5185f-e24f-482b-b5e7-b1af8bf7f9ef)\
Loss:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/3cdf723e-29cb-4baa-b6d2-b9dd3db8a920)\
Result:\
![image](https://github.com/Motz224/Pokemon_DCGANModel/assets/82391453/81d79edf-f8d5-4499-9e86-eb92650ae020)\
