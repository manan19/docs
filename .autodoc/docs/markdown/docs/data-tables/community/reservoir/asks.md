[View code on GitHub](https://dune.com/docs/data-tables/community/reservoir/asks.md)

## Reservoir.asks

This section of the app technical guide covers the `reservoir.asks` table, which contains records with information about each listing. The table includes various columns such as `id`, `kind`, `status`, `contract`, `token_id`, `maker`, `taker`, `price`, `start_price`, `end_price`, `currency_address`, `currency_symbol`, `currency_price`, `dynamic`, `quantity`, `quantity_filled`, `quantity_remaining`, `valid_from`, `valid_until`, `nonce`, `source`, `fee_bps`, `expiration`, `raw_data`, `created_at`, and `updated_at`. Each column is described in detail, including its data type and a brief explanation of its purpose.

The purpose of this guide is to provide developers with a clear understanding of the `reservoir.asks` table and its columns, as well as how to query the table. The guide includes two query examples that can be found at the provided links. Developers can use this information to build applications that interact with the `reservoir.asks` table, such as a marketplace or trading platform.

For example, a developer building a trading platform could use the `price` column to display the current price of a listing, the `quantity` column to show the amount of tokens available for purchase, and the `valid_from` and `valid_until` columns to display the start and end times of the listing. The `maker` and `taker` columns could be used to identify the parties involved in the transaction, and the `fee_bps` column could be used to calculate the listing fee.

Overall, this section of the app technical guide provides a comprehensive overview of the `reservoir.asks` table and its columns, as well as practical examples of how to use the information to build applications that interact with the table.
## Questions: 
 1. What is the purpose of the `reservoir.asks` table in the Dune Docs app?
- The `reservoir.asks` table contains records with information about each listing in the app.

2. What kind of data is stored in the `price` column of the `reservoir.asks` table?
- The `price` column stores the current price of the listing in native currency.

3. Is there any information in the `reservoir.asks` table about the transaction history of a listing?
- No, there is no information in the `reservoir.asks` table about the transaction history of a listing.