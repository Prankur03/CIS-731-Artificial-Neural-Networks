# CIS-731-Artificial-Neural-Networks

### Business problem

With the urbanization, almost everyone now has a vehicle. Most of the people have more than just 1 vehicle which has led to rapid increase in the number of the vehicles. This huge increase in the number of the vehicles has exacerbated the problem of the traffic congestion/jam, pollution emissions and safe travel. To solve this problem of growing of traffic jams and efficient traffic management, it has become important to predict the traffic flow or volume. Accurate prediction for the volume of the vehicles at a given time can help government to allocate more resources for creating the superefficient navigation systems. This forecast of traffic volume becomes important step in creating an intelligent transport system for the people of the country making it a safe to travel with reduced travel time. Also, it would provide guidance to the individuals to choose the best time to travel to avoid unnecessary delays due to roadblocks or take alternate route. Features like weather conditions and holidays would help us determine the traffic volume more accurately. 

To solve this business problem, we will be using artificial neural network on Metro Interstate Traffic Volume Data Set which has hourly traffic volumes and other features which include weather data, holiday data for a duration of 6 years from 2012 to 2018.

Other dataset would be the PEM (Performance Measurement System) data source that has the traffic volume data with features like type of vehicles passing, volume traffic etc. These datasets are Multivariate Time Series Data Sets where the traffic volume may have a seasonal effect based on the holidays or weather. 


### Our approach

First, we would clean the data, perform Exploratory Data Analysis, and scale the Metro Interstate Traffic Volume Dataset and convert it in a format which can be used to make predictions using the Deep Learning Algorithms. Also, we need to consider the cyclic and seasonal behaviors which is exhibited by the data. This seasonal behavior can be found during the holidays, weekdays or weekends, or for a specific time duration in a day. So, to capture this effect we would use Feed forward neural networks, back propagation through time (BPTT), LSTM and GRU Algorithms. We would want to try combination of different optimizers and parameters like Decay, Learning Rate etc. to see how the results would change by tuning the hyper parameters. Also, after using these standard state-of-the-art algorithms and their variations, we would want to try any combinations of LSTM’s or GRU layers which might give better results rather than using only 1 of them at a time. 
If time permits, we may want to look at the spatial data in terms of the traffic flow images along with these temporal data sets in order to predict the traffic better and to have a mixture of long term and short-term traffic volume forecast.   





### Evaluation of our approach

We will be building different models for the data collected from the resources listed and compare the results to the actual traffic volume. As for the evaluation of the models, we will be using Loss functions like MSE and MAE as we have a continuous variable as a target. We would also look at the computational effort needed in terms of weight changes to achieve sufficiently good results in terms of the Loss Function defined.  We will train our models using the hold out method and ensure that the models are not overfitting to build a robust and generalized model able to predict traffic volumes accurately. 
In order to evaluate and make comparison between the different models, we would see how well the algorithms with the same computational effort can forecast the future traffic volumes and how closely these algorithms can make the predictions for the unseen test data based on the learning. We would make changes to the training process based on the results obtained like tweaking the number of the weights, hidden layers, activation functions, or may use an RBF network instead of Simple network for the prediction. 

We are in the process of finding some research papers for this task and would see if we can implement something similar. Some of the research papers which we have gone through till now to explore our ideas about the problem to be solved are listed below. 

Research Papers referred for ideas:
   
•	Using LSTM and GRU neural network methods for traffic flow prediction
•	Improving Traffic Flow Prediction with Weather Information in Connected Cars: A Deep Learning Approach
