# Language Translation Tool

## Overview
The Language Translation Tool is a Python-based application that utilizes the DeepL API to provide real-time translation of text between multiple languages. The application features a user-friendly graphical interface built with Tkinter, allowing users to easily input text, select source and target languages, and view the translated output.

## Features
- **Multi-line Text Input**: Users can enter text for translation in a dedicated text box.
- **Language Selection**: Supports a variety of languages including English, German, French, Spanish, Italian, Polish, Russian, Portuguese, Dutch, Arabic, Chinese, Japanese, and Hindi.
- **Real-time Translation**: Translates text using the DeepL API and displays the result in a read-only output box.
- **Error Handling**: Provides meaningful error messages for input validation and API connection issues.

## Requirements
- Python 3.x
- Tkinter (usually included with Python installations)
- Requests library (install via pip if not already installed)

```bash
pip install requests
```

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ammaremad/language-translation-tool.git
   cd language-translation-tool
   ```

2. **Set Up Your DeepL API Key**:
   Replace the placeholder API key in the `deepl_translate` function with your own DeepL API key.

   ```python
   api_key = "YOUR_DEEPL_API_KEY"
   ```

3. **Run the Application**:
   Execute the script to launch the GUI.
   ```bash
   python translator.py
   ```

## Usage
- Enter the text you wish to translate in the input box.
- Select the source language from the dropdown menu.
- Select the target language from the dropdown menu.
- Click the "Translate" button to see the translated text in the output box.

## Example
1. Input: "Hello, how are you?"
2. Source Language: English (EN)
3. Target Language: Spanish (ES)
4. Output: "Hola, ¿cómo estás?"

## Error Handling
- If no text is entered, an error message will prompt the user to input text.
- If there are issues with the API request, an error message will indicate the problem.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.


## Acknowledgments
- [DeepL API](https://www.deepl.com/pro-api) for providing translation services.
- [Tkinter](https://docs.python.org/3/library/tkinter.html) for the GUI framework.
- [Requests](https://docs.python-requests.org/en/master/) for handling HTTP requests.

---

Feel free to customize this README to better fit your project specifics or personal preferences!
