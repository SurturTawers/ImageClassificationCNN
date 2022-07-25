# ImageClassificationCNN
Implementation of an image Classification CNN (Convolutional Neural Network) in Tensorflow Keras on Google Colab.\
## Data
Data consists of four sets of images:
* Science 
* Template (subtracted to science)
* Difference (result of science minus template)
* SNR(Signal to Noise Ratio, pixel noise estimation of difference).
\
\
Each set has 5026 21x21 real/artifact images of HiTS (High Cadence Transient Survey), divided in 4026 images for training and 1000 images for testing.
