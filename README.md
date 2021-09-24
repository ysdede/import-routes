# import-routes

A tool for batch importing candles data for [jesse ai](https://jesse.trade/).  
It obtains symbol and exchange information from routes.py. Downloads candle data for symbols you are trading.


## Installation

Nothing special, place Python file inside project folder or PYTHON PATH. A pip package can be released soon.

## Usage

```console
python import-routes.py start-date
```
or run it without start-date, if no start date is specified, the system will default to two days earlier.
It's useful for executing script in a cron job to download deltas on a regular basis.  

```console
python import-routes.py
```

## Contributing
Pull requests are welcome.  
You can contact the Jesse team via [Discord](https://discord.gg/hTy5Xty9) 


## License
[MIT](https://choosealicense.com/licenses/mit/)
