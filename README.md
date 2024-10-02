# Translator App - GPT-4o

## Description
This is a simple translator application built using Python, Streamlit, and LangChain. It leverages the power of GPT-4o to provide accurate translations between multiple languages.

## Features
- Translate between multiple languages including English, French, German, Latin, Spanish, Hindi, and Tamil
- User-friendly interface built with Streamlit
- Powered by GPT-4o for high-quality translations

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/arunphilip03/translator-app-gpt4o.git
   cd translator-app-gpt4o
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Open the `config.json` file in the project root
   - Add your OpenAI API key to the file:
     ```json
     {
       "OPENAI_API_KEY": "your-api-key-here"
     }
     ```

## Usage

Run the Streamlit app:
```
streamlit run src/main.py
```

Then, open your web browser and navigate to the provided local URL (usually http://localhost:8501).

## How it works
1. Select the input and output languages
2. Enter the text you want to translate
3. Click the "Translate" button
4. View the translated text

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License
[MIT](https://choosealicense.com/licenses/mit/)
