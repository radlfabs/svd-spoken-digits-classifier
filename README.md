# SVD based Classifier for SpeechRecognition on AudioMNIST
This repo hosts our implementation of the classical SVD-based MNIST digit classifier but applied to AudioMNIST. This project has been conducted during the final project in the course Applied Mathematics at University of Applied Science Cologne. 

# Getting Started

For testing purposes we provide a small subset of AudioMNIST. It has been randomly created with `dev_dataset.py` and 
represents a minimal working example with 30 audio files in each digit class(300 total). 
It is important to point out that the classification error on this data set is not representative. 
Nonetheless, it is a useful way to test the main program without downloading the full data set. 
In addition, the main program will only classify 5 test samples by default to limit computation time. 
So testing will most likely stop before converging to the lowest possible error rate. 
This program was created with Python 3.10.4.

1. Clone this repo.
2. Create a new python venv and activate it.
3. If you would like to perform a complete classification run, clone/download the data from [here](https://github.com/soerenab/AudioMNIST/tree/3c9ed8cfcdee9de04c1f61658dbc0883b5b7d781/data).
   Afterwards, copy the 'data' folder to your local ‘number classifier’ directory.
4. Install required packages with `pip install -r requirements.txt`. 
5. Consecutively, you can run the main program (`number classifier.py`) for testing or grading purposes from the 
   command line. `cd` to the unzipped directory and run the command `py -m number_classifier`. 
   Of course, you can run the file in any Python IDE of your liking.
6. Additional plots can be generated by running the following prompt: `py -m util`
   They will be saved as pdf-files to a plots-subdirectory. 
