# ROCK IDENTIFICATION USING DEEP LEARNING
# About the Project
```diff
- text in red
+ text in green
 text in orange
# text in gray
@@ text in purple (and bold)@@
```
### This project is basically a small prototype of rock identification using deep-learning ([fast.ai](https://www.fast.ai) - which is a fast and accurate neural net library for deep learning) which classify granite and obsidian rock just by looking at the uploaded image. This is just a prototype which can be further developed to make it a complete rock identification webapp.
![block diagram](https://drive.google.com/uc?export=download&id=1mTYrf_aT8bqb-7Yz3TXjSgQ7VWYTxfwM)
# Why I choose Granite and Obsidian?

### In deep learning, we need to train our model by feeding in datasets to make the model accurate and error free. The more data you feed in, lesser would be the chance of error. In this case, dataset refer to images of granite and obsidian that we initially need to feed in using python to teach our model so that it can diffrentiate both the rock.
### Image database of granite and obsidian is quite large which help me to train my model error free. 
### I used 189 images of granite and 268 images of obsidian out of which 70% of the dataset is used for training and rest are used for validation purpose.

# Software/Library used in the Project
⦁	**Google Colab** - to train the model.\
⦁	**Visual studio code** - to code backend and develop the website.\
⦁	 **Fast.ai** - helped me to apply deep learning to practical problems quickly and reliably.\
⦁	**Render** - for deploying my webapp.\

# Breaking Down the Process of Model Building

## **There are four steps involved in model building/training :**

⦁	**Stage 1**: Loading and pre-processing the data
Data is crucial as far as deep learning models are concerned. Our image recognization model will perform well if we have a good amount of images in the training set. Also, the shape of the data varies according to the architecture/framework that we use.
Hence, the critical data pre-processing step is very important.
In order to see how our model performs on unseen data, we need to create a validation set. This is done by partitioning the training set data.
In short, we train the model on the training data and validate it on the validation data. Once we are satisfied with the model's performance on the validation set, we can use it for making predictions on the test data. \
![train model](https://drive.google.com/uc?export=download&id=1YmN0SG4zRwvHy2ES5XFX9lEQfKXoRRmP)
 
⦁	**Stage 2**: Training the model
For training the model, we require:\
⦁	Training images and their corresponding tags\
⦁	Validation images and their corresponding tags \
We also define the number of epochs in this step which is the number of passes of the entire training dataset the machine learning algorithm has completed. More epoch, lesser would be the error rate. \
 ![train model](https://drive.google.com/uc?export=download&id=1VkXS-CNDa0F7OHJOttSXj3jzGue9TbjC)
 
In the above picture, you can see that i have run 4 cycles (epoch 0-3) and you can clearly figure out that the error rate is keep decreasing after each epoch cycle which is justifying our statement, more epoch produce lesser error rate.

⦁	**Stage 3**: Estimating the model's performance
Finally, we load our test data (in our case images of obsidian and granite) and predict the classes for these images using the trained model. \
![train model](https://drive.google.com/uc?export=download&id=1l7IPdWXee8Jlv0ME8JmGhmYgdwM4iiVb)

# Application of Image Recognization in the field of Geology
## a.	Onsite Rock Sample Identification
Idea- We can extend this project to create an android app containing datasets of all the rocks to make rock identification process convinient and at the same time handy.

## b.	To explore mine deposits using images from Google Earth ( satellite images )
Idea- We can find out probability of finding out a perticular mine deposit in a specific region by collecting satellite images of that region from Google Earth and using it as a test data.

 

## c.	Temperature mapping using Histogram of photographs
Idea- We know that the histogram of a photograph contains the color information of that perticular image which can be processed and used as test data to detect temperature.\
![histogram](https://drive.google.com/uc?export=download&id=1CAm4EDSBerK0EtceSXZLXcARQnzMaQny)

With the help of this :\
⦁	 We can predict the cooling rate of lava/magma.\
⦁	We can study about the Thermal expansion of minerals present in the rock.\
⦁	We can study about effect of temperature on rock weathering.\



# Conclusion
I have successfully able to create a webapp which can distinguish between granite and obsidian by processing photo data using deep learning. I came to understand that the application of deep learning is vast touching every field, geology being one of them. 
While working on this project, i came to know that there is lack of datasets in geology as i did not find suffient images (in deep learning more than 1000 images are required for each category to train our model error free) making my model prone to errors.
Therefore, all the geology enthusiast should release there findings/images under certain license so that some big development in this field could occur using deep learning.


 
      
