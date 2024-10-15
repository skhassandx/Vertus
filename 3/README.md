> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">]

# Use Node.Js 18 or later

## Functionality

| Functional                            | Supported |
| ------------------------------------- | :-------: |
| Claiming mining reward                |    ✅     |
| Upgrades                              |    ✅     |
| Multithreading                        |    ✅     |
| Data caching                          |    ✅     |
| Creating sessions with qrcode         |    ✅     |
| Using a session/query_id              |    ✅     |
| Binding a proxy to a session/query_id |    ✅     |
| Random sleep time between clicks      |    ✅     |

### [How to add query id] Video Coming

## [Settings](https://github.com/skhassandx/Vertus)

| Settings                      | Description                                                               |
| ----------------------------- | ------------------------------------------------------------------------- |
| **API_ID / API_HASH**         | Platform data from which to launch a Telegram session (stock - Android)   |
| **AUTO_UPDATE_FARM**          | Whether the bot should upgrade farm (True / False)                        |
| **AUTO_UPDATE_PIGGY_BANK**    | Whether the bot should upgrade piggy farm (True / False)                  |
| **AUTO_UPDATE_SETTLEMENT**    | Whether the bot should upgrade settlement (True / False)                  |
| **AUTO_BUY_AND_UPDATE_CARDS** | Whether the bot should upgrade cards (True / False)                       |
| **BALANCE_TO_SAVE**           | The minimum balance the bot should stop upgrades                          |
| **SLEEP_BETWEEN_REQUESTS**    | Delay between taps in seconds (eg. 70)                                    |
| **USE_PROXY_FROM_FILE**       | Whether to use proxy from the `bot/config/proxies.js` file (True / False) |
| **USE_QUERY_ID**              | Whether to query_id instead of sessions (True / False)                    |

## Installation

You can download [**Repository**](https://github.com/skhassandx/Vertus) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/skhassandx/Vertus.git
~ >>> cd Vertus
~ >>> cd 2

#Linux and MocOS
~/Vertus/3 >>> chmod +x check_node.sh
~/Vertus/3 >>> ./check_node.sh

OR

~/Vertus/3 >>> npm install
~/Vertus/3 >>> cp .env-example .env
~/Vertus/3 >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/Vertus/3 >>> node index.js

#Windows
1. Double click on INSTALL.bat in Vertus/3 directory to install the dependencies
2. Double click on START.bat in Vertus/3 directory to start the bot

OR

~/Vertus/3 >>> npm install
~/Vertus/3 >>> cp .env-example .env
~/Vertus/3 >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/Vertus/3 >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/Vertus/3 >>> node index.js --action=1

OR

~/Vertus/3 >>> node index.js --action=2

#1 - Create session
#2 - Run clicker
```
