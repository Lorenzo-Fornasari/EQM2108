### Final work for the EQM2108 course
# BTP and BTT modeling using Random Forest Regressor
Professor: Amanda Lemette

Student: Lorenzo Fornasari

# Abstract

  This work explores the modeling of the Burn Through Point (BTP) and Burn Through Temperature (BTT) of a sintering machine from a Brazilian steel mill. 
Predicting these parameters can be very helpful in identifying deviations in sinter quality, preventing material recirculation and optimizing the process.
The regression methods of XGBoost and Random Forest were experimented, and XGBoost wasn't capable of correctly modeling the data.
A optimization of hyperparameters was realized and the best results were selected to be used in our model.
Linha falando sobre os resultados.
This study aims to lay the groundwork for future works of BTP and BTT prediction

# Introduction

  Sintering of iron ore is a essential part of a modern integrated steel mill. Unfortunately, it is also a source of a considerable ammount of green house gases, particulates, and other harmfull gases such as NOx and SOx.
Thus, being able to predict parameters of the process that influence its efficiency is an action that not only results in savings for the steel industry, but also lowers its environmental footprint.
However, there is currently no instrument to detect sintering end point at present, due to its large lag and time-varying characteristics.
Thus, the only methods to determine this parameterers estimate the BTP based on other process parameters.
Some efforts to improve sintering through machine learning have alredy achieved considerable accuracy, given the inherent complexity of this process.
One of them used gradient boosting decision trees and an inference engine to predict BTP and BTT.
  Given the expected gains and previous sucesses from modeling, this work aims to build a machine learning framework which may be used to predict sintering end point for this steel mill in the future.
Here, XGBoost and Random Forest algorithms were tested and Random Forest yielded satisfatory results. 

# Methodology
The average process data for each minute was obtained from the company's database for the following parameters: exhaust temperatures of various bellows, negative pressure of main pipe, sintering machine speed, mixing roller speed and gas flux at the main exhaust.
Afterwards, the BTP was calculated for each minute using an empirical equation.

# Results and discussion

# Conclusion

# References
