# Simple CNN for detection of seizure events

This repository consists of multiple Python scripts, which:
1. Navigate the (huge) [Temple University EEG Corpus](https://www.isip.piconepress.com/projects/tuh_eeg/) and detect relevant EEG files
2. Fetch and format the data, translate it from time domain to frequency domain and divide it into small chunks, forming the training data of the CNN
3. Implement a first version of the actual PyTorch Convolutional Neural Network. 

## Oh, by the way...

- This work has been produced in collaboration with [@Lorenzo](https://www.linkedin.com/in/lorenzo-sani/) 👨🏼‍💻

- The code has initially been produced as part as an attempt to the global [Neureka Challenge](https://neureka-challenge.com/). 🧠

- But I'm still on it: This is a work in progress! 🚧
