# Recommender Systems class

Author: Michał Maciaszek

## Requirements

Python 3.7.9 or higher

Install all necessary packages provided in requirements.txt

If using pip:
```
pip install -r requirements.txt
```

If using conda:
```
conda install --file requirements.txt
```

## Overview
The goals of the project are:
- prepare dataset of hotel recommendations for content based recommender,
- select best features for the model,
- find the best model for recommending hotels for users,
- compare the results against Amazon recommender.

Used data is stored in data/hotel_data directory.

Data is prepared in project_1_data_preparation.ipynb notebook.

Feature engineering, fitting the models and comparision are done in project_1_recommender_and_evaluation.ipynb notebook.

The best result so far: SVRCBUIRecommender: HR@10 = 0.049029	
