# Financial planner tools
This project has incorporated financial tools to see whether investers have sufficient for emergency uses or for retirement.

Under the financial planner for emergencies module, investors will be able to visualize their current savings using this tool. They can then assess whether they have sufficient reserves for an emergency fund.

Under the financial planner for retirement module, it will forecast investors' retirement portfolio's performance over the next 30 years. To accomplish this, the program will use the Alpaca SDK to perform an Alpaca API call to obtain historical pricing data for Monte Carlo simulations.

---

## Technologies

This project leverages Jupyter notebook and Pandas.

---

## Installation Guide

Before running the application, first import the following libraries and dependencies:

```python

import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline
```

Then, create the .env file with your Quandl and Alpaca API keys to fetch the financial data online.

---

## Contributors

Initial code is provided by: UC Berkeley Fintech Bootcamp

Code is modified by: Kevin BaRoss [[LinkedIn](https://www.linkedin.com/in/kevin-baross/)]


---
## License
MIT
