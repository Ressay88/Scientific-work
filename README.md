# Scientific-work
import pandas as pd
import numpy as np
gol=pd.read_csv('/content/US_Stock_Data.csv')
#display(gol)
selected_data = gol[['Date', 'Crude_oil_Price', 'Natural_Gas_Price']]
selected_data
