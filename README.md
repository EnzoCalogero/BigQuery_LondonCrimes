# BigQuery London Crimes (Blog Post)

### Software Requirements and packages

This project was created using a jupyter notebook, python 3.6 and the following python libraries:
* numpy 1.15.0
* pandas 0.23.4
* pandas-gbq 0.6.1
* google-cloud-bigquery 1.5.0
* scikit-learn 0.19.1
* matplotlib 2.2.2
* seaborn 0.8.0

The Kaggle version use the library  *'bq_helper'* to access the bigquery dataset.
(with kaggle the google connection library is pre-installed, and all the authentication and connections are handled directly by kaggle)

For further information on how interact with the Google big query with python check the link below.

https://cloud.google.com/bigquery/docs/reference/libraries#client-libraries-install-python

### Motivation

The 3 jupiter notebooks are answering three questions about the Crimes between 2008 and 2016 in London: 

1. In the Criminal events is there any seasonal effect?  

2.  On which of the London Boroughs the number of Crimes is increasing, and which is decreasing? 

3. Which type of criminal event is increasing and which is decreasing? 

### Files

1. London Crimes Trends.ipynb

General introduction to the thematic of the repository. 

2. First Question.ipynb

All the analysis steps for answering the first question.

3. Second Question.ipynb

All the analysis steps for answering the second question.

4. Third Question.ipynb

All the analysis steps for answering the third question

5. README.md

The present document.


### Data Used

The project use an open dataset, which is part of *London Datastore* (https://data.london.gov.uk/) with over 700 datasets to help anyone to understand the city, and develop solutions to London’s problems. 

One useful thing about this dataset is that is directly available with both the Google Big Query from your desktop and with Kaggle.com using their Jupiter notebook. 

### Results

There is a seasonal pattern, the number of crimes in December and January is reduced 
(We may call it Christmas effect :) ), and we have an increase in November as a sort of rush before holiday.
A similar pattern appears in the Summer time, where there is a peak in June and July with a significant decrease on the holiday season (August).

Other good news, the number of crime is decreasing over time.


### Note

The Kaggle version of these  notebooks is available as Kaggle Jupiter as well https://www.kaggle.com/enzus01/christmas-effect-on-london-crimes, https://www.kaggle.com/enzus01/where-in-london-criminality-is-increasing, https://www.kaggle.com/enzus01/what-crimes-category-is-increasing-in-london


