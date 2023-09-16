# Time and Location Analytics of Olist E-Commerce

## Dataset
The dataset can be accessed in Dataset folder. It consists a CSV file as `olist_orders_dataset_full.csv`.

You can find the update dataset through [Kaggle Website](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Package
Please ensure that you have import important packages as follows:
```
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
```

For geo location analysis, it requires additional packages as follows:
```
!pip install --upgrade requests -q
!pip install geopandas -q

!pip install pointpats -q
from pointpats import centrography

from matplotlib.patches import Ellipse

!pip install contextily -q
import contextily
```

## Step 1: Basic Analysis
Basic analysis consists of descriptive analysis of Olist transaction per category.

## Step 2: Time Series Analysis
Time series analysis explores the trend of purchase rate of specific goods each day.

## Step 3: Geolocation Analysis
Geo location analysis explores the quantity of each goods on each brazilian location. 
