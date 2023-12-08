# Bird-Sound-Detection-Project
Overview:
This project focuses on the detection of bird sounds, targeting 7 specific bird species. The goal is to develop a model capable of identifying these species in raw unlabelled audio data.

Data Sources
The labeled training data for this project was meticulously collected from two primary sources:

Xeno-canto: A community-driven website that shares bird sound recordings from around the world.
eBird: A comprehensive database of bird observations providing valuable information about bird species.
Special access to testing data was granted by Cornell University, enhancing the robustness and diversity of dataset.

Target Species
This project specifically focuses on the following 7 bird species:

Germain's Peacock Phesant
Giant ibis
Great hornbill
Orange necked partridge
Oriental pied hornbill
White shouldered ibis
White rumped shama

Training Data: 

The collected data underwent  preprocessing and labeling process:

Manual Labeling: Each audio sample was carefully labeled to ensure accuracy.
Preprocessing Steps:
Conversion to single-channel audio.
Standardization of the sample rate to 44,000 Hz.
Format conversion to .wav for consistency and quality preservation.

Training data is organised in 4 separate folders 
Audio data:
Bird calls Audio
Bird Songs Audio
Image data:
Image data calls
Image data songs

Testing Data:

Dataset is organized into 4 separate folders, each containing a subset of the 38,141 samples. Each sample is a 4-second audio clip, preprocessed to enhance signal quality and remove background noise.

Folder Organization
Folder 1,2,3,4

Model Training and Prediction
The training model utilizes the labeled data to learn the acoustic characteristics of each target species.
The ultimate objective is to apply this model to the raw unlabelled data to accurately predict and identify the presence of these 7 species.

Access to Data:
The data for this project is hosted on OneDrive due to its large size (9.96 GB)
Access to the data can be requested through the following link:
Link: https://1drv.ms/f/s!Ajfnt81R_rn_hepO1yusBNviZFCtFw?e=VgUfHE
