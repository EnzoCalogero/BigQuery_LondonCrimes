## BigQuery London Crimes

The 3 jupiter notebooks are answering three questions about the Crimes between 2008 and 2016 in London: 

1. In the Criminal events is there any seasonal effect?  

2.  On which of the London Boroughs the number of Crimes is increasing, and which is decreasing? 

3. Which type of criminal event is increasing and which is decreasing? 

The project use an open dataset, which is part of *London Datastore* (https://data.london.gov.uk/) with over 700 datasets to help anyone to understand the city, and develop solutions to London’s problems. 

One useful thing about this dataset is that is directly available with both the Google Big Query from your desktop and with Kaggle.com using their Jupiter notebook. 

The Kaggle version of these  notebooks is available as Kaggle Jupiter as well (https://www.kaggle.com/enzus01/christmas-effect-on-london-crimes, https://www.kaggle.com/enzus01/where-in-london-criminality-is-increasing, https://www.kaggle.com/enzus01/what-crimes-category-is-increasing-in-london) 

The Kaggle version use the library  *'bq_helper'* to access the bigquery dataset.
(with kaggle the library is pre-installed, and all the autentication and connections are handled directly by kaggle)

While the notebooks, from your desktop, used in this repository, needs the *bigquery* module from the *google.cloud* library.

The jupiter notebooks have been created using the Anaconda distribution.
and the packages *pandas-gbq* needed to be installed (using the *conda* command), to be used with the pandas package for the Big query:

*conda install pandas-gbq -c conda-forge*

For further information on how interact with the Google big query with python check the link below.

https://cloud.google.com/bigquery/docs/reference/libraries#client-libraries-install-python
