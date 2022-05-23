## What is marketblocks?
marketblocks is a high performance C++ framework that drastically reduces the complexity and development time of cryptocurrency trading algorithms. It provides an abstract interface for interacting with cryptocurrency exchanges and has built-in live test and back testing run modes. This allows trading strategies developed with marketblocks to be both exchange agnostic and run mode agnostic.

### Key Features
marketblocks boasts the following key features:
  - A consistent and predictable API for interacting with any exchange
  - Suppport for REST API endpoints and websocket streams
  - Live, Live-Test and Back-Test run modes
  - Easily extendable config file system
  - Built-in logging framework

### Supported Exchanges
The list of supported exchanges is growing every day and marketblocks already supports:
  - Kraken
  - Coinbase Pro

![image](https://user-images.githubusercontent.com/43093246/169862323-9dcc4e90-9508-4027-b8f0-7720c46d6200.png)



![image](https://user-images.githubusercontent.com/43093246/169862691-26896b6a-bc97-4e73-aa0b-1194f4c50bf0.png)


### Example Strategies

[Triangular Arbitrage](https://github.com/marketblocks/triangular_arbitrage_example) - HFT, websockets, live testing

[Mean Reversion](https://github.com/marketblocks/mean_reversion_example) - Back testing, custom configs, REST API polling

