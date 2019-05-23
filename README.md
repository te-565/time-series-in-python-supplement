# Time Series in Python

Speaker notes and additional resources for the Python Time Series course

# Time Series in Python

### General Terms

* TimeStamp Object: Stores a date / time value. Plays nice with Python datetime functionality.
* TiemDelta: Stores a time period value.
* DateTimeIndex: A series of individual TimeStamp objects. Can be incorporated into a DataFrame, ideally as an index.
* Resampling: Transforming a time series to change the frequency. There are two types of resampling:
	- Upsampling: Increasing the frequency of the samples
	- Downsampliong: Decreasing the frequency of the samples
* Decomposition: Breaking the time series down into the underliying componenents (e.g. trend, seasonal, residuals)
* Autocorrelation: Shows the degree of similarity between the values in a time series.


### Specific Resources

* [Python Date / Time Formats](http://strftime.org/)
* [Pandas Frequency Codes](https://stackoverflow.com/questions/35339139/where-is-the-documentation-on-pandas-freq-tags)
* [Pandas Time Series / Date Functionality](https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html)
* [Pandas Date Offset](http://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html#dateoffset-objects)
* [Pandas Timestamp Reference](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Timestamp.html)
* [Pandas date_range Reference](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.date_range.html)
* [Pandas Timedelta Reference](https://pandas.pydata.org/pandas-docs/stable/user_guide/timedeltas.html)
* [Pandas Date Offset Reference](https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html#timeseries-offset-aliases)
* [Python datetime Reference](https://docs.python.org/3/library/datetime.html)
* [What is Autocorrelation?](https://www.displayr.com/autocorrelation/)
* [Autocorrelation Plot (Correlogram)](https://www.dummies.com/programming/big-data/data-science/autocorrelation-plots-graphical-technique-for-statistical-data/)
* [Autocorrelation in Python](https://s3.amazonaws.com/assets.datacamp.com/production/course_4267/slides/chapter2.pdf)
* [A Gentle Introduction to Exponential Smoothing](https://machinelearningmastery.com/exponential-smoothing-for-time-series-forecasting-in-python/)
* [Introduction to Simple Exponential Smoothing (SES)](https://www.statisticshowto.datasciencecentral.com/exponential-smoothing/)
* [Holt Winters Forecasting for Dummies](https://grisha.org/blog/2016/01/29/triple-exponential-smoothing-forecasting/)
* [Autoregression Models for Time Series Forecasting With Python](https://machinelearningmastery.com/autoregression-models-time-series-forecasting-python/)
* [Time Series Analysis in Python](http://www.blackarbs.com/blog/time-series-analysis-in-python-linear-models-to-garch/11/1/2016)
* [A Gentle Introduction to Autocorrelation and Partial Autocorrelation](https://machinelearningmastery.com/gentle-introduction-autocorrelation-partial-autocorrelation/)
* [ARIMA models in Python](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/)
* [What a p-value tells you about Statistical Data](https://www.dummies.com/education/math/statistics/what-a-p-value-tells-you-about-statistical-data/)
* [How to read and write scientific notation](https://www.dummies.com/education/math/algebra/how-to-write-numbers-in-scientific-notation/)	
* [A Gentle Introduction to Box-Jenkins Models](https://machinelearningmastery.com/gentle-introduction-box-jenkins-method-time-series-forecasting/)


### Tutorials & Books

* [Forecasting: Principles and Practice Book](https://otexts.com/fpp2/)
* [DataQuest Time Series Tutorial](https://www.dataquest.io/blog/tutorial-time-series-analysis-with-pandas/)
* [A comprehensive beginner’s guide to create a Time Series Forecast (with Codes in Python)](https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/)
* [Time Series Forecasting in Python Cheat Sheet](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/)
* [Kaggle Time Series Analysis in Python (Part 1)](https://www.kaggle.com/kashnitsky/topic-9-part-1-time-series-analysis-in-python)
* [Kaggle Time Series Analysis with Facebook Prophet](https://www.kaggle.com/kashnitsky/topic-9-part-2-time-series-with-facebook-prophet)
* [Example Notebook with Prophet](https://nbviewer.jupyter.org/github/departmentfortransport/ds-highwaysEnglandAPI-example/blob/master/python-example.ipynb)




