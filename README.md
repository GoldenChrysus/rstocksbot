# rstocksbot
Discord chat bot based on [discord.js](https://github.com/hydrabolt/discord.js) for the [/r/stocks](https://www.reddit.com/r/stocks/) subreddit [chat server](http://www.r-stocks.com/chat/).

## Dependencies 
* [discord.js](https://www.npmjs.com/package/discord.js) - 10.0.1
* [fs](https://www.npmjs.com/package/fs) - 0.0.1-security
* [node-opus](https://www.npmjs.com/package/node-opus) - 0.2.4
* [opusscript](https://www.npmjs.com/package/opusscript) - 0.0.1
* [request](https://www.npmjs.com/package/request) - 2.69.0
* [youtube-dl](https://www.npmjs.com/package/youtube-dl) - 1.11.1
* [ytdl-core](https://www.npmjs.com/package/ytdl-core) - 0.7.19
* [electron](https://www.npmjs.com/package/electron) - 1.4.15

## Commands
__!price *$SYMBOL*__ - retrieve latest price info on a stock

__!*$SYMBOL*__ - retrieve an overview of a stock

__!chart *$SYMBOL* [--*CANDLE_SIZE*]__ - display chart for a stock; optional candle sizes are "3m": 3-minute, "5m": 5-minute, "15m": 15-minute, "d": daily, "w": weekly, "m": monthly; e.g. __!chart $MSFT --w

__!exthours *$SYMBOL*__ - retrieve premarket/after hours price info on a stock where available

__!nexteps *$SYMBOL*__ - retrieve the next earnings date for a stock

__!nextdiv *$SYMBOL*__ - retrieve the next dividend date for a stock

__!bio *$SYMBOL*__ - retrieve a short profile bio about a stock

__!findticker *companyName*__ - lookup the ticker for a company

__!define *term*__ - retrieve definition of a financial term

__!pattern *patternName*__ - display image example of a specified pattern

__!historicalreturns__ - quick reference of annualized S&P 500 returns

__!map [-t *TYPE*]__ - display the Finviz daily heatmap; optional types are "sp" (S&P 500), "world", "all", and "etf"; e.g. __!map -t etf

__!wiki__ - receive URL of the /r/stocks wiki

__!movies__ - receive a list of great finance movies/documentaries

__!song *YouTubeURLorCode*__ - plays the specified song in the voice channel

Replace $ with / for futures or . for currencies.