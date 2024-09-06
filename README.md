# Retrieval Augmented Generation Base Custom Chatbot

This repository contains implementation of retrieval augmented generation (RAG) based custom chatbot.

The chatbot is specifically designed for **conversation about the timeline of artificial intelligence (AI)** to answer questions related to events about the advancement of AI up to now.

We will be using `gpt-3.5-turbo-instruct` model, which was trained on data upto **September 2021**. Thus, the model does not have information about AI advancements prior to 2021. The RAG enables the chatbot to access and incorporate relevant and upto date information from external source that the model was not trained on. 
This ensures accurate and contextually appropriate response.
We will be using an upto date from the 
Wikipedia page at [Timeline of artificial intelligence](https://en.wikipedia.org/wiki/Timeline_of_artificial_intelligence). 

Visit [developing_custum_custom_chatbot.ipynb](./developing_custum_custom_chatbot.ipynb) notebook for step by step process of the implementation 
and for comparison between a naive chatbot without RAG and a custom chatbot that uses RAG.
