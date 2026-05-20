# LocalAIAgentWithRAG

This is a beginner project to build a local AI agent using Python. I have used Ollama, LangChain, and ChromaDB; to act as our vector search database. All of this will be local and free to run.


# Setup Python Local Environment:
python3 -m venv venv
source ./venv/bin/activate

# Installing Dependencies
pip install -r ./requirements.txt

# Setup Ollama
- Download Ollama from Ollama site and Install. 
- Check the installation typing ollama in separate terminal window
- Pull llama model using follwoing command : ollama pull llama3.2
- Pull vector embeddings using following command ollama pull mxbai-embed-large
- Check the available models under Ollama by following command : ollama list
