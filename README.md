# discoreDB

discoreDB is a NoSQL database system built on top of the Discord API. It allows users to store and retrieve data in text format within Discord chat, providing a lightweight alternative to traditional database systems.

## Features

- Store structured data in Discord chat using text format.
- CRUD (Create, Read, Update, Delete) operations supported through Discord bot commands.
- Utilizes JSON format for data representation, ensuring easy parsing and human readability.

## Getting Started

To get started with discoreDB, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/discoreDB.git
    ```

2. Install dependencies:

    ```bash
    # If using npm
    npm install

    # If using yarn
    yarn install
    ```

3. Set up a Discord bot and obtain your bot token. You can follow the Discord API documentation to create a bot and obtain its token.

4. Configure the bot token in the `.env` file:

    ```plaintext
    DISCORD_TOKEN=your-bot-token
    ```

5. Run the bot:

    ```bash
    # If using npm
    npm start

    # If using yarn
    yarn start
    ```

6. Once the bot is running, you can interact with it using Discord chat commands.

## Commands

discoreDB currently supports the following commands: (more on the way)

- `!insert <data>`: Insert data into the database.
- `!find <query>`: Find data matching the specified query.
- `!update <query> <new-data>`: Update existing data in the database.
- `!delete <query>`: Delete data from the database.

## Example Usage

Here are some example commands and their usage:

- Insert data: `!insert {"name": "John", "age": 30}`
- Find data: `!find {"name": "John"}`
- Update data: `!update {"name": "John"} {"age": 35}`
- Delete data: `!delete {"name": "John"}`

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Author

This project is authored and maintained by HawkdotDev.
