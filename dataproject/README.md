# Data analysis project

Our project is titled **Coronavirus mentions in The Guardian** and is an analysis of data from the British newspaper *The Guardian* and *Johns Hopkins University*. We collected every article that mentions the Coronavirus from *The Guardian* using their API and we then cleaned and structured the data in order to present it in a graph. Furthermore, we collected data from *John Hopkins University* over the confirmed daily cases of Coronavirus in the top 10 most affected countries, which we also present in a graph. 

The **results** of the project can be seen from running [Handin_DataProject.ipynb](Handin_DataProject.ipynb). If you wish to recreate the results of this project you can get the necessary data from the following files: 

1. Data.xlsx 
2. articles_corona.csv.zip 
3. articles_day.csv
4. links_corona.csv

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the installation and import of the following packages:

``import requests``

``import json``
 
``mport pandas as pd``
 
``from bs4 import BeautifulSoup``
 
``import scraping_class``
  
``import re``
  
``import numpy as np``
  
``import seaborn as sns``
  
``import matplotlib.pyplot as plt``

``import datetime``
 
``import nltk``
 
``import matplotlib.dates as mdates``
 
``from matplotlib.transforms import Transform``
 
``from matplotlib.ticker import (AutoLocator, AutoMinorLocator, LinearLocator)``
 
``import matplotlib.cbook as cbook``
 
``from time import sleep``


