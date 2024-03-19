# RunnersTimeSeries
Classifying Time Series using Rocket Transformer and sktime and comparing results with traditional approaches
The objective of this assignment is to identify good models for classifying time series data.
The data is from an accelerometer sensor and there are samples of fatigued and non-fatigued running. The data has been segmented into strides and the segments (samples) are labelled F (fatigued) and NF (not fatigued). The data for two subjects A and B are available in the files fatigueA.csv and fatigueB.csv. This dataset is extracted from a much larger dataset described here.
At present, the best performing method for time-series classification is Rocket. A rocket implementation is available in the sktime tool kit. This sktime implementation can be used in this assignment.
Some code to get you started in available in the notebook RunningCore.
