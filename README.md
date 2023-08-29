Download data from here:  https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz?dl=0

Goal: Given audio files for songs, identify which genre they fall in.

Suggested Guidelines : 
1. You'll have to prepare and maintain your own version of train and validation from the complete data given 
2. The major challenge here is to create features from audio files which can then be passed to your choice of deep learning algorithm 
3. Your solution needs to be uploaded on GitHub repo of your team

Steps :
1. Extracting music and features from the GTZAN genre collection dataset where 10 genres had 100 songs each.
2. Extracting the spectrum for every audio to understand the visual representation of the spectrum of frequencies varying with time.
3. Extracting the following features from Spectogram:-
     1. Root Mean Square Error (RMSE)
     2. Mel-frequency cepstral coefficients (MFCC)
     3. Spectral Centroid
     4. Spectral Bandwidth
     5. Zero Crossing Rate
     6. Chrome Frequencies
     7. Spectral Roll-off
4. Writing the data into CSV format.
5. Analyzing the data in pandas with their respective features with the filename.
6. Encoding the labels and then apply StandardScalar to the feature columns.
7. Splitting the data as train and test data.
8. Executing classification using Keras and building a neural network.
9. Checking the tentative performance using validation data from the training dataset.
10. Doing prediction on test data and achieving an accuracy score of 0.63.
