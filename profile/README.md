## What is marketblocks?

<p align="center">
    ***A single tool for the research, testing and deployment of your trading algorithm.***
</p>


marketblocks is a high performance C++ framework that drastically reduces the complexity and development time of cryptocurrency trading algorithms. It provides an abstract interface for interacting with cryptocurrency exchanges and has built-in live test and back testing run modes which can be enabled simply through changing a config file. This allows trading strategies developed with marketblocks to be both exchange and run mode agnostic.

### Key Features
marketblocks boasts the following key features:
  - A consistent and predictable API for interacting with any exchange
  - Suppport for REST API endpoints and websocket streams
  - Live, Live-Test and Back-Test run modes
  - Easily extendable config file system
  - Built-in logging framework

### Supported Exchanges
marketblocks features built-in support for the following exchanges:
  - Kraken
  - Coinbase Pro

### Images

![image](https://user-images.githubusercontent.com/43093246/169862323-9dcc4e90-9508-4027-b8f0-7720c46d6200.png)



![image](https://user-images.githubusercontent.com/43093246/169862691-26896b6a-bc97-4e73-aa0b-1194f4c50bf0.png)


### Example Strategies

[Triangular Arbitrage](https://github.com/marketblocks/triangular_arbitrage_example) - HFT, websockets, live testing

[Mean Reversion](https://github.com/marketblocks/mean_reversion_example) - Back testing, custom configs, REST API polling

