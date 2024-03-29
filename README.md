﻿# LLM
# GenerativeAI

The repo contains the following notebooks: 
1. Implement_Encoder_Transformer_PyTorch.ipynb. This notebook contains the Pytorch implementation of an encoder transformer from scratch (follow the architecture defined by "attention is all you need")
2. Fine_Tune_Generative_AI_Models.ipynb. This notebook contains the code to fine tune FLAN-T5 model for summarizing dialogues using full fine tune, PEFT/LoRA and model evaluation by ROGUE
3. Using_HuggingFace_LLMs.ipynb demonstrates how to use Huuging face pipeline API to execute common tasks including text classification, text generation, question/answer and translation. It also contains the code of full fine tuning of a distil-bert-base model for text classification
In addition, in the folder of LangChain_Apps there are two notebooks:
4. Prompt_Engineering_GPT_Langchain.ipynb. This notebook contains concepts and code for commonly used prompt engineering techniques for GPT models. Including the use of system messages, prompt template, LLM chain, tools and agents, few shot learning and output parsers
5. RAG_OpenAI_Pinecone.ipynb. This notebook contains the code example of using langchain's OpenAI APIs and Pinecone vector database to store external information and using augmented prompts with contexts defined by information retrieved from pinecone to optimize outcomes. It contains the code to establish the Pinecone index, connect to database, load and retrieve information from the database
