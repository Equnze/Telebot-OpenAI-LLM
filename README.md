# Chatbot-using-OpenAI-LLM

## Prerequisites

To follow this tutorial, you will need:

- Python 3.7 or higher
- A Telegram account and a smartphone
- An OpenAI account and an API key.


## Telegram setup:

1. search for botfather
2. /newbot
   - mybot88
   - mybot88_bot

   Now click on the url


### AIogram docs
https://docs.aiogram.dev/en/latest/

## How to run the code

1. Clone this repository or download the zip file
2. Create a virtual environment and activate it
3. Install the dependencies using `pip install -r requirements.txt`
4. Create a `.env` file in the root directory and add your OpenAI API key and Telegram BOT TOKEN as follows:

```ini
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TELEGRAM_BOT_TOKEN=xxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

5. Run `python src/my_bot.py` to start the bot
6. Open Telegram and search for your bot username
7. Start a conversation with your bot and enjoy!
