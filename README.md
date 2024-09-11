# Assessing the Viability and Accuracy of Machine Learning Models At Predicting Renewable Energy Array Parameters

[![Release Senior Thesis](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)

## Overview

This thesis accompanies the project found [here](https://github.com/AidanNeeson/renewable-ml/) which investigates the ability of machine learning models at predicting renewable energy parameters. This work was completed during my time at Allegheny College as a part of my degree in Computer Science. The thesis covers the process from start to finish encapsulating the entire project. The goal of the project was to see if machine learning models could be valuable when used in an area where they are not as popular as one may expect. The results seem to suggest that they, in fact, are.

## Abstract

The world we all live in is a valuable thing, but we are not treating it with the respect it deserves. As industry expands and citizens become careless, global temperatures increase and sea levels rise. A dangerous future is ahead of us if we do not make a change. The most prominent and fastest growing solution to these problems we face is renewable energy, but barriers in society prevent the ease of development that would be desired to see. The ability to gain insights into the potential for renewables would serve as an effective way to promote the installation of low-carbon technologies. Many tools exist in the world that attempt to fulfill this role, but they suffer due to being too narrowly scoped and complex. The need for quick and accurate predictions is dire. Machine learning has seated itself as a powerful tool in the computer science field for making predictions, but also in the energy sector for the purposes of forecasting. For these reasons, this project is seen as the perfect opportunity to apply its expertise. Using locational data like latitude and longitude, as well as a scaling quantity like capacity, three machine learning models are trained and their performance is evaluated. Using industry standard practices and metrics like k-fold cross-validation, R-squared, Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE), the random forest was shown to be an accurate and effective predictor of renewable energy generation and cost for wind farms. This was evident through an R-squared of 0.911 and relative errors ranging from 12% to 16%. Other models and data were proven to be insufficient due to these same metrics. Regardless, this investigation shows machine learning holds immense promise in the field and future of energy.

### Note on Failing Build

Since the completion of the project some dependencies have updated causing the PDF conversion process to fail. The links within the most recent PDF release are outdated, the new ones are as follows:

- [Website](https://renewableml.netlify.app/)
- [Project Repository](https://github.com/AidanNeeson/renewable-ml)