# Disclaimer

```shell
	This source is foward from unknown people, If this violates someone's copyright please notify me
```
# Usage

### Prerequisites
- [Node js](https://nodejs.org/en/)

### Clone or download the repo

```shell
git clone https://github.com/lephuoccan/BinanceOHLCV
# or click "Download Zip" button
```
### Edit config.js
Example:
```shell
  symbol: 'BTCUSDT',
  timeframe:'1m',
  fromTS:'01/30/2021 12:23:13',	  //Format - mm/dd/yyyy hh:mm:ss;
  toTS:'09/02/2021 20:47:13',	  //Format - mm/dd/yyyy hh:mm:ss;
  fileName:'BTCUSDT_1m_data.csv', //Export to file name.csv
```
### Run
```shell
  node kline.js
```