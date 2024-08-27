

# Dynamic Website Chatting with LangChain

This project allows users to dynamically chat with any website by providing a URL. The model retrieves all information from the specified website, embeds the content, stores it in a vector database, and uses LangChain to retrieve the most relevant data in response to user queries.

## Features

- **Dynamic Website Interaction:** Users can provide any website URL for interaction.
- **Content Embedding:** The model processes the website content, embeds it, and stores it in a vector database.
- **Relevant Data Retrieval:** Uses LangChain to deliver the most relevant information according to user queries.
- **Easy Setup and Usage:** Simple configuration steps for getting the project running locally.

## Setup Instructions

Follow these steps to set up the project locally:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Priteshverma123/DYNAMIC-CHAT-WITH-WEBSITE.git
    cd DYNAMIC-CHAT-WITH-WEBSITE
    ```

2. **Create a `.env` File:**

    In the root directory of your project, create a `.env` file and add your OpenAI API key:

    ```
    OPENAI_API_KEY=your_openai_api_key
    ```

3. **Install Dependencies:**

    Make sure you have Python installed. Then, install the required packages using `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:**

    Once everything is set up, you can start the application by running:

    ```bash
    python app.py
    ```

5. **Using the Application:**

    After running the app, you can interact with the interface by providing a website URL and start querying information from it dynamically.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


