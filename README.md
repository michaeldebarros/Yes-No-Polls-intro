# Yes-No-Polls-intro

![Yes No Polls Logo](https://github.com/michaeldebarros/ynp/blob/master/public/yes_no_logo.png)

Yes No Polls is a simple Telegram Bot that makes ... you guessed it!

## Usage

The idea behind Yes No Polls is to make polls in group chats.  Simply add the bot to your group and send /newpoll in order to makethe question. There is a [Youtube](https://www.youtube.com/watch?v=KJR__T7800w) video explainaing the usage.


The results will be shown in a link at www.yesnopolls.com.

## Built With

Yes No Polls Bot is a Node.js app, using the [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api).  The results are served by Express.js, with an EJS template.  There is a dohnut chart written in D3.js.

Hosting is done an an Amazon Ec2-micro instance (those ones thar are free for one year), managed by PM2.js.  Continuouse integration is achieved via a git hook.

Enjoy!
