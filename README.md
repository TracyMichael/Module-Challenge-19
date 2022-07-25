# Module-Challenge-19


---

## Technologies


The Application has specific technologies that will be needed to run properly.


**Languages Required:** *Python*

**Libraries Required:** *Streamlit, dataclasses, typing, datetime, pandas, hashlib*

Before running the application the following Libraries will need to be imported:

```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3, Account, middleware
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
import os
import requests
from dotenv import load_dotenv
load_dotenv("SAMPLE.env")
from bip44 import Wallet 
from web3.gas_strategies.time_based import medium_gas_price_strategy
from crypto_wallet import generate_account, get_balance, send_transaction
```

Further details denoting requirements and verions are available in the requirements file.            

[Requirements](./requirements.txt)

---

## Installation Guide

This Blockchain app will not work without the proper technologies listed above.  To ensure you have the applicable tools please install the requirements for the Fintech Finder using the text file in the Module-Challenge-19 folder as follows:

In The Terminal Run:

```python

pip install -r requirements.txt

```
---

## Usage


### **For Coders:** 

1. Create Crypto Wallet Python File with 3 functions: generate_account(), get_balance(), send_transaction().
2. Reference Candidate Database to display Fintech professional's information.
3. Create Streamlit Code
4. Use Streamlit code to gather user inputs.

### **For Users:** 

The application uses Streamlit to host the Blockchain application

1. Run Streamlit run fintech_finder.py in terminal and browse the Website.
2. Select A Person
    1. Add Sender + Press Enter
    2. Add Receiver + Press Enter
    3. Add Amount + Press Enter
    4. Click Add Block Button
2. Select the Number of Hours you'd like the person to work. (Be mindful of cost and available funds.)
3. Send the transaction.


**A display of the Sharpe Ratio Chart is listed below**

![BC](https://github.com/TracyMichael/Module-Challenge-18/blob/main/Images/Streamlit%20Blockchain%20and%20Validation.png)


---

## Contributors

Tracy Davis <TracyMDavis88@gmail.com>

[Tracy Davis LinkedIn](https://www.linkedin.com/in/tracy-davis-mba-ma-2940a232/)

---

## License

MIT License

Copyright (c) [2022] [Tracy Davis]