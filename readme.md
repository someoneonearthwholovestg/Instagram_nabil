# Instagram unfollowers bot
This simple bot controls your followers and followings in Instagram.
If it finds out that someone does not follow you back, it tells you. 
You can subscribe to notifications, so it will check your unfollowers automatically once a day.

### Languages
* English
* Russian

## Install with docker-compose
To run this you must have an Instagram account for bot and telegram bot.

You need to set these env-variables:
* `VOLUME_HOST_PATH` - where to store sqlite database
* `TELEGRAM_BOT_TOKEN` - get it from @botfather in telegram
* `INSTAGRAM_USERNAME` - username of Instagram account your bot will use
* `INSTAGRAM_PASSWORD` - password of Instagram account your bot will use

Set variables and go:

`> docker-compose up -d`

Feel free to contribute!