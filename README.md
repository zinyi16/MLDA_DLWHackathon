# DLWHackathon - DentalAnywhere
This is the project submission for Team Incredibear to MLDA-EEE Deep Learning Week 2021 Hackathon  
Team members:
1. Kai Yang
2. Yee Hong
3. Zin Yi

### Problem Statement
In 2021, more than 54,000 adults in US were diagnosed with oral cancer. Out of those diagnosed, about 10,000 people has died, resulting in a death rate of roughly 1 person per hour. Everyday, there are approximately 132 new individuals diagnosed with oral cancer. While the number of oral cancer cases is on the rise, more than 640,000 new cases are estimated to occur each year. The high death rate of oral cancer is not because it is hard to discover or diagnose, but due to the cancer often being discovered late in its development. The warning signs of pre-cancerous growths and early oral cancers include ulcers, sores and red or white patches in the mouth which do not heal. As they are usually painless at this stage, most people either ignore them or self-medicate using gels. As a result, most patients are diagnosed at the later stages of oral cancer which is more difficult to treat.

### Solution
DentalAnywhere is an image recognition sytem which is able to identify oral conditions such as ulcers, inflamation, flurosis etc., thus providing information on the users' oral health. It works based on an image classification model which learns the features of 12 different classes of oral condition and predicts the corresponding class of an input image. Transfer learning was applied using VGG-16, a pre-trained CNN model due to limited training dataset.

### Objective
The objective of this project is to create a multi-class image classification model to predict the oral condition based on the image input by users.

### What's Next for DentalAnywhere
With the current dataset, our model has obtained a training accuracy of about 60%.

Possible improvement to increase model performance:
- Use larger dataset with images which display the distinguishable freatures of each oral condition
- Data augmentation to generate more training data

The improved model can then be deployed to a web to perform the prediction of user's oral condition. 
