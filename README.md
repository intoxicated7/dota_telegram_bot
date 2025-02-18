
  

# Dota Telegram Bot

  

  

## Installation

  

  

To get started with this project, follow the steps below to clone the repository and set up the application using Docker.

  

  

### Step 1: Clone the Repository

  
First, clone the repository to your local machine using the following command:
#### `https://github.com/OmniscientDesiderator/dota_telegram_bot.git`

  

  

### Step 2: Configure Your Tokens

 Navigate to the directory and open the `.env` file. You will need to insert your **Telegram bot** and **Steam** token into this file. Look for the line that specifies the token and replace it with your own:
  
  

#### Change into the project directory:

  

  

### Step 3: Build and Run the Application

  

#### `docker-compose up --build -d`

  

  

## Used libraries and API

  

- [Aiogram](https://aiogram.dev/)

  

- [OpenDota API](https://docs.opendota.com/)

- [Steam API](https://steamcommunity.com/dev)

  

  

## Bot commands

  

-  **/start** - To get information about the bot

  

-  **/help** - Shows existing bot commands

  

-  **/show_player** - Displaying a player by Steam ID (account information, latest matches and heroes)

  

-  **/show_match** - Display match by number (stats, players, bans and scores)