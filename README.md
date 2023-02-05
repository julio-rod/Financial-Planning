# Monte Carlo Simulation for Portfolio Project
### Introduction
This project is designed to help credit union members determine the expected range of returns for their portfolios over a given time horizon, using Monte Carlo simulation.

# Data
The project uses historical stock prices for two assets - AGG (Bonds) and SPY (Stocks). The data for these assets was collected for the past 10 years.

# Methodology
A Monte Carlo simulation was used to model the cumulative returns of the portfolio over a given time horizon. The simulation was run for both 10 and 30 years, using 10 samples each time. Note:  ⭐️Only running this 10x to show cell is performing correctly, feel free to change the `num_simulation`⭐️

# Results
The simulation results were used to calculate the lower and upper 95% confidence intervals for the cumulative returns of the portfolio over the 10 and 30-year horizons.

# Conclusion
The results of the Monte Carlo simulation provide a range of expected returns for the credit union members' portfolios over the 10 and 30-year horizons. This information can be useful in helping the members make informed decisions about their investments. However, it is important to keep in mind that this is only a model and actual results may vary.
# Libraries and Dependencies

`from pathlib import Path`

`import os`

`import requests`

`import json`

`import pandas as pd`

`from dotenv import load_dotenv`

`import alpaca_trade_api as tradeapi`

`from MCForecastTools import MCSimulation`


`%matplotlib inline`

# Contributors

[Demi Gao](https://www.linkedin.com/in/demi-g-9ba9b6243)

[Julio Rodriguez](https://www.linkedin.com/in/julio-rodriguez-5166b0143/)

# Sources

[Bootcamp Spot](https://courses.bootcampspot.com/courses/2916/external_tools/249)

[Google](https://www.google.com/)

[AskBCS Learning Assistant](https://slack.com/)