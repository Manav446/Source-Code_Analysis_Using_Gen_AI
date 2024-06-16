# Source-Code_Analysis_Using_Gen_AI
it is a Gen-AI project which do Source Code Analysis using LLM models.

# Source-Code-Analysis-using-GenAI

# How to run?
### STEPS:

Clone the repository

```bash / CMD
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash / CMD
conda create -n llmapp python=3.8 -y
or you below command
python -m venv <envirnoment_name>
```

```bash / CMD
conda activate <envirnoment_name>
or
<envirnoment_name>\Scripts\activate 
```


### STEP 02- install the requirements
```bash / CMD
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your GEMINI_API_KEY credentials as follows:

```ini
GEMINI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash / CMD
# Finally run the following command
python app.py
```

Now,
```bash / CMD
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Gemini
- Gemini 1.5 Pro
- ChoromaDB

### I have used Google Gemini Open Source API for this project. It's totally upto you which API you guys want to use. Either you guys can use the OpenAI API or Hugging Face Open Source API model too. 
