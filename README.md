# Telegram-gpt-bot
A Telegram bot that utilizes OpenAI's ChatGPT language model to generate responses to messages

## Requirements
- Node.js v18 or higher
- A OpenAI API key
- A Telegram Bot API key

## Getting started
1. Install dependencies: `npm install`
2. Modify the file at `config/settings.env` with your OpenAI API key and Telegram Bot API key.
3. Start the app: `node src/index.js`

## Using the bot
To use the bot, simply start a conversation with it in Telegram and send it messages. If you want to start a new GPT3 instance, just send the bot the message `/reset`.

## Commands

- `/help` - Displays a help message
- `/reset` - Resets the GPT3 instance
- `/retry` - Retries the last message sent to the bot

## Made using

- [chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api) - by transitive-bullshit
- [node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api)
