# Agent Base Application

## 1.0 Projects Overview 
This is an agent base application. I defined two agents one is "Retrieve" another one is "Wiki_search". I defined some url for ingestion of the data, after pre-processing and Embedding the data, stored in serverless vector database. I used "DataStax" AstraDB database for storing the data as a serverless vector database. When user will give input(text) Router will take decision wether call the wiki_search agent or VectorDB agent for the best answer. For the LLMs I have choosen "Gemma2-9b-It" from "Groq", for that I used their API  


## 2.0 How to run/check the code 
1. Open the terminal of your local pc and run the below code.  
   git clone https://github.com/hasan-moni-321/Agent.git
2. Change your current directory to Agent directory using below code.  
   cd Agent
3. install the necesary library and dependencies using below code.  
   pip install -r requirements.txt
4. And finally run the cells one-by-one of agent_app.ipynb file.   

 

## How to improve accuracy 
i) Choose the best LLMs model like GPT-4, Llama-3, Gemini-2
ii) Collect more and more data with quality.
iii) Fine-tune the LLMs for better 
iv) If dataset is in dataframe/csv type data store them in MySQL database and query using LLMs model with defining best prompt. 
v) 

## 3.0 Architecture/ Diagram of the Multi Agent AI application/project  
![alt text](https://github.com/hasan-moni-321/Agent/blob/main/images/Screenshot%20from%202024-12-14%2023-34-48.png)  
here is 2 agents one is retrieve and the another one is wiki_search. Retrieve agent is for vectorDB search and wiki_search agent is for wikipedia search. 

## Justification for chosen LLM, frameworks, and data handling strategies  


## Discussion of alternative approaches and trade-offs   
1. Using Swarm framework and mySQL database. Swarm framework for multi-agent and MySQL for the database and then query the MySQL database using LLMs model. Although Swarm is not a framework for deployment, maybe with some months it will be production grade framework by OpenAI. 
2. For multi-agent we can use LangFlow and their API for accesing Agents. Now-a-days its a very popular way to do Agent base application specially for multi-agent. 
3. 

