# Telegram Bot with Mistral AI Integration

## 🤖 Bot Description

This Telegram bot leverages the power of Mistral AI to perform various tasks:
- Answering questions with deep context
- Generating text on demand
- Generating images
- Analyzing images (text in photos)
- Processing LaTeX expressions
- Intelligent information analysis

The bot is powered by the Mistral AI API, ensuring high quality and accuracy of responses.

## ⚙️ Installation and Setup

1. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

2. **Activate the environment**:
   - For Windows:
     ```bash
     venv\Scripts\activate
     ```
   - For Linux/MacOS:
     ```bash
     source venv/bin/activate
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Create a `.env` file in the project root** with the following variables:
   ```
   DB_PATH=your_database_path.db
   ADMIN_ID=your_telegram_id
   TG_TOKEN=your_telegram_bot_token
   MISTRAL_API_KEY=your_mistral_api_key
   ```

5. **Run the bot**:
   ```bash
   python main.py
   ```
