Here's the `README.md` content formatted as Markdown:

```markdown
# Medical Chatbot

This project is a Telegram-based Medical Chatbot designed to provide users with general health advice. The bot uses the Groq API for natural language processing and ensures responses are concise and healthcare-focused. If users ask about anything unrelated to healthcare, the bot responds with "I am your healthcare assistant."

## Features

- Short and precise health advice.
- Directly addresses user problems in 2-3 lines.
- Offers detailed explanations upon user request.
- Recommends consulting a doctor for serious health issues.
- Ensures all non-healthcare-related queries are redirected with a default response.

## Requirements

- Python 3.10
- Telegram Bot Token
- Groq API Key

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/medical-chatbot.git
   cd medical-chatbot
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python3.10 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment variables:

   - `TELEGRAM_BOT_TOKEN`: Your Telegram bot token.
   - `GROQ_API_KEY`: Your Groq API key.

## Usage

1. Start the bot by running:

   ```bash
   python chatbot.py
   ```

2. Interact with the bot on Telegram by searching for your bot's username and starting a conversation.

3. Use the `/start` command to initialize the chatbot.

## System Prompt

The chatbot operates based on the following system prompt:

> "You are a medical assistant chatbot. Provide short and precise health advice based on user input. Address the user's problem directly in 2-3 lines. If they want more details, provide a clear explanation. Always recommend consulting a doctor for serious issues and clarify that you are not a substitute for professional medical advice. If the user asks about anything unrelated to healthcare, respond with 'I am your healthcare assistant.'"

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgments

- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Groq API](https://groq.com)
```
