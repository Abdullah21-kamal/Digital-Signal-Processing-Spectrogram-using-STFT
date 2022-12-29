# Digital-Signal-Processing-Spectrogram-using-STFT
## Intorduction:
The aim of this project is to build up an analytical system based on the spectrogram using
Short-Time Fourier Transform (STFT) to assist neurologists in monitoring and diagnosing
epileptic electroencephalography (EEG) signals. Epilepsy is a disorder in the electrical activity
of the brain that causes repetitive and unprovoked seizures. In general, the epileptic EEG signal
is characterized by two main states: interictal and ictal. The interictal state is considered the
period between seizures while the ictal state is the period of a seizure which is characterized by
its large spikes. Other states (i.e., preictal and postictal) are out of our scope in this project.
CHB-MIT [1] is the source of the EEG records that will be used for this project and found in this
link:
https://drive.google.com/drive/folders/129n48qq7R7Y-QE68dciBESN9YCW8PCf1?usp=sharing
## Project tasks:
* Pre-processing
* Spectrogram
* Plotting
* Manipulating the data and feeding it to a ML or DL model to be trained without
coding errors.
* Manipulating the data, training model(s), tuning for different hyperparameters,
tuning for different spectrogram parameters (f & t resolution, window size,
window type) and documenting the different runs. 

* Manipulating the data, training model(s), tuning for different hyperparameters,
tuning for different spectrogram parameters (f & t resolution, window size,
window type) and documenting the different runs and reporting high metrics
(e.g., accuracy).


# ML, DL Models' accurecies:
*   SVM	0.874016	
* 	SVM Kfold	0.841327
* 	KNN	0.937008	
* 	KNN Kfold	0.895772
* 	Logistic Regression	0.929134	
* 	Logistic Regression Kfold	0.903302	
* 	LSTM	0.944882
* 	LSTM Kfold	0.970309
