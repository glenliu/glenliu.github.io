# System overview #
## Performance review

|Input|Process|Output|
|:---       |:------ |:------- |
|Trade (buy, sell)|   | Return, Risk, Ratio (Sharpe, etc) |
|Daily price |Calc performance (return:TWRR, MWRR, volatility);  |plot|
|Benchmark|  |  |
|Risk free rate |  |  |

### Input data
- Trade
  - buy/sell
  - Price
  - cost, fee
  - size
  - date
- daily Price
  - ticker
  - price OHLC
  - date
  - special
    - dividend
    - split
    - stock dividend
    - trade closed period
- Benchmark
  - Price
  - date

### Return
- TWRR
- DWRR

### Risk
- Volatility
- Beta
- VAR
- Max DD

### Query
- position
- performance
