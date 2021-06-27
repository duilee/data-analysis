## Arctic Sea Ice Concentration Prediction

Summary of ML project on Arctic Sea Ice Concentration using Satellite Images  
_**Detailed project summary can be found at [here](https://github.com/duilee/data_projects/blob/master/_00_ice_concentration_AI/Project_summary_eng.pdf)**_  
_**Medium post can be found [here](https://medium.com/@duilee/how-climate-change-is-affecting-arctic-sea-ice-concentration-with-ml-db725bea33e5)**_

## Motivation

As a result of global warming, various climate change signs had been detected including Earth’s surface temperature change, 
irregular temperature, and rising sea levels. The ice concentration at the North Pole has also been decreasing.  
  
**\[GOAL] :** Use the satellite images of the past North Pole’s ice concentrations, and predict the ice concentration in the future

## DATASET

5 images(448 x 304) are provided for each month from Nov. 1978 to Dec. 2018.  
Each data contains ice concentration(0~250), blind spot, shoreline, land border, and null value locations  

Dataset can be found [here](https://dacon.io/en/competitions/official/235731/overview/description)

## Language and Libraries Used

Primary Language used was Python(3.7)  

With libraries including TensorFlow/Keras (Autoencoder, LSTM/ConvLSTM, Multi-Head Attention), numpy, and pandas  

## Quick Project Results

