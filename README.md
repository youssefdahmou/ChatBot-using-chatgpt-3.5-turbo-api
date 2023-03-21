# ChatBot-using-chatgpt-3.5-turbo-api
I've developed a chatBot with Python using the chat_gpt API for improving your customer support or engagement approach in a thrilling and inventive manner.


This code creates a simple chatbot using the OpenAI Chat Completion API with the GPT-3.5-turbo model. The chatbot is built using the Gradio library to create a web interface where a user can enter text input and receive a response from the chatbot.

The code starts by importing the necessary libraries, including OpenAI and Gradio, and setting the API key for OpenAI. The messages list is created to store the conversation between the user and the chatbot.

Next, a function named CustomChatGPT is defined to handle the chatbot's response. The user's input is appended to the messages list, and the openai.ChatCompletion.create() method is called to generate a response using the GPT-3.5-turbo model. The response is extracted from the API response and appended to the messages list with the role of "assistant". Finally, the function returns the chatbot's response.

A Gradio interface is created using the CustomChatGPT function as the callback function, with the input and output types set to "text". The interface is given a title of "my chatbot using chatGPT api". Finally, the interface is launched with the demo.launch(share=True) method, which makes it possible to share the interface with others.


# steps :
  ## step 1:
  you need to get you'r api key from here : https://platform.openai.com/account/api-keys
  ## step2 :
  install openai using  your cnd  : pip install openai
  ## step3 :
  install gardio using  your cnd  : pip install gardio
  ## step2 :
  run this script in  your VSC.
