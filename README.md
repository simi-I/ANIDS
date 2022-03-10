# ANIDS

Intrusion detection system (IDS) is critical in identifying abnormalities and assaults on  networks. 
To implement a realistic IDS, an up-to-date security dataset, CSE-CIC-IDS2018 is used. 

The Chosen dataset is highly imbalanced. The imbalance ratio is reduced by using a synthetic data generation model called Synthetic Minority Oversampling Technique (SMOTE). 

Transducive transfer learning strategy is leveraged in building the IDS, a pretrained ResNEt50 model was used.

To train the model with the numerical dataset,  78 features from the dataset was transformed into grayscale images with 13 x 6 shape. The images are then resized into a 32 x 32 images and the final input dimension of 32 x 32 x 3 is generated for the model.
