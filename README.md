# rstocksbot
Chat bot based on [discord.js](https://github.com/hydrabolt/discord.js) for the [/r/stocks](https://www.reddit.com/r/stocks/) subreddit [chat server](http://www.r-stocks.com/chat/).

## Commandss
!price $SYMBOL - retrieve latest price info on a stock
!$SYMBOL - retrieve an overview of a stock
!chart $SYMBOL [--CANDLE_SIZE] - display chart for a stock; optional candle sizes are "3m": 3-minute, "5m": 5-minute, "15m": 15-minute, "d": daily, "w": weekly, "m": monthly; e.g. !chart $MSFT --w
!exthours $SYMBOL - retrieve premarket/after hours price info on a stock where available
!nexteps $SYMBOL - retrieve the next earnings date for a stock
!nextdiv $SYMBOL - retrieve the next dividend date for a stock
!bio $SYMBOL - retrieve a short profile bio about a stock
!findticker companyName - lookup the ticker for a company
!define term - retrieve definition of a financial term
!pattern patternName - display image example of a specified pattern
!historicalreturns - quick reference of annualized S&P 500 returns
!map [-t TYPE] - display the Finviz daily heatmap; optional types are "sp" (S&P 500), "world", "all", and "etf"; e.g. !map -t etf
!wiki - receive URL of the /r/stocks wiki
!movies - receive a list of great finance movies/documentaries
!song YouTubeURLorCode - plays the specified song in the voice channel

Replace $ with / for futures or . for currencies.