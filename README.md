# Movie-rating-Predection
# Movie Rating Prediction using Hybrid CNN-LSTM Model

## Overview
This project aims to predict movie ratings based on user reviews using a hybrid model combining Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs). The model is trained in a supervised learning mode, utilizing a labeled dataset of movie reviews and corresponding ratings.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook (optional, for running the provided notebooks)
- google colab (preferable)


# Model Architecture
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 embedding (Embedding)       (None, 50, 100)           10785300  
                                                                 
 conv1d (Conv1D)             (None, 46, 128)           64128     
                                                                 
 max_pooling1d (MaxPooling1  (None, 11, 128)           0         
 D)                                                              
                                                                 
 conv1d_1 (Conv1D)           (None, 7, 64)             41024     
                                                                 
 max_pooling1d_1 (MaxPoolin  (None, 1, 64)             0         
 g1D)                                                            
                                                                 
 lstm (LSTM)                 (None, 64)                33024     
                                                                 
 dense (Dense)               (None, 1)                 65        
                                                                 
=================================================================

# Acknowledgement
I sincerely extend my Thanks to Nikhitha (https://github.com/KanchetiSaiNikhitha)   
