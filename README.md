# SONM Community Telegram Bot

## Installation

First, provide your Telegram Bot Token (given by @BotFather) into a terminal window
```
TELEGRAM_BOT_TOKEN=123456789:ABCDEFhijklmn123OPQRSTUvw4567xyz890
```

Then, run the following commands
```
cp config/telegram.json.template config/telegram.json
sed -i "s/ADD_BOT_TOKEN_HERE/$TELEGRAM_BOT_TOKEN/g" config/telegram.json
```

Now you have your Bot Token in place. Next, it is time to install Python dependencies.
(if you don't yet have pipenv, please install it)
```
pipenv install
```

Then, simply start the bot
```
python3 start.py
```