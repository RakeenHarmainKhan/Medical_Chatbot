# Medical Chatbot Using LangChain

# How to run?
### STEPS:

Clone the repository

```bash
git clonehttps://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
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
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone

### Result:
<img width="956" height="579" alt="Screenshot 2025-11-19 184207" src="https://github.com/user-attachments/assets/feef4f5c-70b1-4ec2-aa96-6bbdfe2dce38" />
<img width="961" height="580" alt="Screenshot 2025-11-19 184120" src="https://github.com/user-attachments/assets/d394289a-7b57-4dd8-846c-39ee8b101de8" />


