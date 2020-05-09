# OdesliBot based on TikBot (not done yet)

![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)
![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/fronbasal/tikbot)
![GitHub](https://img.shields.io/github/license/fronbasal/tikbot)


See TikTok videos in your Telegram chats without hassle!
This bot will upload all posted TikTok links as a video with stats and caption.

### [**Add this bot to your group chat or text it now!**](https://t.me/tiktokurlbot)


## Deployment

If you want to deploy your own instance of TikBot follow these instructions.

Firstly you need to generate a new bot token by following [Telegrams instructions](https://core.telegram.org/bots#3-how-do-i-create-a-bot).

This application has a publically accessible [Docker image](https://gitlab.com/fronbasal/tikbot/container_registry).

To deploy TikBot to your server you may use the provided `docker-compose.yml` configuration file.

Add your Telegram token to the `.env` file (or set it explicitly while runnning the bot) and boot it with `docker-compose`.
