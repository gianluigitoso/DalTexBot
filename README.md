# DalTexBot
I Love the [LaTeX2IMGbot] (https://github.com/analca3/LaTeX2IMGbot), and this is fork is a testing ground for my personal Telegram bot: [@DalTexBot] (https://telegram.me/DalTexBot)

----------

**Original ReadMe.md**:

# LaTeX2IMGbot

Telegram Bot that receive an LaTeX equation and uses LaTeX2IMG to send a sticker.

This is developed with [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) using the listener mechanism. My bot is @LaTeX2IMGbot but you can create your own one =).

## Required packages

You need to install previously **libwebp**, **Pillow** and **pyTelegramBotAPI**. It's very important you get libwebp BEFORE pillow. You can get them using your package manager or using pip.

In Archlinux
```
# pacman -S libwebp python-pillow
```

In Debian-based distros
```
# apt-get install libwebp2 libwebp-dev
```

Using pip
```
# pip install Pillow
# pip install pyTelegramBotAPI
```

## Usage

1. Create a bot with the BotFather Telegram Bot
2. Write the token in token.txt file
3. Execute the bot in your server with ``` ./bot.py ```
4. In the Telegram client you can talk with your bot or add them to groups. All messages beggining with **/latex** or @aliasofyourbot will be catched by your bot.

## Examples

![Examples from my mobile](Ejemplos.png)

Enjoy it!
