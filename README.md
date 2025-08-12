# gif-nest
A simple Telegram bot for managing your GIFs

## Use

I have this bot in production which you can use it for free [here](https://t.me/gifnestbot).

## Run

### Docker

I have built the project as a Docker image which is now available on [Docker Hub](https://hub.docker.com/repository/docker/alirezabar/gif-nest).

In order to run the bot, you should have MongoDB installed on your OS and run the image with its environemnt variables:

- Install Docker and MongoDB on your host
- Run the docker image

```shell
sudo docker run -d --network=host --name=real-gifs -e BOT_TOKEN=<your-bot-token> -e BOT_USERNAME=<your-bot-username> -e PLACEHOLDER_GIF=<your-placeholder-gif-file-id> alirezabrtn/gif-nest:latest
```

### From Source

- Make sure you have Node.js and MongoDB installed on your machine
- Clone the repo
- Install npm dependecies
- Provide your environment variables
- Run

### This project is still under development and not ready for public use.