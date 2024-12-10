# Simple-RAG-Based Application 
The Repository Consists of the following :-
  - Retrieval-Augmented Generation (RAG) model for a Question Answering (QA)
    bot using Pinecone DB vector database like Cohere Genrative Model in a ipynb notebook.
  - An Application which runs the same RAG model above via Streamlit.
  - Docker File (For building the image)

Architecture
![Blank diagram_page-0001](https://github.com/user-attachments/assets/306db2c1-d842-42b0-8873-275cfbd9bf73)
[Note:- Front end not included in diagram]



Instructions
  - For Notebook :- Download the notebook and run via VScode, Collab etc...
  - For App.py :- Install the dependencies and run the application on streamlit (streamlit run app.py)

## Docker 
 Run the following commands to pull and run the docker version of the application

 - Pull :- docker pull skm26/myapp
 - Run :- docker run -p 8501:8501  skm26/myapp
