# SatelliteImaging-AmazonRainforest
 Classifying Satellite Images of the Amazon Rainforest

Download the Dataset from [**Planet: Understanding the Amazon from Space**](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data) on Kaggle. These files/folders are needed for training the model and performing inference:-
1. train_v2.csv
2. train-jpg.tar
3. test-jpg.tar
4. test-jpg-additional.tar

We place them in our working directory as shown below:- 
 <pre>
 ├─── AmazonPlanet.ipynb
 ├─── train_v2.csv
 ├─── train-jpg
      ├─── train_0.jpg
      ├─── train_1.jpg
      ├─── train_2.jpg
      ├─── ..
      ├─── ..
      ├─── train_40476.jpg
      ├─── train_40477.jpg
      └─── train_40478.jpg
 └─── test-jpg
      ├─── test_0.jpg
      ├─── test_1.jpg
      ├─── ..
      ├─── ..
      ├─── test_40667.jpg
      └─── test_40668.jpg
 └─── test-jpg-additional
      ├─── file_0.jpg
      ├─── file_1.jpg
      ├─── ..
      ├─── ..
      ├─── file_20520.jpg
      └─── file_20521.jpg

     
</pre>

Here, we have used **Fastai**, and after creating an ImageDataBunch, we finetuned a pre-trained Resnet50 to perform the Multi-label classification task.

**Note:** The **trained_model.pkl** file has been uploaded using **Git-LFS**.
