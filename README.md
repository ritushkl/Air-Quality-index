# Air-Quality-index
Abstract-Air is essential natural resource available which is being compromised by the various human related works and activities. Air pollution alludes to the issue of toxins into the air that are harmful to human well being and the entire planet. It can be described as one of the most dangerous threats that the humanity ever faced. It causes damage to animals, crops, forests etc. To prevent this problem, Several research are being done to predict air quality from pollutants using machine learning techniques. The aim of this project is to implement machine learning based techniques for air quality prediction.


I.	MOTIVATION
The  air  quality  index  (AQI)  is  an  index  used to report air quality on a daily basis. Air quality index is  a  measure  used  to  indicate  level  of  the pollutant like so2, no2, rspm, spm etc. Air quality has been depleted in terms of quality due to various economic activities. The purpose of the AQI is to help people know how the local air quality impacts their health. Higher the AQI value, greater will be the level of air pollution and greater the health concerns. We choose this project to predict the air quality using the machine learning model with the help of previous year data.  By this, We would be able to check the major AQI pollutants and  the  areas  which  are  worst  affected.   People with lung diseases are at higher risks. And in the prevailing  corona  times  when  the  virus  also  affects  the  lungs,  the  poor  air  quality  will  make things worse for the PC, provides authors with most of the formatting specifications needed for preparing 
II.	RELATED WORK
Air pollution leads to raise in    diseases, lower immunity and other respiratory problems. Decision tree algorithm seems to work well in predicting air quality. This could be used in predicting the air quality by the weather department E. Kalapanidas et.al[1].
It is believed that city air pollution has a huge impact on human well being  as in developing nations the air quality measures are not available or are not enforced properly.
Several studies have shown that the bad air quality or air pollution is linked with high Covid-19 death rates.
Covid-19 death rates have a pattern where the population density is high and the exposure to P.M2.5 is also more K.Mahesh et.al [2].Some recent studies are focusing on more advanced statistic based learning algorithms for air quality checking and prediction of air pollution. Raimondo et al.[3],Garcia et al. Used neural network s to build model for prediction. They used SVM and ANN to train models. The ANN gave the best result with 79% specification and 0.82% false positive rate and SVM gave the result with 80% specificity and 0.13% false positive rate.Yu.et al proposed random forest approach for AQI prediction and the best performance prediction was given by stacking assembles. Yun-Chia et.al[6] has done series of experiment on three different dataset which are from various  regions in china . There experiment suggests that Machine learning algorithms in combination with Adaboost results in better prediction performance and provides best results in MAE.

III. RESULTS

Below Table shows the comparison of the results between various Machine Learning algorithms implemented in the model: DT, SVM, RF, multiple linear regression and Logistic Regression.

Algorithms	Accuracy
Linear Regression Model 1	97.79%
Linear Regression Model 2	94.65%
Logistic Regression Model 1	77.75%
Logistic Regression Model 2	68.06%
Random Forest	99.98%
Decision Tree	99.97%
SVM	99.97%

On the basis of all the observations, and Analysis, the best algorithm suited well for this prediction of AQI is Decision Tree Algorithm with the accuracy of 99.98%.
Along with the accuracy, the error is also of prime importance. The algorithm with the less error is supposed to be the best than the ones having greater errors. The Mean Squared Error (MSE) is used to calculate the mean of the squared differences between actual value and predicted value. The Mean Absolute Error (MAE) is the mean of the absolute difference between actual value and predicted value For Linear Regression, MAE for Model 1 is 12.89 & for Model 2 is 20.08.

VI. CONCLUSION

Since our model is capable of predicting the current data with 99.98% accuracy, it will successfully predict the upcoming air quality index of particular data within a given region. With this model we can forecast the AQI.

V. REFERENCES

[1]. E. Kalapanidas and N. Avouris, “Applying machine learning techniques in air quality prediction,” in Proc. ACAI, vol. 99, September 2017.
[2]. K. Mahesh Babu, J. Rene Beulah,” Air Quality Prediction based on Supervised Machine Learning Methods”, International Journal of Innovative Technology and Exploring Engineering (IJITEE) ISSN: 2278-3075, Volume-8, Issue-9S4, July 2019.
[3]. Raimondo, G.; Montuori, A.; Moniaci, W.; Pasero, E.; Almkvist, E. A Machine Learning Tool to Forecast PM10 Level. In Proceedings of the Fifth Conference on
 
Artificial Intelligence Applications to Environmental Science, San Antonio, TX, USA, 14–18 January 2007; pp. 1–9.
[4]. Garcia, J.M.; Teodoro, F.; Cerdeira, R.; Coelho, R.M.; Kumar, P.; Carvalho, M.G. Developing a Methodology to Predict PM10 Concentrations in Urban Areas Using Generalized Linear Models. Environ. Technol. 2016, 37, 2316–2325.
[5]. Yu, R.; Yang, Y.; Yang, L.; Han, G.; Move, O.A. RAQ
“A Random Forest Approach for Predicting Air Quality in Urban Sensing Systems”. Sensors 2016, 16, 86.
[6].Soundari, M., Jeslin, M., & A.C, A. (2019). “Indian air quality prediction and analysis using machine learning”. International Journal Of Applied Engineering  Research,  14(0973-4562),  1-6. Retrieved
22	July	2020,
https://www.ripublication.com/ijaerspl2019/ijae rv14n11spl_34.pdf.
[7]. C R, A., Deshmukh, C., D K, N., Gandhi, P., & astu, V. (2018). “Detection and Prediction of Air Pollution using Machine Learning Models.” International Journal Of Engineering Trends And Technology, 59(4), 204-207.
[8]. Kleine Deters, J., Zalakeviciute, R., Gonzalez, M., & Rybarczyk, Y. (2017). “Modeling PM2.5 Urban Pollution Using Machine Learning and Selected Meteorological Parameters.” Journal Of Electrical And Computer	Engineering,	2017,	1-14.
https://doi.org/10.1155/2017/5106045
[9].Bhalgat, P., Pitale, S., & Bhoite, S. (2019). “Air Quality Prediction using Machine Learning Algorithms.” International Journal Of Computer Applications Technology And Research, 8(9), 367-370.
https://doi.org/10.7753/ijcatr0809.1006



 

