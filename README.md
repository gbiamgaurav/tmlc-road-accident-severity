# Road Accident Severity Prediction

[Find the webapp here](https://road-safety-prediction-app.onrender.com)

## Webapp Screenshorts

![screenshot](https://github.com/gbiamgaurav/tmlc-road-accident-severity/assets/81230208/90bc9814-46ca-411e-9118-4b29409d382e)

![screenshot](https://github.com/gbiamgaurav/tmlc-road-accident-severity/assets/81230208/81d142bb-aafd-4926-a283-b1f159045ef2)


## Dataset Description:

This data set is collected from Addis Ababa Sub-city police departments for master's research work. The data set has been prepared from manual records of road traffic accidents of the year 2017-20. All the sensitive information has been excluded during data encoding and finally it has 32 features and 12316 instances of the accident. Then it is preprocessed and for identification of major causes of the accident by analyzing it using different machine learning classification algorithms. 

## Problem Statement:

The target feature is `Accident_severity`` which is a multi-class variable. The task is to classify this variable based on the other 31 features step-by-step by going through each day's task. Metric for evaluation will be f1-score


## Data Source 

[Click here to check the data source](https://dans.knaw.nl/nl/data-diensten/narcis/)

## Tech Stack Used:
* Python
  
* Streamlit
  
* Render

## How to Setup in local

* Fork the repo `https://github.com/gbiamgaurav/road_accident_severity.git`

* install the dependencies `pip install -r requirements.txt`

* run the main.py `python main.py`

* run app.py `streamlit run app.py`



