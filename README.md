# Session-5.4-Restaurant-tips-analysis
**1.The First Steps**
-#Data import # PUT YOUR CODE HERE

import pandas as pd
import matplotlib as plt

#Then load data from the following link: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
#PUT YOUR CODE HERE
data = pd.read_csv("https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv")

#Let's take a look at the first 5 rows to be sure, that data is loaded properly:     
#PUT YOUR CODE HERE
data.head()

