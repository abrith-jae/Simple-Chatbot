# Simple Chatbot with Open Source LLMs using Python and Hugging Face

## Introduction: Under the hood of a chatbot
### Intro: How does a chatbot work?
A chatbot is a computer program that takes a text input, and returns a corresponding text output.

Chatbots use a special kind of computer program called a transformer, which is like its brain. Inside this brain, there is something called a language model (LLM), which helps the chatbot understand and generate human-like responses. It deciphers many examples of human conversations it has seen prior to responding in a sensible manner.

Transformers and LLMs work together within a chatbot to enable conversation. Here's a simplified explanation of how they interact:

Input processing: When you send a message to the chatbot, the transformer helps process your input. It breaks down your message into smaller parts and represents them in a way that the chatbot can understand. Each part is called a token.

Understanding context: The transformer passes these tokens to the LLM, which is a language model trained on lots of text data. The LLM has learned patterns and meanings from this data, so it tries to understand the context of your message based on what it has learned.

Generating response: Once the LLM understands your message, it generates a response based on its understanding. The transformer then takes this response and converts it into a format that can be easily sent back to you.

Iterative conversation: As the conversation continues, this process repeats. The transformer and LLM work together to process each new input message, understand the context, and generate a relevant response.

The key is that the LLM learns from a large amount of text data to understand language patterns and generate meaningful responses. The transformer helps with the technical aspects of processing and representing the input/output data, allowing the LLM to focus on understanding and generating language.

Once the chatbot understands your message, it uses the language model to generate a response that it thinks will be helpful or interesting to you. The response is sent back to you, and the process continues as you have a back-and-forth conversation with the chatbot.

### Intro: Hugging Face
Hugging Face is an organization that focuses on natural language processing (NLP) and AI. They provide a variety of tools, resources, and services to support NLP tasks.

You'll be making use of their Python library transformers in this project.

Alright! Now that you know how a chatbot works at a high level, let's get started with implementing a simple chatbot!


# Step 1: Installing requirements
Follow these steps to create a Python virtual environment and install the necessary libraries. Open a new terminal first.
Set up your virtual environment:

  1. pip3 install virtualenv
  2. virtualenv my_env # create a virtual environment my_env
  3. source my_env/bin/activate # activate my_env

For this example, you will be using the transformers library, which is an open-source natural language processing (NLP) toolkit with many useful features, and also let's install a torch library.

  1. python3 -m pip install transformers torch

Wait a few minutes to install the packages.


# Interfacing your Chatbot into a Web Interface
## Hosting your chatbot on a backend server

### Prerequisites
In your terminal, let's install the following requisites:

1. python3 -m pip install flask
2. python3 -m pip install flask_cors


### Setting up the server
To create a new Python file, Click on File Explorer, then right-click in the explorer area and select New File. Name this new file app.py.

Run the app using the following command in the Terminal:
python3 app.py



