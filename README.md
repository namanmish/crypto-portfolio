# crypto-portfolio

Portfolio means the balance of the token where you need to add deposits and subtract withdrawals. 
Let us assume you are a crypto investor. You have made transactions over a period of time which is logged in a CSV file. 

Given no parameters, return the latest portfolio value per token in USD
Given a token, return the latest portfolio value for that token in USD
Given a date, return the portfolio value per token in USD on that date
Given a date and a token, return the portfolio value of that token in USD on that date
The CSV file has the following columns

timestamp: Integer number of seconds since the Epoch
transaction_type: Either a DEPOSIT or a WITHDRAWAL
token: The token symbol
amount: The amount transacted

Crypto exchange rates are obtained from https://nomics.com/.