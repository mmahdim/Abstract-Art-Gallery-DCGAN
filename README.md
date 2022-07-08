# Abstract Art Gallery DCGAN
 ## Using DCGAN to generate abstract art
 
 In this project, the aim is to produce abstract art similar to the ones in https://www.kaggle.com/datasets/bryanb/abstract-art-gallery using Keras.

 In order for it to work, you need to put a Kaggle API key in your google drive.<br> 
 The first python notebook is just a plain DCGAN.<br>
 The second one is DCGAN with noise added to the discriminator in order to improve convergance.<br>
 The third one which performs the best utilizes **Wasserstein** loss function, and it mitigates mode collapse and vanishing gradient. You can see its results after 100 epochs below. You can also train for more epochs if you want to acieve better results. <br>
 ![image](https://user-images.githubusercontent.com/8644346/178071614-0d6797cf-3690-4ede-869a-52399631a820.png)

![image](https://user-images.githubusercontent.com/8644346/178037731-d1203a4d-ccc3-4b9f-ac42-ea405175fbf9.png)
