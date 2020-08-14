# Dissolved-Gas-Analysis
Dissolved Gas Analysis is used to find the fault in Transformers(partial corona discharge, high energy arc fault, low energy arc fault, is hot spot in oil, hot spots in paper etc). Recently people started applying Machine Learning techniques to find the faults. I applied XGBoost model for the tabular data and even with less data also I was able to get a decent accuracy.
People generally don't use Deep Learning models for tabular data but using #cAInvas platform I created a notebook which converts each row of the the .csv file into image and treated Dissolved gas analysis as a image classification problem and was able to achieve a decent accuracy which I feel could be improved using more data.
By doing this DL method I can use #cAInvas 's deepC compiler and run this model on EDGE devices.
Check out the code for both model and converting the .csv file's rows into image.


