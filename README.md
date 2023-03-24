# **Bean#331 Discord Bot**

A Discord bot that uses the OpenAI API to interact with users in a friendly manner.

## **Table of Contents**

- **[Getting Started](https://chat.openai.com/chat?model=gpt-4#getting-started)**
- **[Prerequisites](https://chat.openai.com/chat?model=gpt-4#prerequisites)**
- **[Installation](https://chat.openai.com/chat?model=gpt-4#installation)**
- **[Usage](https://chat.openai.com/chat?model=gpt-4#usage)**
- **[Acknowledgements](https://chat.openai.com/chat?model=gpt-4#acknowledgements)**

## **Getting Started**

These instructions will guide you on how to set up and use the Friendly Discord Bot in your server.

## **Prerequisites**

Before starting the installation process, make sure you have the following:

- Node.js (v16 or higher)
- npm (v7 or higher)
- An OpenAI API key
- A Discord bot token

## **Installation**

1. Clone this repository to your local machine:
    
    ```
    git clone https://github.com/eren-olympic/discord-gpt3.5.git
    cd friendly-discord-bot
    ```
    
2. Install the required dependencies:
    
    ```
    npm install
    ```
    
3. Create a **`.env`** file in the root folder of the project, and fill it with your API key and Discord bot token:
    
    ```
    API_KEY=<your_openai_api_key>
    TOKEN=<your_discord_bot_token>
    CHANNEL_ID=<your_discord_channel_id>
    ```
    
4. Run the bot:
    
    ```
    node index.js
    ```
    

## **Usage**

1. Invite the bot to your Discord server.
2. In the specified channel (defined by **`CHANNEL_ID`** in the **`.env`** file), start chatting with the bot by sending messages. The bot will respond based on the context and content of the messages.

## **Acknowledgements**

- Special thanks to **[Under Ctrl](https://www.youtube.com/watch?v=CB76_GDrPsE)** for their valuable resources, which helped to build this project.
- This project utilizes the **OpenAI API** to generate friendly and context-aware responses. Learn more about OpenAI at **[https://www.openai.com/](https://www.openai.com/)**.