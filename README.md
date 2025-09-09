# Build-a-complete-medical-chat-bot-with-LLM


# How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/mhmdrza9789/Build-a-complete-medical-chat-bot-with-LLM.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.12 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py