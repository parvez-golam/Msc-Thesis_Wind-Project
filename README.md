# Msc-Thesis_Wind-Project
Impact of Covid-19 in Wind Power Prediction in Ireland

The ongoing COVID-19 pandemic has instigated worldwide social-economic turmoil, forcing governments to introduce extreme measures to reduce its spread. In addition, 
it has caused significant challenges to the energy industry. This project details the impacts and challenges of the COVID-19 pandemic on energy demand and wind-generated 
energy in Ireland. It provides a deep learning model through an experimental study comparing the performance of the most popular architectures. This study
investigated the accuracy of RNN and LSTM time series modelling approaches using publicly available datasets from the EIR Grid. As a result, long short-term memory (LSTM) obtained the most accurate forecasts for wind-generated energy. However, the prediction of energy demand during the pandemic is inaccurate, 
indicating a post-pandemic change in energy demand.


"Data_check.ipynb" has the data analysys part, it shows the yearly, monthly, weekly energy demand and wind generated energy data and the statisical comparisons between pre and post pandemic time.

"parameters.json" contains all the hyperparameters to run the experiment for model selection.

"model_run_main.py" runs the main experiments with all the hyperparameters and the data is saved in "results.csv" file.

"Hyperparameter_evaluation.ipynb" this file evaluates the results for different hyperparameters from "results.csv" file and finds the suitable parameters.

"MODELS_DEMAND.ipynb" and "MODELS_WIND.ipynb" notebooks contains the final selected models for energy demand and wind generated energy and the prediction results generated from the models.

'fig_out' folder has all the generated ouput visual figures throughout the project.




