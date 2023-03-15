# ONLYOPTION
ONLY OPTION CHAIN ALICE BLUE 

# Installation
This module is installed via pip:

pip install aliceblueindia

#Prerequisites
Python >=3.11

#Getting started with API
Overview


#Using the API

from Optionchain import *

Create Optionchain Object

Optionchainlogin(user_id='',session_id='')

PremiumDashboard()

Getlix(exchange="NSE", quantity=250,segment="CE",strike=45000, code="35347", op_pr="34.00",name="NIFTY", expiry="2023-03-016")

GetMarginBasedOption(tab_name="bullish", name="NIFTY",   expiry="2023-03-16",spot_price="18794.00",code="62809",exchange="NSE")

MoreCards(tab_name="bullish",name="NIFTY",expiry="2023-03-16",spot_price=18193.2,exchange="NSE")

OpenInterest(date="2023-02-16",cm="true",cm_1="true",cm_2="true",short=1,long=5)

optionGreeks(strike_price=17450,spot_price=18765,price=777.90,days_to_expire=1)

OptionSpan(expiry="2023-03-16",name="NIFTY",strike=18200,segment="CE", quantity=50,op_pr=82.95,code="55902",trading_symbol="NIFTY23JAN18200CE")

OptionStrategy(tab="bullish",combo=3,expiry="2023-03-16",ltp=18193.25,name="BANKNIFTY", days_to_expire=1,target_days=0,exchange="NSE")

StrategyBuilder(expiry= "2022-11-24",quantity= 50,op_type= "c",strike= 18200,tr_type= "b",op_pr= 82.95,trading_symbol= "NIFTY22NOV18200CE",spot_price= 18194.2,code= "53395",exchange= "NSE",days_to_expire= 3,target_days= 0)


