# Match_OR_NoMatch
Price Prediction for Airbnb listings

This project predicts the price for a listing on an online marketplace. The online marketplace of choice is Airbnb.
This project makes recommendations for the price that a host should list his/her rental space for on Airbnb by building a machine learning model using Python.
The reason we chose Airbnb data set is that there are multiple sources of Airbnb data available online.

We used dataset from insiderairbnb. Inside Airbnb has extracted data on a sample of the listings for many of the major cities on the Airbnb website.
http://insideairbnb.com/get-the-data.html 
Data set for Washington DC Listings is used.  Why Washington DC ? Washington DC is National Capital. It has good number of monuments , museums , churches government offices.  A large Number of conventions and tradeshows are organized in DC every year. DC welcomed a record 22.0 million total visitors in 2016. This dataset does not consider seasonality and specific event pricing)

ETL – Python , MongoDB ,Jupyter Notebook
Pre-processing Data for machine learning – Python
Running ML Models – Python
Visualization of Data – Tableau

The K-nearest neighbors (knn) algorithm compares our listing to similar listings and takes the average price. 
Similarity metric that's used in this case is Euclidean distance
d=√(q1−p1)2+(q2−p2)2+⋯+(qn−pn)2d=(q1−p1)2+(q2−p2)2+⋯+(qn−pn)2
where q1q1 to qnqn represent the feature values for one observation and p1p1 to pnpn represent the feature values for the other observation.