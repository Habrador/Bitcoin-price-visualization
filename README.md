# Bitcoin price visualization

If you study the history of the cryptocurrency <a href="https://en.wikipedia.org/wiki/Bitcoin" target="_blank">bitcoin</a> you realize that bitcoin has been a really rough ride since it was launched around 2009. If you haven't studied the history of bitcoin you should read the book <a href="https://www.amazon.com/Digital-Gold-Bitcoin-Millionaires-Reinvent/dp/006236250X" target="_blank">Digital Gold</a> by Nathaniel Popper which covers events up to 2014, so you have to google the rest. If you google you will see that bitcoin reached a price of around $20000 in December 2017, then it crashed, but has since then recovered, reaching a new ATH in 2020. 

You keep seeing comments that bitcoin is a bubble and it will crash again. But listening to comments by random people on the Internet is not always a good idea. A better idea is to use data and study what has happened before. And you have to use as much data as possible! I've here used data from all the way back in 2010 when the price of a Bitcoin was just $0.09. You can find that data in this repository both as a csv file and in the LibreOffice Calc document! 


## Price

The data I found is from various sources. Most of it is from Coindesk but when they stopped making data available to the public I had to change to data from [Yahoo](https://finance.yahoo.com/chart/BTC-USD). The data consists of one price during the day and not necessarily the highest or lowest price during the day, but that's not a big deal if you look at the price in a wider perspective. 

If you look at all the data you can clearly see that it looks like the classic bubble chart.

<img src="/_images/bitcoin-price.png" width="400">

<img src="/_images/bubble-phases.png" width="400">

To better see what has happened from an historical point-of-view, one way is to change the price axis to a logarithmic scale. You can now better see the tops and bottoms:

<img src="/_images/bitcoin-price-log" width="400">

It's difficult to know where a bottom and a top is. But I've defined a top as the highest price before a fall with more than 50 percent to a bottom. A bottom is the lowest price before a raise to a top which is higher than the top before the fall. A crash is defined as over when the price reaches a new ATH, which bitcoin did 2020-12-01 meaning that the 2017 crash was over.   


## Bubbles and crashes

Bitcoin has crashed the following times:

* 2011-06-08: -93 percent
* 2013-04-09: -71 percent
* 2013-12-04: -85 percent
* 2017-12-16: -84 percent
* 2021-04-16: -53 percent
* 2021-11-08: -77 percent

<img src="/_images/bitcoin-crash-graph.png" width="400">

Bitcoin has crashed so many times the chart is cluttered, so this is a more visible one:

<img src="/_images/bitcoin-crash-graph-visible.png" width="400">

Here I've removed the data of previous crashes except the end points to make it even more visible:

<img src="/_images/bitcoin-crash-graph-minimalistic.png" width="400">

Now we can see how well the "classic bubble chart" fits the previous crashes:

<img src="/_images/bitcoin-bubble-1.png" width="400">
<img src="/_images/bitcoin-bubble-2.png" width="400">
<img src="/_images/bitcoin-bubble-3.png" width="400">
<img src="/_images/bitcoin-bubble-4.png" width="400">
<img src="/_images/bitcoin-bubble-5.png" width="400">

You can see that the price crashed below the mean line except in one case where the price bounced on the mean line. 


## Other

This chart visualizes the daily percentage changes for all dates. 

<img src="/_images/bitcoin-daily-changes.png" width="400">

I also tried to make charts to compare the bubbles before the crash and he recovery after a crash, but I'm not sure how good they are...

<img src="/_images/bitcoin-bubble-crashes.png" width="400">

<img src="/_images/bitcoin-recovery.png" width="400">
