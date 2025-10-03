# Muscle-EMG-SVM

This is the loacation for my personal work on the i-MADE Stealth Project. Here, a simle Dense model is in the work to classify muscle fatigue based upon sEMG data. 
Please contact me if you need access to the data 


# How to get the parsed data

After getting the study data from https://zenodo.org/records/14182446, unzip the files into the github file

Then, run the ipynb found within the unzipped files (should be labeled code.ipynb) .

After changing the correct paths (should be lablled in the code.ipynb file that came with this repo, otherwise just message me), run the code, it will take around 5 minutes
This should create two new folders with the right data, self_perceived_fatigue_index and frequency_analysis

After that go to muscle_data_processing.ipynb. This file is used to merge the two new created folders. It takes the self perceived index and properly associates it with the frequency/time. 

Good luck and slack Chris with any questions!
