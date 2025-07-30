## How are in-demand skills trending for Data Analyst?

```python

from matplotlib.ticker import PercentFormatter
df_plot= df_da_us_percent.iloc[:, :5]
sns.lineplot(data=df_plot, dashes=False, palette='tab10')
plt.gca().yaxis.set_major_formatter(PercentFormatter(decimals=0))

plt.show()

```

## Result
![Skills Top Trending](Python_Data_Project\images\skill_trend_da.png)
*Bar graph visualizing the trending top skills for data analyst in the US in 2023.*


