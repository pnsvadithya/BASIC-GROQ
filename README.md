THIS IS A BASIC GROQ APP DEVELOPED WITH STREAMLIT.

# Groq Chat App

## Features

- **Model Selection**: Users can select between the following models to tailor conversations based on their capabilities:
  - `mixtral-8x7b-32768`
  - `llama2-70b-4096`
  - `Gemma-7b-it`
  - `llama3-70b-8192`
  - `lama3-8b-8192`

- **Chat History**: The app maintains a session-based chat history, enabling continuous conversation flow during the session.

- **Dynamic Response Generation**: Utilizes a generator function to stream responses from the Groq API, ensuring a seamless chat experience.

- **Error Handling**: Implements robust `try-except` blocks to gracefully handle potential errors during API calls.

## Requirements

- **Python**: Version 3.7 or higher
- **Dependencies**:
  - Streamlit
  - Groq Python SDK

## Setup and Installation

1. **Install Dependencies**:

   ```bash
   pip install streamlit groq
   ```

2. **Set Up Groq API Key**:

   Ensure you have an API key from Groq. Store the key securely using Streamlit's secrets management:

   ```toml
   # .streamlit/secrets.toml
   GROQ_API_KEY="your_api_key_here"
   ```

3. **Run the App**:

   Navigate to the app's directory and run:

   ```bash
   streamlit run streamlit_app.py
   ```

## Usage

1. Launch the app to be greeted with a title and a model selection dropdown.
2. Choose your preferred model.
3. Interact with the chat interface by entering prompts.
4. View the AI's responses and continue the conversation seamlessly.

## Customization

- **Add New Models**: Extend the app to include additional language models as Groq adds more options.
- **Enhance UI**: Modify the user interface to better suit your needs.
- **Extend Functionality**: Incorporate other interactions with the Groq API for a richer experience.

## Contributing

Contributions are welcome! To enhance the app, fix bugs, or improve documentation:

1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

Feel free to suggest improvements or open issues for any bugs encountered. Happy coding!


