# Bearing Fault Diagnosis via Deep Transfer Learning
This project attempts to identify nine different faults and the healthy condition based on vibrational dataset of bearings. For this purpose, the original time series signals are transformed into 2D wavelet maps. Due to few number of wavelet maps, a pretrained convolutional network (VGG16) is transfered to the deep neural network model. By freezing the initial layers and fine-tuning the last layers of VGG16 and fully-connected network, an accuracy higher than 94% is obtained for this 10-class project.

# Bearing Dataset
The open-access dataset can be obtained at https://engineering.case.edu/bearingdatacenter.
It includes vibrational time series of the bearing at four loading conditions, involving 9 different faults and one healthy condition. 
