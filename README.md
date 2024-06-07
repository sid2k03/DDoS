# Telegram Bot for DDoS Attack Management

A Python Telegram bot for managing DDoS attacks on servers. This bot allows authorized users to initiate attacks on specified targets with customizable parameters.

## Features

- Add and remove authorized users
- Clear attack logs
- View authorized users
- View recent attack logs
- Initiate DDoS attacks with custom parameters
- Broadcast messages to all users

## Setup

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Insert your Telegram bot token in the script (`bot = telebot.TeleBot('YOUR_TOKEN_HERE')`).
4. Run the script (`python3 bot.py`).

## Commands

- `/add <userID>`: Add a user to the list of authorized users.
- `/remove <userID>`: Remove a user from the list of authorized users.
- `/allusers`: View the list of authorized users.
- `/logs`: View recent attack logs.
- `/clearlogs`: Clear all attack logs.
- `/broadcast <message>`: Broadcast a message to all users.
- `/bgmi <target> <port> <time>`: Initiate a DDoS attack with specified parameters.
- `/help`: View available commands and usage.

## Usage

1. Add authorized users using the `/add` command.
2. Start initiating DDoS attacks using the `/bgmi` command.
3. View logs using the `/logs` command.
4. Broadcast messages to all users using the `/broadcast` command.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.
