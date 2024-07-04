# QA-System-with-LlamaIndex-And-Google-Gemini-




## Goal: 
- Build custom `Question, Answering (Information Retrieval) application` system to query against given documents using Llama-Index, Google GeminiAPI     
### Application: 
- LLMs provide answers to your questions searching across wide range of resources. But, this custom QA_Information_Retrival_Application facilitate accessing information from given documents (useful to search confidential/proprietary documents).

# Access Streamlit application
In terminal -->
- create and activate virtual env
- pip install -r requirements.txt
- streamlit run StreamlitApp.py
- http://localhost:8501/
  
# 1. Application interface

![Streamlit QA sys application interface](https://github.com/JunaidARahat/Images/blob/main/326592634-d84cef4c-17b7-45fa-aca5-23e9a1efb9e3.png)

# 2. Application facilitates loading any number of files from `your local directory`
![Load multiple files](https://github.com/JunaidARahat/Images/blob/main/326592330-08dd0abf-5227-4c64-8f6f-8497c817f6ae.png)

# 3. After uploading files, ask question and retrive information as below...........
![QA](https://github.com/JunaidARahat/Images/blob/main/326592824-938118ca-cc8e-4410-988f-c3c2f4027c89.png)

# 4. Ask another question
![QA2](https://github.com/JunaidARahat/Images/blob/main/326592961-4e473f2c-c345-48cd-a18d-eb17cf39cf17.png)



## How to run?

```bash
conda create -n qasys python=3.9 -y
```

```bash
conda activate qasys
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run StreamlitApp.py
```

## Set Environment variables
GOOGLE_API_KEY = get from .env 

## Streamlit application
http://localhost:8501/



