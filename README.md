# NLP bot with Dispatch
A friendly chat bot built with Microsoft Bot Framework and his NLU LUIS and QnAMaker 

This bot that relies on multiple [LUIS.ai](https://www.luis.ai) and [QnAMaker.ai](https://qnamaker.ai) models for natural language processing (NLP).

## Prerequisites
- [Node.js][4] version 8.5 or higher
    ```bash
    # determine node version
    node --version
    ```
- [Dispatch CLI](https://github.com/Microsoft/botbuilder-tools/tree/master/packages/Dispatch)
    ```bash
    # install the dispatch CLI tool
    npm install -g botdispatch
    ```

# To try this sample
- Clone the repository
    ```bash
    git clone https://github.com/ledrui/nlp-bot.git
    ```
- In a terminal, navigate to `nlp-bot.git`
    ```bash
    cd nlp-bot.git
    ```
- Install modules
    ```bash
    npm install
    ```
- Start the bot
    ```bash
    npm start
    ```
- Try it with one of these queries
  
    ```bash
    What is your name ?
    Where do you live in ?
    ```

# Testing the bot using Bot Framework Emulator **v4**
[Microsoft Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the Bot Framework emulator from [here](https://github.com/microsoft/botframework-emulator/releases)

## Connect to bot using Bot Framework Emulator **v4**
- Launch Bot Framework Emulator
- File -> Open Bot Configuration and navigate to `nlp-bot` folder
- Select `nlp-bot.bot` file
