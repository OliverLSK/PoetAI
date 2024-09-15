**NLP Finetuning LORA Qwen1.5-4B-Chat
**

**Learning Objective
**Demonstration of fineturing pretrained model for specific purpose. In this case, it's turning model to poem generator.

**Overiew
**This project is to train and to finetune pretrained model to become PoetBot. The goal of this project is to train chatbot that can construct short quote using themes listed in keywords with correct logic and grammar. For example, given keywords 'friendship, love', model could generate sentences with theme of friendship and love but not necessary contain words of 'friendship' or 'love', like:

There is nothing I would not do for those who are really firends. I have no notion of loving people by halves, it is not my native.
If I had a flower for every time I thought of you... I could walk through my garden forever.
This model is different with general keyword-generation model on:

Number of keywords is not fixed.
Sentence generated is random.
Related Works
Conditional text/story generation: For task of conditional text or story generation, model usually use all keywords to compromise new sentence or story using seq2seq model with attention mechanism other pretrained model as GPT-3 and BART. Hierarchial story generation: This task requires to draft story line and then new story is generated based on input story line. Meaningful and detailed sentence would be required as input to generate accurate stories.

**Dataset
**Quotes-500k in Kaggle, which stores qoutes with various category tags ranging from love, life to philisophy, motivation to describes quote which categories belong to.
