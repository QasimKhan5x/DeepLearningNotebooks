In this project, I have used the [GTZAN](http://marsyas.info/downloads/datasets.html) dataset, which contains audio files and image representations of these audio files, to perform music genre classification.
The dataset can be downloaded by clicking [here](http://opihi.cs.uvic.ca/sound/genres.tar.gz). Afterwards, this notebook can be run in a Kaggle kernel once the data has been downloaded.

I trained logistic regression and feed-forward neural network models to classify music through audio files.
Afterwards, I used a custom CNN and a pre-trained DenseNet to classify music through MFCC plots (max accuracy was 70%).