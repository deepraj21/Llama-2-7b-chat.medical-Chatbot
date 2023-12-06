# Llama2-Medical-Chatbot
This is a medical bot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

# Contribute

clone the repo

```
git clone https://github.com/deepraj21/Llama-2-7b-chat.medical-Chatbot
```

Get into the cloned repo

```
cd Llama-2-7b-chat.medical-Chatbot
```

Install the requirements for the project

```
pip install -r requirements.txt
```

Run the ingest.py for dumping the pdf data into pkl

```
python ingest.py
```

Run the Webapp made using chainlit

```
chainlit run model.py
```
