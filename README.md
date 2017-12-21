# Binance Trader (Beta)
@yasinkuyu - 2017

This is an experimental bot for auto trading the binance.com exchange.

![Screenshot](https://github.com/yasinkuyu/binance-trader/blob/master/screenshot.png)

## Configuration

    1. Signup Binance ( Referral url: http://www.binance.com/?ref=10701111 )
    2. Enable Two-factor Authentication    
    3. Go API Center, https://www.binance.com/userCenter/createApi.html
    4. Create New Key
       [✓] Read Info [✓] Enable Trading [X] Enable Withdrawals 
    6. Rename config.sample.py to config.py
    7. Get an API and Secret Key, insert into config.py

        API key for account access
        api_key = ''
    
        Secret key for account access
        api_secret = ''
    
        API Docs: https://www.binance.com/restapipub.html
    
 
## Requirements

    sudo easy_install -U requests
    or 
    sudo pip install requests
    
    Python 2.7

## Usage

    python trader.py
    
    Behind...
    
    Enter your Cryptocurrency symbol. Ex: IOTABTC
    (All binance symbols are supported.)
     
## DISCLAIMER

    I am not responsible for anything done with this bot. 
    You use it at your own risk. 
    There are no warranties or guarantees expressed or implied. 
    You assume all responsibility and liability.
     
## License

    Code released under the MIT License.

## Contributing

    Fork this Repo
    Commit your changes (git commit -m 'Add some feature')
    Push to the changes (git push)
    Create a new Pull Request
    
    Thanks all for your contributions...
    
## Roadmap

    - Order tracking
    - Binance/Bittrex/HitBTC/Liqui Arbitrage  

---
