

![Languages](https://img.shields.io/badge/languages-Python%20%2F%20SQL-%238b0000?style=flat-square)

![Coincap (Price USD)](https://img.shields.io/coincap/price-usd/bitcoin?color=%23F7931A&logoColor=%234D4D4D&style=flat-square)

# Bitcoin/USD Block Fees

The ***Block Fees*** visualization helps a Bitcoiner, depending on the market conditions, volume of transactions and network activity on the blockchain, to approximately estimate the **lowest fee possible** or to have an idea of when paying too much for a transaction on the blockchain can be **avoided**. 

The graph shows the fees in both **BTC** and **USD**, as well as the **block** for which are the given fees. 

It gives an idea of when and at what time of the day the sizes of the transactions are the highest and lowest due to the connection between the fee and the size of the transaction(below you can find more information about block fees).


## Mempool API Reference

#### Get block fees for 1 month

```http
  https://mempool.space/api/v1/mining/blocks/fees/1m
```



## Acknowledgements

 - [Mempool](https://mempool.space/)



## Resources
- [Mempool API](https://mempool.space/it/docs/api/rest#get-block-fees)
- [Plotly Documentation](https://plotly.com/python/)
- [AWS Relational Database](https://aws.amazon.com/rds/)
- [More about Block Fees](https://river.com/learn/how-bitcoin-fees-work/)