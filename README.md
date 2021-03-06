# MVAI
Created by Spencer Zhang.

Email: zhangchunzhe@scdc.sh.cn / sepmein@gmail.com

> AI applications on malaria vector control.

> This project provides several proposals for the application of artificial intelligence technology in the malaria control. 

> The document is written in [markdown](https://daringfireball.net/projects/markdown/syntax) syntax.

> This project is currently been actively updated. To check current status, please check the [insights](https://github.com/sepmein/mvai/pulse) tab.


## Table of Content
- [Possible Applications](#Possible-Applications)

- [Papers](#Papers)

- [News](#News)

- [Projects](#Repositories)

---

## Possible Applications

### 1. Strengthening Surveillance System

### 1.1. Automated Adult Mosquito Identification

Deep-learning software uses artificial neural networks mimicking the brain to allow computers to recognize abstract patterns. In 2012, one concurrent neural network(CNN) model called AlexNet achieved 15.3% error rate(26.2%, second place) in the [ImageNet](http://image-net.org) challenge. ImageNet challenge is a challenge for the computer algorithm to classify on 14M images on 1000 categories. AlexNet was a huge success on the computer vision. Since then, the accuracy of CNN models(GoogleNet, ResNet, SENet) gradually increased, and surpassed the average human levels(2.25% error rate, 2017).

Mosquitoes transmit malaria, yellow fever, dengue and encephalitis. The mosquito entomology surveillance required trained entomologist to identify the mosquito species. The microscopy currently used to quantify the parasites requires well-trained entomologists, and many malaria-prone areas don’t have enough of those, or the resources to train new ones. 

By using CNN models, it's possible to create a web service that could automatically differentiate different species of mosquitoes. Based on the mosquito image(s) given by the user, the online identification model would give the result of classification of the image and the confidence of the results. So anyone that could access to the internet could take pictures of the mosquitoes that transmit malaria and send the photo to the web service and get the identification result.

In the future, it's possible to create a off-line version of these online service.

Mosquito image(s) -> Identification model -> Results

For example:

![Image of the model example](https://github.com/sepmein/mvai/blob/master/mosquito_identification_example.jpg?raw=true)

#### 1.1.1. Why?

##### Benefits
- **Reducing the overall cost of the global entomological surveillance network**

    **Conducting entomological surveillance often require trained entomologist.** And training a qualified entomologist require vast amount of investment. The lack of entomologist restrained the ability of the surveillance network to achieve a higher coverage. 

    By automating the identification process, AI could make the surveillance much more easier to implement. The cost of training and salary could be reduced.

- **Improving data quality**

    The ability of entomologist varies. Automating the process with an intelligent model can alleviate the shortfall of trained personnel in under-resourced countries.

    With the accumulation of vector images, the performance of AI model will gradually increase. Finally, it could approach human expert level. The performance of the final model would 
    
    Artificial intelligence program can do it more reliably than most humans.

- **Gather more data**

    Data is key resource in the future. By providing online prediction services globally, model provider could collect a great amount of vector pictures. More pictures could increase the precision of the model.

##### Comparing to Human Performance

In the last few years, a lot more machine learning teams have been talking about comparing the machine learning systems to human level performance. Because of advances in deep learning, the algorithms are suddenly working much better and have become much more feasible in a lot of application areas for machine learning.

![human vs AI performance](https://github.com/sepmein/mvai/blob/master/AI%20vs%20human%20performance.jpg?raw=true)

*Figure 2 - AI model accuracy vs human performance*

#### 1.1.2. How to do?

##### Data Collection
Using current entomological network
*the current situation of the surveillance network globally*

Mosquito surveillance network
Collect mosquito
Photograph the mosquito
Upload to the database
Identification by the Experts

##### Model -> Performance -> Data -> Model cycle

##### Building a new data Cooperation mechanism in the AI era
- AI needs a large amount of data
- It's unfeasible for one organization to gather all the 

##### Overall costs for the project

##### Cost Efficiency

##### Possible ways to reduce the cost of building this identification model
Transfer Learning

#### 1.1.3. What to do?

##### 1.1.3.1. Methods
Building an effective neural network model requires careful consideration of the network architecture as well as the input data format.

###### 1.1.3.1.0. Data preprocessing
Data Preprocessing is a technique that is used to convert the raw data into a clean data set. Pre-processing refers to the transformations applied to the images before feeding it to the algorithm. In other words, whenever the data is gathered from different sources it is collected in raw format which is not feasible for the analysis. 
In the mosquito image classification problem, algorithms should **transform the image to matrices**. The most common image data input parameters are the number of images, image height, image width, number of channels, and the number of levels per pixel. Typically we have 3 channels of data corresponding to the colors Red, Green, Blue (RGB) Pixel levels are usually [0,255].
- Data Augmentation

###### 1.1.3.1.1. Building AI Model

Concurrent neural network(CNN) model was been proven the best model to identify image. The model could  

###### 1.1.3.1.2. Model Selection

###### 1.1.3.1.3. Model Initialization

###### 1.1.3.1.4. Model Training

Machine learning, gradient descent

###### 1.1.3.1.5. Model Evaluation

###### 1.1.3.1.6. Prediction

##### 1.1.3.2. Tools
Artificial Intelligence(model building, training, evaluation):
- [Google Tensorflow](https://tensorflow.org)
- [Facebook Pytorch](https://pytorch.org)
- [Keras](https://keras.io)

Matrix Manipulation
- [numpy](http://www.numpy.org)

Data preprocessing
- [pandas](https://pandas.pydata.org/)
- [scipy](https://www.scipy.org/)

Data Visualization
- [Matplotlib](https://matplotlib.org)

Coding Language
- [Python](http://python.org)

##### 1.1.3.3. Hardware
GPU

CPU

Server

Hard Drive

---

### 1.2. Automated Larvae Identification
TODO

---

### 2. Supporting Policy Making 
TODO

---

### 3. Development
TODO

---

## Papers
Automated microscopy for routine malaria diagnosis: a field comparison on Giemsa-stained blood films in Peru
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6157053/


---

## News
Artificial Intelligence Offers a Better Way to Diagnose Malaria
https://www.technologyreview.com/s/600779/artificial-intelligence-offers-a-better-way-to-diagnose-malaria/

AI model 
https://futurism.com/the-byte/debug-project-ai-mosquitoes


---

## Repositories
Mosquito classifier 55.3% accuracy in distinguishing *Culex*, *Aedes*, *Anopheles*
https://github.com/ultimatepritam/mosquito_classifier

OpenMalaria - A simulator of malaria epidemiology and control
https://github.com/SwissTPH/openmalaria
