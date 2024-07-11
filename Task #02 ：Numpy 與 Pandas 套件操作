import pandas as pd
import numpy as np

d = [
    {'city': 'Austin', 'visitor': 139, 'weekday': 'Sun'},
    {'city': 'Dallas', 'visitor': 237, 'weekday': 'Sun'},
    {'city': 'Austin', 'visitor': 326, 'weekday': 'Mon'},
    {'city': 'Dallas', 'visitor': 456, 'weekday': 'Mon'}
]
grouped = df.groupby('weekday')
result = grouped.agg({'visitor': 'sum'})
print(result)

import pandas as pd
import numpy as np

df = pd.read_csv('https://raw.githubusercontent.com/kiang/pharmacies/master/data.csv')

grouped = df.groupby('縣市')
pharmacy_count = grouped.agg({'醫事機構代碼': 'count'})
result = pharmacy_count.sort_values('醫事機構代碼',ascending=False)
print(result[0:5])
