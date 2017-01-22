# rstocksbot
Chat bot based on [discord.js](https://github.com/hydrabolt/discord.js) for the [/r/stocks](https://www.reddit.com/r/stocks/) subreddit [chat server](http://www.r-stocks.com/chat/).

## Commands
__!price _$SYMBOL___ - retrieve latest price info on a stock

__!_$SYMBOL___ - retrieve an overview of a stock

__!chart _$SYMBOL_ [--_CANDLE_SIZE_]__ - display chart for a stock; optional candle sizes are "3m": 3-minute, "5m": 5-minute, "15m": 15-minute, "d": daily, "w": weekly, "m": monthly; e.g. __!chart $MSFT --w

__!exthours _$SYMBOL___ - retrieve premarket/after hours price info on a stock where available

__!nexteps _$SYMBOL___ - retrieve the next earnings date for a stock

__!nextdiv _$SYMBOL___ - retrieve the next dividend date for a stock

__!bio _$SYMBOL___ - retrieve a short profile bio about a stock

__!findticker _companyName___ - lookup the ticker for a company

__!define _term___ - retrieve definition of a financial term

__!pattern _patternName___ - display image example of a specified pattern

__!historicalreturns__ - quick reference of annualized S&P 500 returns

__!map [-t _TYPE_]__ - display the Finviz daily heatmap; optional types are "sp" (S&P 500), "world", "all", and "etf"; e.g. __!map -t etf

__!wiki__ - receive URL of the /r/stocks wiki

__!movies__ - receive a list of great finance movies/documentaries

__!song _YouTubeURLorCode___ - plays the specified song in the voice channel

Replace $ with / for futures or . for currencies.