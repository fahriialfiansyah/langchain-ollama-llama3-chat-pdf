# Chat with Multiple PDF Using LangChain, Ollama, and Llama3 8B
This project creates chat local interfaces for multiple PDF documents using LangChain, Ollama, and the LLaMA 3 8B model. The repository includes sample pdf, notebook, and requirements for interacting with and extracting information from PDFs, enabling efficient conversations with document content. It uses Python 3.12.4 and DocArrayInMemorySearch as the vector database.

## Installation Steps
1. Clone the repository:
```shell
git clone https://github.com/fahriialfiansyah/langchain-ollama-llama3-chat-pdf.git
```
2. Navigate to the project directory:
```shell
cd langchain-ollama-llama3-chat-pdf
```
3. This project uses [Pip Python](https://pip.pypa.io/en/stable/) for dependency management. Install the required dependencies:
```shell
# create python environment
python -m venv .venv

# activate the virtual environment
.venv/Scripts/activate

# install the dependencies
pip install -r requirements.txt
```
4. Download Ollama from https://ollama.com and follow their installation instructions.
5. Open terminal to install Llama3:8B LLM Model:
```shell
ollama pull llama3:8b
```
6. Run the code of chat pdf locally.
