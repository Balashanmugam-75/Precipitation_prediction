**Precipitation Prediction Project**

**Overview**

This project focuses on predicting precipitation in Thanjavur district using three different recurrent neural network (RNN) architectures: Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and vanilla RNN. The goal is to analyze and compare the performance of these models in real-time precipitation prediction based on historical data spanning from 1980 to 2022.

**Models Used**

**LSTM (Long Short-Term Memory)**:

Description: LSTM is a type of RNN that is well-suited for learning and remembering over long sequences.


**GRU (Gated Recurrent Unit)**:

Description: GRU is another variant of RNN that simplifies the architecture compared to LSTM, aiming to achieve similar performance with fewer parameters.


**RNN (Recurrent Neural Network)**:

Description: The standard RNN architecture was also implemented for comparison with more advanced models like LSTM and GRU.


**Harris Hawk Optimization (HHO)**

**Overview**
Harris Hawk Optimization is an evolutionary algorithm that is particularly well-suited for optimizing complex, high-dimensional problems. It is inspired by the collaborative hunting strategy of Harris's Hawks in nature.

**Integration with Precipitation Prediction Models**
To enhance the performance of the LSTM, GRU, and RNN models, hyperparameter tuning is crucial. HHO is employed to efficiently search the hyperparameter space and find optimal configurations for the models.

**Data**

The real-time data used for this project covers precipitation records in Thanjavur district from 1980 to 2022. The dataset is preprocessed and split into training, validation, and test sets to train and evaluate the models.

**Performance Metrics**
To assess the performance of the models, the following metrics were used:

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

R2 Score

Mean Square Error(MSE)

Mean Bias Deviation (MBD)
