# Recognising-music-genres-with-the-Wolfram-Language
Using deep neural networks to identify the music genres of 30 second extracts.

This project was put together during the Wolfram Summer School in August 2018 at Wolfram Research in Oxfordshire. I worked in a pair with Emeline Aubel on building neural networks capable of classifying music by genre. Our worked was quickly channeled towards convolutional neural networks which proved particularly accurate when trained on Mel Frequency Cepstral Coefficients (MFCC). Our project was selected out of many to be presented at the Wolfram Conference in June 2019 at the École Centrale-Supélec in Paris, unfortunately I could not make it due to exams.

Several notebooks with different network architectures have been added to the repository. Particularly accurate trained networks have also been added with their parameters saved through the wlnet format, the accuracy of the network is in the name of the file. The maximum accuracy achieved by a network on the testing data was 97.5% achieved by a three-layer convolutional network with five classification categories.

The dataset used is the GTZAN genre collection from http://marsyas.info/downloads/datasets.html. Only the five main music genres were used (rock, pop, hip-hop, classical, jazz). 
