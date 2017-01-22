# rstocksbot
Discord chat bot based on [discord.js](https://github.com/hydrabolt/discord.js) for the [/r/stocks](https://www.reddit.com/r/stocks/) subreddit [chat server](http://www.r-stocks.com/chat/).

## How to use

### Linux
To install, you can use NPM:

`npm install rstocksbot`

Or you can clone the git repository:

```
git clone https://github.com/GoldenChrysus/rstocksbot.git
cd rstocksbot
npm install
```

Navigate to installation directory if you aren't already there (if you didn't use git clone):

`cd ~/node_modules/rstocksbot`

Start the package:

`npm start`

## Dependencies 
* [discord.js](https://www.npmjs.com/package/discord.js) - **10.0.1** - used for interfacing with Discord
* [fs](https://www.npmjs.com/package/fs) - **0.0.1-security** - used to write YouTube audio to the local disk for playback
* [node-opus](https://www.npmjs.com/package/node-opus) - **0.2.4** - audio codec for voice
* [opusscript](https://www.npmjs.com/package/opusscript) - **0.0.1** - audio codec for voice
* [request](https://www.npmjs.com/package/request) - **2.69.0** - used to GET/POST to the server handlers and receive the response
* [youtube-dl](https://www.npmjs.com/package/youtube-dl) - **1.11.1** - deprecated
* [ytdl-core](https://www.npmjs.com/package/ytdl-core) - **0.7.19** - used to download YouTube video info and audio
* [electron](https://www.npmjs.com/package/electron) - **1.4.15** - used to pull javascript-generated content from websites

## Commands
**!price** $SYMBOL - retrieve latest price info on a stock

__!_$SYMBOL___ - retrieve an overview of a stock

__!chart _$SYMBOL_ [--_CANDLE_SIZE_]__ - display chart for a stock; optional candle sizes are "3m": 3-minute, "5m": 5-minute, "15m": 15-minute, "d": daily, "w": weekly, "m": monthly; e.g. __!chart $MSFT --w

__!exthours _$SYMBOL___ - retrieve premarket/after hours price info on a stock where available

__!nexteps _$SYMBOL___ - retrieve the next earnings date for a stock

__!nextdiv _$SYMBOL___ - retrieve the next dividend date for a stock

__!bio _$SYMBOL___ - retrieve a short profile bio about a stock

__!findticker _COMPANY_NAME___ - lookup the ticker for a company

__!define _TERM___ - retrieve definition of a financial term

__!pattern _PATTERN_NAME___ - display image example of a specified pattern

__!historicalreturns__ - quick reference of annualized S&P 500 returns

__!map [-t _TYPE_]__ - display the Finviz daily heatmap; optional types are "sp" (S&P 500), "world", "all", and "etf"; e.g. __!map -t etf

__!wiki__ - receive URL of the /r/stocks wiki

__!movies__ - receive a list of great finance movies/documentaries

__!song _YOUTUBE_URL_OR_CODE___ - plays the specified song in the voice channel

Replace $ with / for futures or . for currencies.