# CS5340-Pedestrian_intention
This project is to demonstrate the uncertainty of HMM and KF in describing pedestrian intentions. The experiment uses ETH data set to try HMM and KF for pedestrian trajectories prediction, and trains the two models online and offline respectively. During the experiment, the prediction variance of the model at each time step is used to describe the uncertainty of the trajectory in the modeling, and the RMSE is counted during the experiment. In terms of pedestrian intention, the number of real pedestrians crossing the road in ETH data set is counted and compared with the number predicted by the models, and AUC and PR are calculated to measure the accuracy of the model


Uncertainty converges overtime as shown in the graph below.

![Screenshot (395)](https://user-images.githubusercontent.com/65244703/166104219-419ba466-b544-4b5f-99df-24f130320313.png)
