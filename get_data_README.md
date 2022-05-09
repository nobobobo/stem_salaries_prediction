# How to Get Kaggle Data by API

1. install `opendatasets` package by:
```
!pip install opendatasets
import opendatasets as od
```

2. use `od.download` to download data

```
od.download("https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries", "./data/")
```

3. While downloading, it would prompt Kaggle credentials. Please enter your Kaggle username and Kaggle Key

    ***Please refer [here](https://github.com/JovianML/opendatasets/blob/master/README.md#kaggle-credentials) to find your API credentials***

    <br>

    **Sample Output:**

    Please provide your Kaggle credentials to download this dataset. Learn more: http://bit.ly/kaggle-creds

    Your Kaggle username:

    nobobobo

    Your Kaggle Key:

    ································

    Downloading data-science-and-stem-salaries.zip to ./data/data-science-and-stem-salaries


4. Now data is ready!