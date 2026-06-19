#                                  CODING_HELPER_BOT 


### PROBLEM STATEMENT:


   "To build an intelligent conversational coding assistant that uses Retrieval-Augmented Generation (RAG) to provide accurate, source-grounded answers to programming questions by searching a user-curated knowledge base of documents and code files.it helps to learn AI skills"

### FEATURES/USES CASES:

 For students & learners: Instant doubt solver,Study notes assistant,etc,.
 For developers & teams : Private codebase Q&A,Documentation search ,etc
 Special & creative uses:Hackathon assistant,Exam preparation,etc,.

 ### TECHNOLOGIES :

1. Python = Main programming language
2. Streamlit = Creates the web interface
3. Google Gemini API = Large Language Model (LLM)
4. Python Dotenv = Loads API keys from the .env file
5. Environment Variables (.env) = Securely stores API keys

### INSTALLATIONS :

1.CREATE A VIRTUAL ENVIRONMENT

| python -m venv venv |

2.ACTIVATE

| .\venv\Scripts\Activate |

3.INSTALL LABRARIES

| pip install -r requirements.txt |

4.INSTALL THE PACKAGE

| pip install google-generativeai |

5.CREATING API KEY 

| GOOGLE_API_KEY=your_api_key_here |

6.RUN APP.PY

7.STREAMLIT 

| streamlit run app.py |

### WORKFLOW OF CODING_HELPER_BOT:

-> user ask query related to errors,programming languages,codes.   
-> query to gemini api key and text files
-> search the related answer
-> send it to user

 ### USE CASES:

For students & learners: Instant doubt solver,Study notes assistant,etc,.
For developers & teams : Private codebase Q&A,Documentation search ,etc
Special & creative uses:Hackathon assistant,Exam preparation,etc,.
