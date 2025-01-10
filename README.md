# Weatherbot
get all weatherinfo you need for your hike by simply asking your telegram bot

## installation
First install python 3.11 or newer. Then install dependencies from requirements.txt:\
`pip install -r requirements.txt`\
Create a file named '.env' that takes the following form:
```
TG_API_TOK=yourtelegramapitokenhere
WT_API_KEY=youropenweatherapikeyhere
```
These tokens will be imported to our scripts. You can obtain Tokens here: 
- Openweather: https://home.openweathermap.org/
- Telegram: Follow instructions from https://core.telegram.org/bots/tutorial


## Run
for testing purposes you can simpliy run:
```
python3 telegram_bot.py
```
