# Turbofan-RUL
**Objective**  
The objective of this project is to develop a machine learning model to predict the remaining useful life of aircraft turbofan engines. The Remaining Useful Life (RUL) is the amount of cycles an engine has left before it needs maintenance.

**Dataset**  
The dataset has 249 engines (engine_no) which are monitored over time (time_in_cycles). Each engine had operational_settings and sensor_measurements recorded for each cycle. This dataset is further divided into training and testing subset.  Each engine starts from a different degrees of initial wear and manufacturing variation which is unknown. The data is also contaminated with sensor noise.    

The engine is operating normally at the start of each time series, and develops fault at some point during the series. In the training set, the fault grows in magnitude until the system failure. In the test set, the time series ends sometime prior to system failure.The objective is to forecast the number of remaining operational cycles before the failure in the test set, that is, the number of operational cycles after the last cycle that the unit will continue to operate.

