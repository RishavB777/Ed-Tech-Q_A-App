# Ed-Tech-Q_A-App

QA application designed to enhance the educational experience for students, educators, and lifelong learners which can be used by any Ed-Tech company. 

## Tools used
LLM: [Google PaLM](https://ai.google/discover/palm2)
Fine-tuning: [LangChain](https://www.langchain.com/)
Deployment: [Streamlit](https://streamlit.io/)

## Warning
You would need your own Google PaLM API key to use this
After getting your API key from [MakerSuite](https://makersuite.google.com/app/apikey) edit the .env file

```
GOOGLE_API_KEY = 'YOUR API KEY'
```

## Usage
Run the main.py from your terminal with streamlit:
```
streamlit run main.py
```

We are using faqs.csv as an example FAQ dataset but you can use any dataset according to your needs.
