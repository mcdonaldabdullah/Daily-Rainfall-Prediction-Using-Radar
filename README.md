# Daily-Rainfall-Prediction-Using-Radar
Reliable daily rainfall predictions can play an important role in a) watershed management, b) disaster management, and c) helping people to plan their day. Numerous factors can have an effect on the patterns of rainfall and therefore it can be difficult to predict. Recent papers studied deep learning for rainfall prediction using various prediction models with an emphasis on short-term predictions (hourly), however, few have looked at daily rainfall prediction using deep learning. This paper discusses a deep learning model, ConvLSTM, for daily rainfall prediction using various sequence lengths of radar images and predicting 1, 2, 4, 7, and 12 days ahead. The aim of this paper is to investigate how well the ConvLSTM model fairs against a Multivariate Regressor and also to look at whether increasing the length of the sequences of images a model can learn from decreases the prediction error of the model. To establish the effectiveness of the ConvLSTM model, we compare it against the Multivariate Regressor and a Last Frame Regressor model. The results of our work show that the ConvLSTM model outperformed the Multivariate Regressor and Last Frame Regressor models when predicting 1 day ahead, however, when predicting 2, 4, 7, and 12 days ahead, the results of the ConvLSTM and Multivariate Regressor models are quite similar. When comparing sequence lengths, our results show that an increase in sequence length does not necessarily decrease the prediction error of a model.
