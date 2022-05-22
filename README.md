# Forecasting-and-analyzing-the-Financial-Market :man_scientist: :computer:


![screem.png](https://github.com/M-MSilva/Forecasting-and-analyzing-the-Financial-Market/blob/main/Images/allPictures.png) 

## Important notes about the project

This project was built with numerous tools and technologies, this is a summary document. So if you want more statistical and computational information, see [Google Collaboratory](https://github.com/M-MSilva/Forecasting-and-analyzing-the-Financial-Market/blob/main/jupyter%20notebook/Forecasting_and_analyzing_the_Financial_Market.ipynb), to read about the findings found in the project review the [Report](https://github.com/M-MSilva/Forecasting-and-analyzing-the-Financial-Market/blob/main/Report/Report_of_forecast__M_MSilva.pdf) and see more information about datasets at [Stooq](https://stooq.com/t/) and [Data Reader API](https://pandas-datareader.readthedocs.io/en/latest/readers/stooq.html). It is worth mentioning that the time series forecasting method was not implemented in the cloud, because every time we have new data inserted in the dataset we must retrain the model, which is a good practice for time series methods, justifying the non-implementation of the method.

## About this project

The purpose of this project is to forecast the closing price of the Apple stock market, in addition, we **answer some business questions** that are in the jupyter notebook. Furthermore, this is a complete project as we go through several steps of a usual data science project such as data collection, feature engineering, data cleansing, data transformation, data visualization, data analysis, modeling.

## Applications 

The current project can be used to help users, companies and shareholders in investments, decision making and understanding of market behavior. Through this project, shareholders can choose whether or not to invest in Apple's stock exchange or choose to invest in others. Although this program is part of my personal portfolio, please feel free to use it for studies, repairs and improvements. :call_me_hand:

## Motivation and Future challenges

This project was developed to be part of my personal portfolio, which served both to test my skills and for my learning, since countless technologies could be used in it. Despite being an end-to-end project, it still needs some future improvements, as I initially intended to make a program to predict several different investment markets and compare them, to the point where I could choose the best among them. I believe it would be possible to create several models for this, however, all data analysis, accuracy and performance tests should also be done for each of the markets, in addition to the execution time that would be very long even to implement it. :smiley:


## Instructions to run and/or compile the code

### Initial Requirements

The application is already running and it is not necessary to install anything on your machine, however, if you want to run the application locally, you must install the  [Python](https://www.python.org/downloads/release/python-390/) language on your machine. In addition, you must have the libraries listed below on your machine.

### Built With

* [Pandas 1.3.5](https://pandas.pydata.org/pandas-docs/version/1.3/getting_started/install.html);
* [Imblearn 0.8.1](https://imbalanced-learn.org/stable/whats_new/v0.8.html?highlight=0%208%201);
* [seaborn 0.11.2](https://pypi.org/project/seaborn/0.11.2/);
* [statsmodels](https://www.statsmodels.org/devel/release/version0.10.2.html);
* [numpy 1.21.6](https://numpy.org/devdocs/release/1.21.6-notes.html);
* [keras 2.8.0](https://faroit.com/keras-docs/2.0.8/);
* [tensorflow 2.8](https://www.tensorflow.org/api_docs/python/tf);
* [pandas datareader 0.9.0](https://pandas-datareader.readthedocs.io/en/latest/whatsnew.html#v0-9-0-july-10-2020);
* [scikit-learn 1.0.2](https://scikit-learn.org/stable/whats_new/v1.0.html).



### Running the Code

The installations of the libraries are already explained in the links above, but if you want to be in the same versions I do:

```bash
pip install scikit-learn==1.0.2
```
```bash
pip install numpy==1.21.6
```
```bash
pip install pandas==1.3.5
```
```bash
pip install imblearn==0.8.1
```
```bash
pip install statsmodels==0.10.2
```
```bash
pip install keras==2.8.0
```
```bash
pip install tensorflow==2.8.0
```
```bash
pip install pandas_datareader==0.9.0
```

done, for information about jupyter notebook see:

[Jupyter Notebook](https://jupyter.org/install)


and see the application run on your machine. :open_mouth:


## Contributing

Criticism, doubts and suggestions feel free to send me:

e-mail: marcosmatheusdepaivasilva@gmail.com

LinkedIn: https://www.linkedin.com/in/marcos-matheus-silva-089699b3/ :hugs:

## Author

Marcos Matheus de Paiva Silva

## Credits

The code written in Google Colaboratory was based on the steps of the book (Aurelien Geron,2019), (ZAREMBA; SUTSKEVER; VINYALS,
2014), (SAK; SENIOR; BEAUFAYS, 2014). In addition, this code was developed based on everything I learned from: Jesse E.Agbe, Siddhardhan, Lucas Grassano Lattari, Shashank Kalanithi, Walisson Silva, Israel Dryer, Fernando Nakamuta,  Alex Freberg, Jason Brownlee.


## License

This project is licensed under the MIT License - see the file [LICENSE](LICENSE) for more details.
