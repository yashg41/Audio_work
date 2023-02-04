# Audio_work
Machine learning model for audio classification , converting audio data to MFCC and then creating a sequential model and training for classification of audio.

There are two files for this project:

In the first file I have done an explorative data analysis to understant the data set and properties of samples.

I then converted the audio data which is wav form to MFC coefficients

Then I exported these coefficient to another file (on google colab to get faster computation)

In second notebook, I first streamlined the imported coefficients and then divide them into output and input features

Then I splitted the dataset into test and validation and train set and created three different models

I trained all the models for 400 epochs and was able to achieve approx 80% accuracy on validation set.

At last i tried the best model out of three on a new example and was able to get correct classification :)
