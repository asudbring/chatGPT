# ChatGPT Discord Bot

A Discord bot that uses OpenAI's GPT-3.5 to generate messages based on inputs from users in the Discord server. This version of the bot is associated with a channel in your Discord server, and will only respond to messages in that channel.

The bot is written in Node.js, and uses the [discord.js](https://discord.js.org/#/) library to interact with Discord. The bot uses the [OpenAI API](https://beta.openai.com/) to generate messages.

## Requirements

* OpenAI account and API key
* Discord server
* Node.js for local installation
* (Optional) Docker for containerized installation

## Installation

The .env file is used to store the OpenAI API key and Discord bot token. The .env file has blank values that need to be filled in with your own API key and token. To install the bot into a channel in your Discord server, obtain the channel ID in developer mode in Discord, and add it to the .env file.

### Local

1. Clone this repository to your local machine.

2. Change to the discord-bot directory.

3. Run bot locally with `node index.js`.

### Docker

1. Clone this repository to your local machine.

2. Change to the discord-bot directory.

3. Build the Docker image with `docker build -t chatgpt-discord-bot .`


### Acknowledgements

* The Clever Programmer Discord bot tutorial on YouTube. [I Built a Discord Bot with ChatGPT](https://www.youtube.com/watch?v=95_e2YoZ5SA).
* [OpenAI](https://beta.openai.com/) for the API and the GPT-3.5 model
* [Discord.js](https://discord.js.org/#/) for the Discord library
* [Discord.js Guide](https://discordjs.guide/) for the Discord bot tutorial
* [Discord.js Guide: Deploying your bot](https://discordjs.guide/deploying-your-bot/) for the Docker tutorial
