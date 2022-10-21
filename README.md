# Removing Noise from Two Dimensional Signals with the help of LSTM

**Removing Noise from Two Dimensional Signals with the help of LSTM**

In this project, we deal with noise reduction of different signals with recurrent networks.

## **Dataset**

* With the help of commands in python, we generate circular signals, Epitrochoid, and Nephroid. The following defaults are considered for these signals.

* We consider ten periods for each signal. That is (10x2π)

**Why 10x2π? Why go around the circle ten times?**
Because out of 10 periods, we keep 7 of them for train data (7x2π), assign one period to validation data (1x2π), and give 2 to test data. (2 x 2π)

* Then, to each dimension of these three signals (x,y), we add noise with a variance of one and a mean of zero.
 
* We consider ten periods for each signal.

* We consider the periodicity of each signal as 200 seconds. That is, the total time is 2000 seconds.

* We consider the sampling frequency 1000, so we have 2000,000 samples for each signal.

* The figure below shows these three signals.

 ![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Two-Dimensional-Signals-with-the-help-of-LSTM/blob/main/Images/Original.and.noisy.Signals.png)


* Then, out of these ten periods, we keep 7 for train data (i.e., 1400 seconds), assign one period to validation data (i.e., 200 seconds), and give 2 for test data.

* We generate Gaussian noise with a variance of one and a mean of zero and add it to the signals.
Signals and noise signals are shown in the below figure.

## **Network**

We designed the LSTM Network with the below features. 

 ![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Two-Dimensional-Signals-with-the-help-of-LSTM/blob/main/Images/LSTM.png)


 ![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Two-Dimensional-Signals-with-the-help-of-LSTM/blob/main/Images/Results.png)


 ![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Two-Dimensional-Signals-with-the-help-of-LSTM/blob/main/Images/Output.png)

