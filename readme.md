# Deep Learning Essentials with Keras 
The final project for the Coursera course "Deep Learning Essentials with Keras" provided by IBM. The project consists of four parts, A through D, focusing on different thought worthy aspects to consider when training Deep Learning models. 
Each part is constituted as a Jupyter Notebook named after the respective part it covers. 

The project goal is to build a neural network regressor predicting the strenght of concrete. The dataset is provided in `concrete_data.csv.`
## Part A
We construct a 3-layer network(Input, 1xHidden, Output) trained for 50 iterations(this is persistant for all parts), 50 epochs each iteration. The model is evaluated based on the mean Mean-Squared Error(MSE) and the Standard Deviation of the achieved MSE. 
Training and test feature sets is not standardized during this section. 
### Results
PART A - Mean MSE: *53.22*, Standard Deviation: *16.26* <br>

## Part B
The first adjustment we perform is standardizing/normalizing the training and test feature dataset. 
### Results
PART A - Mean MSE: *53.22*, Standard Deviation: *16.26* <br>
PART B - Mean MSE: *57.57*, Standard Deviation: *47.52* <br>

## Part C
In addition to standardizing the feature sets, we increase the number of epochs to 100 and examine the effect. 
### Results
PART A - Mean MSE: *53.22*, Standard Deviation: *16.26* <br>
PART B - Mean MSE: *57.57*, Standard Deviation: *47.52* <br>
PART C - Mean MSE: *47.35*, Standard Deviation: *19.97* <br>

## Part D
The final adjustment we perform is creating a deeper model. We add two additional hidden layers with ten nodes each. 
### Results
PART A - Mean MSE: *53.22*, Standard Deviation: *16.26* <br>
PART B - Mean MSE: *57.57*, Standard Deviation: *47.52* <br>
PART C - Mean MSE: *47.35*, Standard Deviation: *19.97* <br>
PART D - Mean MSE: *53.43*, Standard Deviation: *14.78* <br>
