## How to add a new chain

Fork this repo and add your evm chain info into `chains.json` 

Example:

```javascript
{
    "app_resource": {
        "color_chain_bg": "0x58B2AF",
        "ic_chain_select": "http://www.zdtchain.com/static/img/logo.4e5676f.png",
        "ic_chain_unselect": "http://www.zdtchain.com/static/img/logo.4e5676f.png"
    },
    "chain": "ZDT",
    "chainId": 100,
    "faucets": [],
    "infoURL": "http://www.zdtchain.com",
    "name": "ZDT Chain",
    "nativeCurrency": {
        "decimals": 8,
        "name": "ZDT",
        "symbol": "ZDT"
    },
    "network": "mainnet",
    "networkId": 100,
    "rpc": [
        "http://api.zdtchain.com",
        "http://rpc.zdtchain.com:8888"
    ],
    "shortName": "ZDT"
}
```

`app_resource` is optional, which is only affect the appearance in TokenPocket Wallet. You can follow the standard below:


![standard](https://tp-statics.tokenpocket.pro/images/custom-chains-standard-1.png)
![standard](https://tp-statics.tokenpocket.pro/images/custom-chains-standard-2.png)
![standard](https://tp-statics.tokenpocket.pro/images/custom-chains-standard-3.png)
![standard](https://tp-statics.tokenpocket.pro/images/custom-chains-standard-4.png)
![standard](https://tp-statics.tokenpocket.pro/images/custom-chains-standard-5.png)


