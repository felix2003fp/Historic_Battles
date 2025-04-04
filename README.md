# History Battles

## Description
Predicting the outcome of a battle has always been a challenge, even for the most experienced commanders in history. This project leverages the power of machine learning to analyze historical battles and provide insights into their outcomes based on features like troop strength, leadership, and battlefield conditions.

Using data from historical records, advanced models like Logistic Regression, Random Forest, SVM, XGBoost, and LightGBM have been trained to determine the victor of battles. This project explores how data-driven approaches can complement strategic decision-making by predicting potential outcomes before the first shots are off.

This repository includes everything you need to understand, train, and utilize the models, from feature engineering and hyperparameter optimization to the final evaluation metrics.


## Data Source
The dataset used is called Historical Military Battles, found on Kaggle, in this [link](https://www.kaggle.com/datasets/residentmario/database-of-battles?), by Jeffrey Arnold. At the same time, this Kaggle is a cleaned-up version of the "CAA Database of Battles, Version 1990" distributed by the U.S. Army Concepts Analysis Agency. Although some modifications have been done to the dataset, all of them are found in the python files in this repository, and the dataset is the baseline for any of the work in here.

The dataset shows 660 battles from 1600 onwards, including commander names, troop strength, initiative advantage and weather among many others. The content is split in several files, found in *original_data*, where I have included a file with a short explanation of every variable in each CSV file, *Explicacions_Variables.txt*, whether these variables were later included in the predictions or not.


## Resources
In this Github repository you can find. 
-  **original_data**: all the original files of the Kaggle dataset
- **History_Battles_Dataset_Creation.ipynb**: The jupyter notebook with all the code to unify all the different CSV files into one, the History_Battles CSV
- **History_Battles.csv**: The CSV file, a combination of all the data in *data*
- **History_Battles.ipynb**: The main jupyter notebook of the project, all predictions are made here
- **History_Battles.pdf**: A 5-page overview of the project, explaining all the process involved
- **Variables_Explanation**: Explanation of all the variables used in *History_Battles.ipynb*, after cleaning unnecessary ones in *History_Battles_Dataset_Creation.ipynb* and in the first lines of *History_Battles.ipynb*
- **Battle_Scrapper.ipynb**: Scrapper in order to extend the original dataset, not used in *History_Battles.ipynb*, due to the need to produce data as complex (and interpretative) as that already in the CSV files. The whole process is also explained in *History_Battles.pdf*
- **added_Battles.csv**: The result of *Battle_Scrapper.ipynb*, also not used in *History_Battles.ipynb*
