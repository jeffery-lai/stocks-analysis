# stocks-analysis

This project analyzes the stock trades made by Members of the US House of Representatives. Part one focuses mainly on analyzing the data, from cleaning the data to running a missingness analysis on N/A data. Finally, a hypothesis test is run to analyze the type of missingness that is observed. 

Part 2 then uses the cleaned data to make predictions based on the political affiliations of the parties who made the trades. The model uses a decision tree to attempt to predict if the transactions were made by Democrat or Republican parties using most available columns as feature variables. This model uses a Pipeline which seamlessly convert the data to a matrix that the decision tree then processes. Once the parameters of the decision tree are refined, CV Grid Search is then run on the decision tree to find the best hyperparameters for the model.
