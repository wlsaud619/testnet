# Public Testnet for Columbus-4
 
## Steps

* September 3, 2020 06:00 KST, Collect Genesis Addresses
* September 3, 2020 24:00 KST, Collect Genesis Transactions
* September 4, 2020 15:00 KST, Launch Tequila-0004 network


## How to submit Genesis Address
Add your address line on the last part of [address.json](address.json) via Pull Request.

## How to generate Genesis Transaction
Download the `genesis-template`, which will be released after we gather all Genesis Accounts, and place that file to `~/.terrad/config/genesis.json` and execute following command. 
```
terrad gentx --name my_account --amount 10000000000uluna
```

The file will be store in `~/.terrad/config/gentx/gentx-xxxx.json`. Please upload `gentx-xxxx.json` file to [gentx](gentx) folder via Pull Request.
