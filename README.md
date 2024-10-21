# Assessing the Financial Impact of Tornadoes in Minnesota Using Time Series Data

## Contents
1. DATA folder: Contains 1950-2023_all_tornadoes.csv, our original dataset which was produced by the National Oceanic and Atmospheric Administration (NOAA) and posted on their Storm Prediction Center website.
2. SCRIPTS folder: Includes DS_PROJECT_2.ipynb, which holds all the source code for data loading, cleaning, and ARIMA analysis and forecasting.
3. OUTPUT folder: Contains plots generated during the initial exploratory data analysis (EDA) of the dataset as well as during evaluation of model statistics and diagnostics.

## Software and platform
For the project, we used Python and the additional pandas, numpy, matplotlib, statsmodels, and scikit-learn libraries. Each of our group members used Mac platforms.

## Map of Documentation
In the DATA folder, there is 1950-2023_all_tornadoes.csv, which is the original CSV file of our dataset. In the SCRIPTS folder, there is DS_PROJECT_2.ipynb, which includes all of our source code for loading and cleaning the data, as well as ARIMA analysis and forecasting. In the OUTPUT folder, there are plots that were produced from initial EDA of our dataset as well as from evaluation of our ARIMA model.


## Instructions for reproducing results
To reproduce the results of this study, follow the steps outlined below:

1. Navigate to Google Colab and sign in with your Google account.
2. In the Colab interface, click on File in the top navigation bar, then select Open Notebook.
3. In the popup titled "Open Notebook," find the left-hand navigation bar and click on the GitHub tab.
4. In the search bar, enter the username RainaVardhan. In the Repository field, select RainaVardhan/DS4002-Project-2.
5. Open the file located at SCRIPTS/DS_PROJECT_2.ipynb.
6. After the file opens, go to Runtime in the menu and select Run all to execute all the cells. This will run the entire analysis process, including data preprocessing, model building, and result generation.
7. The notebook contains sections for data exploration, preprocessing, model training, and evaluation. Review the outputs, plots, and performance metrics generated. You can also modify or rerun specific cells to test different models or parameters.
8.  Once the notebook finishes running, save the results (such as plots and metrics) by downloading them locally or saving them to your Google Drive.


## References
1. Noaa.gov, 2024. https://www.spc.noaa.gov/wcm/data/1950-2023_all_tornadoes.csv (accessed Oct. 11, 2024).
2. D. Bhatt, “Time Series Analysis and Forecasting with ARIMA in Python,” The ML Classroom, Nov. 03, 2023. https://medium.com/datainc/time-series-analysis-and-forecasting-with-arima-in-python-aa22694b3aaa 
3. “Storm Prediction Center Severe Weather GIS (SVRGIS) Page,” www.spc.noaa.gov, Jul. 17, 2017. https://www.spc.noaa.gov/gis/svrgis/ 
4. “Severe Database Description,” Apr. 07, 2010. https://www.spc.noaa.gov/wcm/data/SPC_severe_database_description.pdf
5. Zaina Saadeddin, “ARIMA for Time Series Forecasting: A Complete Guide,” Datacamp.com, Sep. 09, 2024. https://www.datacamp.com/tutorial/arima
