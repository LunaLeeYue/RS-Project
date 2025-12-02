# Real-time Flood Inundation Forecasting with Satellite Observations and In-situ Streamflow Data

**Yue Li**   
**GEOL 2283 Remote Sensing**
**Dec 3, 2025**

---

## Introduction
Accurate and timely flood extent forecasting is crucial for flood management and disaster response. While traditional hydrodynamic modeling is capable of simulating the water flow within a watershed, they face significant challenges in large-scale applications due to its sensitivity to uncertain inputs and high computational complexity. In this project, we present a novel real-time flood forecasting model based on a Convolutional Long Short-Term Memory (ConvLSTM) network. The model effectively integrates multimodal data sources, specifically SNPP/NOAA-20 Visible Infrared Imaging Radiometer Suite (VIIRS) water fraction maps and sparse in-situ streamflow data from the United States Geological Survey (USGS), to capture both the spatial and temporal dependencies of flood dynamics. Its encoder-decoder architecture enhances the model interpretability by clearly separating the input-to-state transformation from the state-to-state generation. Experimental results on the Upper Mississippi Alluvial Plain (UMAP), a large river basin in the U.S., validate the model’s effectiveness in spatio-temporal flood extent mapping and real-time flood forecasting.

## Data
### VIIRS Water Fraction Maps

### USGS Streamflow Data

## Study Area
Upper Mississippi Alluvial Plain (UMAP)
![Study Area](StudyArea.jpg)

## Long-term Flood Pattern Analysis

### Data Processing
![Sample](Sample_Original.mp4)
*Processed Water Fraction Maps*

![LinearInterpolation](Sample_Interoplated.mp4)
*Processed Water Fraction Maps after temporal Interpolation*

### Flood Dynamics
![Flood Frequency](FloodFrequency.jpg)

![Max Frequency](MaxFrequency.jpg)

![Max Inundation Extent](MaxExtent.jpg)

## Real-time Flood Forecasting

### Overall Framework
![Model](model.jpg)

### Convolutional LSTM
![ConvLSTM Structure](ConvLSTM.jpg)

### Case Studies
![Case1_input](Case1_input.png)

![Case1_output1](Case1_output1.png)
![Case1_output2](Case1_output2.png)
![Case1_output3](Case1_output3.png)

![Case1_output](Case1_output.png)

![Case2_input](Case2_input.png)

![Case2_output1](Case2_output1.png)
![Case2_output2](Case2_output2.png)
![Case2_output3](Case2_output3.png)

![Case2_output](Case2_output.png)


## Summary
Spatio-temporal Analysis (2012–2020)
Visualize long-term flood patterns with Inundation Frequency Map and Maximum Inundation Extent Map 
Validate temporal correlation between RS observation with in-situ measurement data.

Real-time Flood Forecasting
Develop a deep learning model for flood forecasting
Limited by cloud cover, leading to under/over-prediction in specific events.






---
*GitHub Pages*
