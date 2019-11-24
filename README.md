# FunViz - Style Description 

For multiple calculation the expected growth rate is used.<br/>
Time Frame: Current Year to (Curren Year + 2 Years)<br/>
In case there is no earnings forecast, the time frame is from two years in the past to the current year.<br/>
Time Frame: (Current Year - 2 Years) to Current Year

## Base
#### Plots earnings per share, normal multiple, dividend, stock price
If exp. growth rate < 15% --> Earnings Multiple = 15<br/>
If exp. growth rate > 15% --> Earnings Multiple = exp. growth rate
## PE15
#### Analogous to Base
Earnings Multiple = 15<br/>
## PEG85
#### Analogous to Base, inspired by the Benjamin Graham formula
If exp. growth rate < 0% --> Earnings Multiple = 8.5<br/>
If exp. growth rate > 0% --> Earnings Multiple = exp. growth rate + 8.5
## PE-Plot
#### Plots the PE-Ratio over the last 10 years
## REIT
#### Plots Operating Cash Flow (FFO), currently no forecasting data
OCF Multiple = 15


