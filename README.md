# landuse-classifier
Land use classification from satellite images with sci-kit learn. Made as a part of CENG463 in AYBU.\
\
\
\
- Navigate using the headers. For example in google colab you can jump to a line by clicking on the header in `contents` tab\
\
# How to prepare a classifier and send submission
\
1. Import the libraries and mount google drive for permanent storage\
2. Enter the `Prepare Data` section and run the cells one by one.\
3. Split the data for the kind of classification you want (either water -> rest or water -> building -> rest)\
4. Create and fit a classifier of each kind (Water only, Building only without water, without Water, without water and Building)\
5. Import the test data and pre-process it using the code at the beginning of the `Prediction` section\
6. Use the classifiers on the pre-processed data depending on the classifier you have created (either water -> rest or water -> building -> rest)\
7. Install and configure kaggle command line tool.\
8. Submit the result using the kaggle command line tool.\
