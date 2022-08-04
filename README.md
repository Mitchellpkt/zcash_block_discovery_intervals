Empirical analysis of Zcash block discovery times as self-reported by the miners

Lazy way to get data from bigquery txn database:

```
SELECT
  block_number,
  block_timestamp
FROM
  `bigquery-public-data.crypto_zcash.transactions`
```
