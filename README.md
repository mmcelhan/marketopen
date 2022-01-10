# marketopen
Package that returns if the stock market is open given a date

![image of usage](https://github.com/mmcelhan/marketopen/blob/main/image/market_open_usage.png)

## Examples:

### Sunday
marketopen.market_open('2021-11-28')
Returns False

### Monday
marketopen.market_open('2021-11-29)
Returns True

### Thanksgiving 2023
marketopen.market_open('2023-11-23')
Returns True

#### Fourth of July
marketopen.market_open('2021-07-04')
Returns False

## Installation Information
Install from github with the following command (Windows):

pip install git+https://github.com/mmcelhan/marketopen.git#egg=marketopen

## Lunar Dates
Easter / Good Friday are based on the lunar calendar. I hard coded these out until 2030, so if you're using this package into 2031 and beyond it won't catch those

## More information here:
https://lamplightlab.com/2021/11/28/stock-market-open-python-package/
