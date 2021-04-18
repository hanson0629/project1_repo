# **BITCOIN: COMMODITY OR PORTFOLIO STRATEGY?**

## *OVERVIEW*

In this project, we compared Bitcoin's price growth to other commodities/asset class like Gold,etc. We were able to collect data from various sources for these commodities and compare the statistics to come to a conclusion about whether Bitcoin can be treated as a commodity or not. 

### *Import requests*

from io import StringIO
import csv
import pandas as pd
import numpy as np
import hvplot.pandas
import matplotlib.pyplot as plt
from pathlib import Path
from datetime import datetime
import plotly.express as px
import plotly.graph_objects as go
import seaborn as sns
from collections import Iterable

### FAQs

**1. Can Bitcoin be described as Digital Gold?**

*Our Data Analysis shows that the percent change of returns of the two assets'price action do not mimic one another and the correlation coefficient of 0.099 shows an insignificant relationship between the two assets.

<img width="598" alt="BitcoinGold" src="https://user-images.githubusercontent.com/78338890/115130202-85f41a00-9fbb-11eb-9c40-fc2ba8b5585a.png">


Graph picture

**2. How does bitcoin perform during inflation or deflation? CPI Index monthly return % change vs Bitcoin monthly return % change.

*In this Data Analysis as well, correlation coefficient of 0.099 shows an insignificant relationship between the two assets.


Graph picture

**3. How does a new asset/asset class stack up against traditional markets? Are there any relationships? (Bitcoin compared to Market Indices)

*In this Data Analysis, 

Graph Picture

**4. What is Bitcoin’s growth prospect? And is it a viable investment? 

*Bitcoin’s growth prospect would need to be gauged against a regulated growth ETF to prove its viability as an investment. Our Data Analysis shows that its distribution is spread much wider than iShares ETF indicating the significant risk involved in Bitcoin given its growth.

**5. What is Bitcoin's comparison with traditional asset classes based on their returns, volatility, and volume in the the past 5 years? (Bitcoin vs Other Traditional Assets and Indices)

*

Graph Picture




### *SOURCES*

Import method refreneced from: https://github.com/israel-dryer/Yahoo-Finance-Scraper/blob/master/yahoo-finance-tut.ipynb




