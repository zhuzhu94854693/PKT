# PKT
The general idea of the PKT method is shown in Figure. Firstly, the normalized difference vegetation index (NDVI), normalized difference phenology index (NDPI) and normalized difference greenness index (NDGI) are calculated for each month of the year in the Sentinel-2 data to construct the relevant spectral indices time series. Secondly, based on the sample points of each wetland category, the mean values of 108 features over 12 months for Sentinel-1 and Sentinel-2, i.e., B2, B3, B4, B8, VV, VH, NDVI, NDPI and NPGI, are used to construct the phenological knowledge transfer model for each wetland category. Then, the DTW method is employed to match the phenological knowledge transfer models of each wetland category with each pixel to obtain the probability of each wetland category for each pixel. Finally, the difference between the probability of each wetland category for each pixel in the two time phases are calculated at the value and shape levels, and the change training sample containing change areas and change types are obtained.

![image](https://github.com/zhuzhu94854693/PKT/blob/main/image.jpg)

https://code.earthengine.google.com/d7e3f4fe5e3d3ea67fde42d041c2d720
