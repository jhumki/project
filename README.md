# project
import numpy as np 
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
data=pd.read_excel("arif.xlsx")
data.head()
data.tail()
data.columns
data['kills']
0       0
1       1
2       2
3       1
4       0
       ..
9995    2
9996    0
9997    0
9998    0
9999    0
Name: kills, Length: 10000, dtype: int64
data['headshotKills']
0       0
1       1
2       1
3       0
4       0
       ..
9995    0
9996    0
9997    0
9998    0
9999    0
Name: headshotKills, Length: 10000, dtype: int64
data['heals']0       0
1       0
2       8
3       0
4       0
       ..
9995    0
9996    0
9997    0
9998    0
9999    0
Name: heals, Length: 10000, dtype: int64
​
