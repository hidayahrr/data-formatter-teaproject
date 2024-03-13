# Data-Formatter-Teaproject
This is a data formatter functions, built as a contribution to the Tea Project.
Functions to format data such as numbers, dates, or currencies in various formats. 

## Requirements:
Web Browser - Can be used as an emulator to build applications.
Internet - Because many use CDN and to make it easier to find solutions to all problems.
 
## How To Use (Python):
### Example Syntax:
from data_formatting_helpers import format_currency, format_date
#### Format currency
price = 1300.75
formatted_price = format_currency(price, 'USD')
print(formatted_price)  # Output: $1,300.75
#### Format date
date = '2023-04-17'
formatted_date = format_date(date, 'yyyy-MM-dd')
print(formatted_date)  # Output: 2023-04-17

## Release Date
v1.0.0 : 13 March 2024
