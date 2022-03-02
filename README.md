# Machine Learning - Short Term Rental Rates

This project demonstrates a linear regression model for predicting the expected daily rate of short term rentals in my area. The daily rate prediction is valid only for the month you input as part of your query (e.g. December might have lower prices than June). The model was built with Python, SKlearn, and CSV data dumps from the website, AllTheRooms.com. This type of model might be used often for price recommendation algorithms in websites like AirBnB or Turo.

The model has an R2 and R2 adjusted score of 70% with an RMSE of 43. That means the model is pretty good at predicting the "right" daily rate for a rental based on the features of the property in question.

To simply use the model, you can download the pickle file and integrate it into your code (remember it was trained for my area only and may not accurately predict prices for your area). You can also download the Jupyter notebook and modify it for your own data.

Note that AllTheRooms.com requires a subscription to download their data and therefore the legality of uploading the source data from this project is questionable. 
