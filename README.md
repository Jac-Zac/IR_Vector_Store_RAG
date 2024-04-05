# Vector Store

### Summary

This is a simple python implementation of a vector store that showcase the ability to use an embedding model to store documents in an high dimensional vector space, and do similarity search to retrieve the most relevant documents.

### Description of the directory

Everything relevant to the implementation is explained and implemented inside a .ipn ... file -> this

### Installation

- Install [Ollama](https://ollama.com/)

- Install the model we are using:

```bash
ollama pull nomic-embed-text
```

#### Clone the repo and move inside it

```bash
git clone https://github.com/Jac-Zac/FFF && cd FFF
```

##### Set up a Python virtual environment

```bash
python -m venv .env
source .env/bin/activate
```

#### Install dependencies

```bash
pip install -r requirements.txt
```
