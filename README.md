# Codestral Mistral AI Auto-Complete

This project is a Streamlit application that utilizes the Codestral API from Mistral AI to provide code suggestions and auto-complete functionality. The app allows users to ask coding-related questions and receive a comprehensive response, including a description, imports, code snippets, and sample input/output.

## Features

- **Interactive UI**: The application features a user-friendly interface built with Streamlit, allowing users to easily input their coding questions.
- **Code Suggestions**: The app leverages the Codestral API to generate code solutions based on the user's input.
- **Structured Responses**: The responses are structured in a JSON format, providing a clear separation of different components like description, imports, code, and sample input/output.
- **Syntax Highlighting**: The code snippets are displayed with syntax highlighting for better readability.
- **Sample Input/Output**: The app includes sample input and output examples to help users understand the functionality of the suggested code.

## Installation

1. Clone the repository:

- git clone https://github.com/tushark01/Codestral-Mistral-AI.git

2. Navigate to the project directory:
  
- cd Codestral-Mistral-AI

3. pip install -r requirements.txt

4. Create a `.env` file in the project root directory and add your Mistral API key:
MISTRAL_API_KEY=your_api_key_here

Replace `your_api_key_here` with your actual Mistral API key.

## Usage

1. Run the Streamlit application:
2. The application will open in your default web browser.
3. Enter your coding question in the input field and press Enter.
4. The app will fetch the response from the Codestral API and display the structured output, including the description, imports, code, and sample input/output.

## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or new features to add, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Streamlit](https://streamlit.io/) - The Python library used for building the interactive UI.
- [Codestral API](https://www.mistral.ai/codestral-ai/) - The powerful AI model from Mistral AI that powers the code suggestions.
