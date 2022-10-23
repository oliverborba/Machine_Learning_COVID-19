# Projeto DIO Covid-19
Projeto Digital Innovation One em parceria com o Prof. Dr. Neylson Crepalde
```
Análise exploratória dos dados do COVID-19 com Python.
```
```
import pandas as pd
import numpy as np
from datetime import datetime
import plotly.express as px
import plotly.graph_objects as go
from statsmodels.tsa.seasonal import seasonal_decompose
import matplotlib.pyplot as plt
```
```
#Instalação ARIMA
!pip install pmdarima
from pmdarima.arima import auto_arima
```
```
!conda install -c conda-forge fbprophet -y
```
