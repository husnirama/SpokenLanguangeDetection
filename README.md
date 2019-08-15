
# Spoken Languange Identifications

Identify a spoken language using artificial intelligence (LID). The solution uses the convolutional neural network and long short term memory model in order to detect language specific phonemes. It supports 3 languages: English, German and Spanish.

# Dataset

The dataset contains speech samples of English, German and Spanish languages. Samples are equally balanced between languages, genders and speakers.
The core of the train set is based on 420 minutes (2520 samples) of original recordings. After applying several audio transformations (pitch, speed and noise) the train set was extended to 12180 minutes (73080 samples). The test set contains 90 minutes (540 samples) of original recordings. No data augmentation has been applied.
I create dataframe function to simplify the data exploration section.

The dataset is divided into 2 directories:

* train (73080 samples)
* test (540 samples)

The filename of the sample has following syntax:

(language)_(gender)_(recording ID).fragment(index)[.(transformation)(index)].flac

The dataset resource are get from this link : [Spoken Languange Identifications]()

# Prerequisties

I use my laptop with specification as follows :
* core i7 8 core CPUs
* 16gb Memory
* Installed tensorflow & Keras on CPUs

# Demo

All you need to run the script its just download the datasource on your local directory and pull the repository (*include model.h5 & modelLSTM.h5*)

Using python3.6 environtment in jupyter notebook. Don't forget to install several package via pip (*the detail of the packages are listed in scripts*)
