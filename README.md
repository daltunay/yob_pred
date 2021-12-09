# yob_prediction
Year of birth and gender prediction based on first name, zip code and email domain

The initial database is composed of 2M rows and 5 features :
- year of birth
- first name
- zipcode
- gender
- email domain

800,000 of these 2M users had a NaN value for the year of birth (yob). 

I began to do a data exploration analysis. Then, using a KMeans clustering algorithm and two regression models (Random Forest and Neural Network), I was able to achieve a 99.56% accuracy rate on test data.
