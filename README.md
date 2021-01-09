# COVID-19-Analysis

## About

Created a dynamic map using time series data of Coronavirus infections around the world using GeoPandas and Pandas Python libraries. The time series data are acquired from the 2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE.


## Dataset

Data Source :  https://github.com/CSSEGISandData

## Prerequisites

-> pandas==1.0.3
-> pillow==2.1.0
-> mapclassify==2.4.0
-> descartes==1.1.0
-> geopandas==0.8.0


## Installation steps

### Optional: Create virtual environment for python

```
pip install --user virtualenv
virtualenv env
source env/bin/activate
```

### Clone the repository and install required packages

```
git clone https://github.com/yashaswi2311/COVID-19-Analysis.git
cd COVID-19-Analysis
pip3 install -r requirements.txt
Run Python dynamic_mapping_of_covid_cases.py on command line
```
