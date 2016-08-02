This is telegram XO game bot

base on php

How to setup:

First use @BotFather to create new bot

after you create new bot in botfather you get a token for your bot

enable inline mode with /setinline in botfather bot

insert your token to XO_Game.php => define('BOT_TOKEN', 'Your Token Here');

now you need setwebhook for your bot
for webhook you need https url

you can do it in your browser with this code:
Exmple: https://example.com/mybot/XO_Game.php
https://api.telegram.org/bot<botToken>/setWebhook?url=Your https url to php file

replace <botToken> with your token geted from BotFather bot

now your bot is ready