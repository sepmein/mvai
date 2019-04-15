# MVAI
> AI applications on malaria vector control.

> This project provides several proposals for the application of artificial intelligence technology in the malaria control. 

> The document is written in [markdown](https://daringfireball.net/projects/markdown/syntax) syntax.

> This project is currently been actively updated. To check current status, please check the insight tab.


## Table of Content
[Possible Applications](#Possible-Applications)

[Papers](#Papers)

[News](#News)

[Projects](#Repositories)

## Possible Applications

### 1. Strengthening Surveillance System

#### 1.1. Automated Adult Mosquito Identification

In 2012, one concurrent neural network(CNN) model called AlexNet achieved 15.3% error rate(26.2%, second place) in the [ImageNet](http://image-net.org) challenge. Imagenet challenge is a challenge for the computer algorithm to classify on 14M images on 1000 categories. 

AlexNet was a huge success on the computer vision. Since then, the accuracy of CNN models(GoogleNet, ResNet, SENet) gradually increased, and surpassed the average human levels(2.25% error rate, 2017).

Mosquitoes transmit malaria, yellow fever, dengue and encephalitis.

Current identification net

By using CNN models, it's possible to create a web service that could automatedly differentiate different species of mosquitoes.

Based on the mosquito image(s) given by the user, the online identification model would give the result of classification of the image and the confidence of the results.

mosquito image(s) -> identification model -> results

For example:

![Image of the model example](https://github.com/sepmein/mvai/blob/master/mosquito_identification_example.jpg?raw=true)


##### 1.1.1. Why?

###### Benefits
- Reducing the overall cost of the global entomological surveillance network

    **Conducting entomological surveillance often require trained entomologist.** And training a qualified entomologist require vast amount of investment. The lack of entomologist restrained the ability of the surveillance network to achieve a higher coverage. 

    By automating the identification process, AI could make the surveillance much more easier to implement. The cost of training and salary could be reduced.

- Improving data quality

    The ability of entomologist varies. Automating the process with an intelligent model can alleviate the shortfall of trained personnel in under-resourced countries.

    With the accumulation of vector images, the performance of AI model will gradually increase. Finally, it could approach human expert level. The performance of the final model would 
    
    artificial intelligence program can do it more reliably than most humans.

- Improving data feasibility

    By providing prediction services to the world, model provider could collect more and more vector pictures. More pictures could increase the precision of the model.

Quickly, cheaply and accurately.

###### Importance of entomological surveillance network
Differences of different mosquitoes
Differences in density, resistance, ability to transmit malaria

###### Comparing to Average Human Performance
Will surpass average human performance.

###### Comparing to Experts Performance

##### 1.1.2. How to do?

###### Data Collection
Using current entomological network
*the current situation of the surveillance network globally*

Mosquito surveillance network
Collect mosquito
Photograph the mosquito
Upload to the database
Identification by the Experts

###### Model -> Performance -> Data -> Model cycle

###### Building a new data Cooperation mechanism in the AI era
- AI needs a large amount of data
- It's unfeasible for one organization to gather all the 

###### Overall costs for the project

###### Cost Efficiency

###### Possible ways to reduce the cost of building this identification model
Transfer Learning

##### 1.1.3. What to do?

###### 1.1.3.1. Methods
1.1.3.1.0. Data preprocessing

- Data Augmentation
- Transform images to data

1.1.3.1.1. Building AI model

Concurrent neural network(CNN) model was been proven the best model to identify image. The model could  

1.1.3.1.2. Model Selection

1.1.3.1.3. Model Initialization

1.1.3.1.4. Model Training

Machine learning, gradient descent

1.1.3.1.5. Model Evaluation

1.1.3.1.6. Prediction

###### 1.1.3.2. Tools
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

###### 1.1.3.3. Hardware
GPU

CPU

Server

Hard Drive
#### 1.2. Automated Larvae Identification
TODO
### 2. Supporting Policy Making 
TODO
### 3. Development
TODO
## Papers
TODO
## News
TODO

AI model 
https://futurism.com/the-byte/debug-project-ai-mosquitoes

## Repositories

Mosquito classifier 55.3% accuracy in distinguishing *Culex*, *Aedes*, *Anopheles*
https://github.com/ultimatepritam/mosquito_classifier