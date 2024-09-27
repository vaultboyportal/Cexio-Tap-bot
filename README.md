## Recommendation before use

# 🔥🔥 Use PYTHON 3.10 - 3.11.5 🔥🔥

## Features  
| Feature                                                     | Supported  |
|---------------------------------------------------------------|:----------------:|
| Multithreading                                                |        ✅        |
| Proxy binding to session                                      |        ✅        |
| Auto-Click coin, Claim and convert                            |        ✅        |
| Specify number of taps                                        |        ✅        |
| Auto-claim squad reward                                       |        ✅        |
| Auto-start, auto-check and auto-claim tasks                   |        ✅        |
| Auto-Buy Upgrade card                                         |        ✅        |
| Auto-REF                                                      |        ✅        |
| Support for tdata / pyrogram .session / telethon .session     |        ✅        |


## [Settings](https://github.com/vanhbakaa/Cexio-Tap-bot/blob/main/.env-example)
| Settings | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Platform data from which to run the Telegram session (default - android)                                      |
| **REF_LINK**               | auto register with your ref link (default: my ref link)                                                       |
| **AUTO_TAP**               | Automatically tapping (e.g. True) IMPORTANT please dont open app while you are running bot with this option and just turn on this option if your wifi is good |                                
| **RANDOM_TAPS_COUNT**      | How many taps will be clicked (e.g. [25, 75])                                                                 |
| **SLEEP_BETWEEN_TAPS**     | Random delay between taps (e.g. [25, 35])                                                                     |
| **AUTO_CONVERT**           | Auto convert BTC balance to coin (e.g. True)                                                                  |
| **MINIMUM_TO_CONVERT**     | Minimum BTC balance to convert (e.g. 0.1)                                                                     |
| **AUTO_BUY_UPGRADE**       | Auto upgrade the most profitable card (eg. True)                                                              |
| **AUTO_TASK**              | Auto tasks (one time) ((eg. True))                                                                            |
| **AUTO_CLAIM_SQUAD_BONUS** | Auto claim bonus from ref (one time) ((eg. False))                                                            |
| **USE_PROXY_FROM_FILE**    | Whether to use a proxy from the bot/config/proxies.txt file (True / False)                                    |


## Quick Start 📚

To install libraries and run bot - open run.bat on Windows

## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10 - 3.11.5**

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Installation
You can download the [**repository**](https://github.com/vanhbakaa/Cexio-Tap-bot) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/vaultboyportal/Cexio-Tap-bot.git
cd Cexio-Tap-bot
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/Cexio-Tap-bot >>> python3 main.py --action (1/2)
# Or
~/Cexio-Tap-bot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/Cexio-Tap-bot >>> python main.py --action (1/2)
# Or
~/Cexio-Tap-bot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```
# Support This Project

If you'd like to support the development of this project, please consider making a donation. Every little bit helps!

👉 **[Click here to view donation options](https://github.com/vanhbakaa/Donation/blob/main/README.md)** 👈

Your support allows us to keep improving the project and bring more features!

Thank you for your generosity! 🙌

### Contacts

For support or questions, you can contact me [![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/vaultboyportal)
