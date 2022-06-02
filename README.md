# Steel Defect Detection

The repository covers a project which aims to differentiate between different classes of steel defects utilizing the open-source data available on Kaggle. 

### School: 
    University of Chicago
### Program: 
    Master of Science in Analytics (MScA) 
### Class: 
    Machine Learning and Predictive Analytics MSCA 31009 4
### Professor: 
    Dr. Arnab Bose

### Team: 
1.	Ali Ahmad: aliahmad@uchicago.edu
2. Melody Feng: ylfeng@uchicago.edu
3. Kai Hayden: kaihayden@uchicago.edu

### Structure of the repository: 

1.	Data 

Incorporates a link to the publicly available kaggle data, which includes: 
a. train_images: contains all images for the training set 
b. test_images: all images for the test which require classification
c. train.csv: includes further feature information for the images found within the training data 

2. EDA:

Contains a notebook containing initial exploratory data analysis which factor into our data cleaning and model considerations.

3.	Models: 

Contains a separate notebook for each category of neural network utilized to create the image classification

a. CNN-1 
b. CNN-2 
c. CNN-3 
d. RNN
e. Transfer-Learning

#### Detailed Project Description: 

**Details related to data**


|    Dataset            |  Image Quality (pixel) |      Count      |             
|:----------------------|:----------------------:|:---------------:|
|    Train (labeled)    |         1600x900       |    12,568       |       
|    Test (unlabeled)   |         1600x900       |     5,506       |

After careful considerations derived from the EDA, we structure our data cleaning to engineer and train our models. We utilize various iterations with parameter tuning for CNN's, RNN's and transfer learning models to achieve the desired results. 

We examine binary accuracy and accuracy for the entire dataset. Precision, recall and F1-score are used for the entire dataset and each class separately as well. 







