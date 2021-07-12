# SpeedRuntimeDatascience
Increasing the runtime in data analysis and multiprocessing using python

## Time Series Data Processing with Pandas

If one works with time series data, chances are you have spent a significant amount of time accounting for missing records or aggregating data at a particular temporal granularity either via SQL queries or writing custom functions.
Pandas has a very efficient resample function that can help you process the data at a particular frequency by simply setting the DataFrame index to be the timestamp column.

## Speed up pandas apply() via Swifter

Sometimes running into long wait times for processing pandas columns even with running code on a notebook with a large instance. Instead, there is an easy one word addition that can be used to speed up the apply functionality in a pandas DataFrame.
One only has to import the library swifter.

## Multiprocessing in Python

While we are on the topic of decreasing time complexity, I often end up dealing with datasets that I wish to process at multiple granularities.
Using multiprocessing in python helps me save that time by utilizing multiple workers.
