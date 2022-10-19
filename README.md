# Generic Real Estate Consulting Project

**Intro:**



**Team members:**

- Name: Qihan JIANG
- Student ID: 1174068

- Name: Shuyu CHEN
- Student ID: 1174258

- Name: Yuehan ZHAO
- Student ID: 1174279

- Name: Yuyan ZHANG
- Student ID: 955009

- Name: Zesong ZHANG
- Student ID: 1118527


**Research Goal:** 
1. The most important internal and external features in predicting rental prices
2. The top 10 suburbs with the highest predicted growth rate
3. The most liveable and affordable suburbs 

**Data:** Due to the data is large, please visit this link: , download data.zip and replace the original blank data folder.


To run the pipeline, please visit the `notebooks` directory and run the files in order:

1. `data.ipynb`: This notebook is used to scrape data from Domian, please note, as the process takes a lot of time, the completed json file already exists in data.zip, so you could skip this notebook. 

2. `preprocess.ipynb`: This notebook is used to preprocess the data and generate some csv that will be useful for later research.

3. `Distance.ipynb`: This notebook is used to generate some geographic external data, such as the distance from one single property to the nearest school or train station.

stage one: most important internal and external features, please visit the `stage1` folder.

4. `LR.ipynb`: This notebook is used to generate linear regression model for stage 1.

5. `DT.ipynb`: This notebook is used to random forest model for stage 1.

stage two: top 10 suburbs with the highest predicted growth rate, please visit the `stage2` folder.

6. `ranking.ipynb`: This notebook is used to predictions were made for important features based on the results of Stage 1 and each suburb was scored and ranked according to the feature prediction data.

7. `failed_prediction.ipynb`: This noteboooks is for linear regression model to predict top 10 suburb directlly. However, the model were not used in the final presentation due to data limitations and lack of accuracy. you could skip this notebook. 


stage two: top 10 suburbs with the highest predicted growth rate.

8. `geo_pro.ipynb`: This notebook is used to preprocesse the data for geospatial visualisation




