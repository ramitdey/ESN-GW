# ESN-GW

In this project, we use a deep-learning model to detect gravitational wave (GW) signals from a given time-series data. For this purpose, we implement an Echo Memory Network (EMN) to detect GW signal embedded in noise. The dataset used for training consists of waveforms of slow-evolving Extreme mass ratio inspiral (EMRI) and Gaussian noise generated using the power spectral density of the space-based LISA GW detectors. 
While designing a Deep learning-based model that can detect faint GW signals buried underneath the noise, several architectures (such as convolutional neural network (CNN), recurrent neural network (RNN), etc) have been implemented and shown to produce results that surpass the conventional methods of matched filtering and cross-correlation based approaches. In most of the previous works the deep learning models were customized to deal with short-lived transient GW signal originating from the coalescence of compact binary objects. In light of the upcoming space-based detector (e.g. LISA) we will be able to detect continuous gravitational wave signals as well as slowly evolving EMRI waveforms. A typical CNN or RNN-based time series classifier would not be optimal for dealing with these slow-evolving time series signals and hence in this work, we introduce the use of ESN for the task of classifying slow time-evolving GW signals. 
We found for these types of GW waveforms the network performs exceptionally well compared to other Recurrent neural network architectures.  
