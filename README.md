# MARK-I

MARK-I is a Node.js-based command bot project. It provides a modular structure for implementing various commands, making it easy to extend and maintain. This project is suitable for chat platforms or automation tasks where custom commands are required.

## Project Structure

```
index.js
package.json
Procfile
commands/
  ban.js
  bye.js
  ctc.js
  hello.js
  kick.js
  meme.js
  mute.js
```

- **index.js**: Main entry point for the bot.
- **package.json**: Project metadata and dependencies.
- **Procfile**: Used for deployment (e.g., Heroku).
- **commands/**: Directory containing individual command modules.

## Features

- Modular command system
- Easy to add new commands
- Supports various chat commands (ban, kick, mute, meme, etc.)
- Ready for deployment with Procfile

## Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd MARK-I
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the bot:
   ```bash
   node index.js
   ```
2. The bot will listen for commands and respond accordingly.

## Adding New Commands

1. Create a new file in the `commands/` directory (e.g., `greet.js`).
2. Export a function that handles the command logic.
3. Update `index.js` to include the new command if required.

## Deployment

- The project includes a `Procfile` for easy deployment to platforms like Heroku.
- Ensure all environment variables are set as needed.

## Example Commands

- `ban`: Ban a user from the chat.
- `kick`: Kick a user from the chat.
- `mute`: Mute a user.
- `meme`: Send a meme.
- `hello`: Greet users.
- `bye`: Say goodbye.
- `ctc`: Custom command.

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For questions or support, please open an issue in the repository.
