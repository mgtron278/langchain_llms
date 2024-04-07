# Langchain with OpenAI API

This project demonstrates how to integrate the Langchain and OpenAI APIs to create a conversational assistant using Streamlit.

## Overview

Langchain is a library designed for creating conversational AI systems. This demo showcases a simple application using Langchain along with the powerful GPT-3.5 model from OpenAI.

## Setup

To run this demo locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Install Dependencies:**

   Make sure you have Python installed. Then, install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables:**

   Create a `.env` file in the project directory and add your API keys:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   LANGCHAIN_API_KEY=your_langchain_api_key
   ```

4. **Run the Application:**

   Start the Streamlit app by running:

   ```bash
   streamlit run app.py
   ```

## Usage

Once the application is running, you can interact with the demo:

1. Enter a question in the text input field.
2. Click on the "Search the topic you want" button.

The application will use Langchain and OpenAI's GPT-3.5 model to generate a response based on your input.

## Langsmith and tracing

- why did  we use ( os.environ["LANGCHAIN_TRACING_V2"]="true" )

LangSmith is a development tool that bridges the gap between your application and large language models (LLMs) like GPT-3. It acts as a middleman, streamlining how you send prompts to the LLM and receive its responses. But LangSmith goes beyond just interaction.

Here's where tracing comes in. Tracing, enabled through the code you provided,  is like watching a behind-the-scenes documentary of your application's communication with the LLM. It captures details like the prompts sent, the LLM's responses, and other data. This information is invaluable for debugging issues, understanding how your application leverages the LLM, and optimizing its performance.

## About

This project is a part of integrating Langchain with OpenAI's powerful language model for creating conversational interfaces.

## Contributing

Contributions are welcome! If you have suggestions or want to report issues, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
