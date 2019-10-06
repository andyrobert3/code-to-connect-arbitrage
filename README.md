# code-to-connect-arbitrage

Objective is to build an arbitrage engine that can detect profit from the difference in forex quotes from different liquidity providers (servers) then execute trades based on the difference in prices between forex quotes. 

Arbitrage engine was a client that listened to the liquidity provider servers using socket.io (web socket).
Java client engine was used to detect and execute trades, the liquidity providers used NodeJS as servers by publishing quotes at every time interval.

Won 2nd place in Bank of America Merrill Lynch Code to Connect

![Arbitrage Poster](https://raw.githubusercontent.com/andyrobert3/code-to-connect-arbitrage/master/aribitrage.png)
