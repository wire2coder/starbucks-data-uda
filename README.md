## Table of Contents
- [Summary](#summary)
- [Description](#description)
- [Description of Metrics](#Description-of-Metrics)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Installing](#installing)
- [Executing Program](#executing-program)
- [Screenshots](#screenshots)

## Summary
Build a machine learning 'pipeline' that can classify emergency text messages in various categories.

## Description
The objective is to construct a Natural Language Processing (NLP) model capable of categorizing messages from real-life disaster events. The 

## Justification for Selecting 'F1-Score' as the Metric

The 'class' refers to the possible 'outcomes' or 'labels' in a 'classification' problem
in this project, we have 2 'classes':
- 0, indicating that the offer (promotion) is 'NOT effective'
- 1, indicating that the offer (promotion) is 'effective'
here1


1. **Precision**: If your model predicts a message as 'related', precision tells you how likely it is that the message is indeed 'related'. High precision is good.

2. **Recall**: Out of all the 'related' messages, recall tells you how many of them your model was able to find. High recall is good.

3. **F1-Score**: This is a combination of precision and recall into a single number. It tries to give you a single score to evaluate your model instead of having to look at two different ones (precision and recall). Again, a high F1 score is good.

4. **Support**: This tells you how many examples of each class you had in the data you used to evaluate the model.


## Getting Started
1. run Piplines/ETL Pipeline Preparation.ipynb and will make ETL_Preparation.db file


## Dependencies

requirements.txt

- pandas
- matplotlib
- seaborn
- numpy
- scipy
- scikit-learn
- tensorflow
- keras

## Installing

- Create a new 'virtual environment' (conda or venv) 
- Activate the new environment
- and install the dependencies.

```
python -m venv myenv

# for windows
myenv\Scripts\activate.bat

# for linux and macOS
source myenv/bin/activate

pip install -r requirements.txt
```

## Executing Program






## Screenshots
![alt text](screenshots/etl_database.png)






