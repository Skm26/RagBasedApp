# Simple-RAG-Based Application 
The Repository Consists of the following :-
  - Retrieval-Augmented Generation (RAG) model for a Question Answering (QA)
    bot using Pinecone DB vector database like Cohere Genrative Model in a ipynb notebook.
  - An Apllication which runs the same RAG model above via Streamlit.
  - Docker File (For building the image)

Instructions
  - For Notebook :- Download the notebook and run via VScode, Collab etc...
  - For App.py :- Install the dependencies and run the application on streamlit (streamlit run app.py)

## Docker 
 Run the following commands to pull and run the docker version of the application

 - Pull :- docker pull skm26/myapp
 - Run :- docker run -p 8501:8501  skm26/myapp
