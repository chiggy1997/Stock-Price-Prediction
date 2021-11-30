# Stock-Price-Prediction
- In this project, I trained a Ridge regression model and deep neural network model to predict future stock prices.
- The AI model will be trained using historical stock price data  along with volume of transactions.


## 1. Overview :				
### a. Goal :	
* Based on volume and price data , can we predict stock prices?			
* Why?			
* Because while investing other peoples money we need to be really careful and we need real data to support our decisions rather than intuition			
	
				
### b. Impact :	
* Optimization and revamp which improved the accuracy by 12%			
				
### c. Challenges Faced :	
* Reshaping data while feeding into the model			
* Optimization which needed multiple level of changes  and multiple runs plus going through numerous research papers.			
				
### d. Interesting findings :	
* With only a few layers we can get good accuracy.			
				
## 2. Code and resource used :	
* Data manipulation:	Pandas		
* Visualisation    :	Plotly and matplotlib		
* Regression	     :  Sklearn		
* Metrics	     :  R2score		
* Deep Learning    :  Tensorflow, keras		
				
				
## 3. About the data :				
				
				
## 4. Data Preprocessing :	
 * Took data of all stocks and combined them in a single dataframe containing only the strike price and close price			
 * Time based splitting			
 * Normalization			
				
## 5. Visualisation :	
* Histogram of returns data in matplotlib.py and plotly express to understand its distribution			
* Volatility vs time plot to observe the change in volatily over time.			
* Price vs time to observe the stock returns over time			
				
## 6. Modelling :	
* Ridge regression with accuracy as metrics.			
* LSTM model with following layers			
* Optimizer used was ADAM 			
* Loss taken was categorical mean squared error and metrics taken as accuracy.			
				

