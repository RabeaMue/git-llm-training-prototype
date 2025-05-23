# Git-LLM Project

> A reproducible prototype for personalized Git training using local LLMs (e.g. Phi) with LlamaIndex and Carpentries content.  
> Developed with FAIR and open science principles in mind.

⚠️ **This project is under active development.**  
It is intended as an experimental prototype and not yet ready for production use. Contributions and feedback are welcome.

## Contents

- `git_llm_training_data.json` – Example questions and answers based on the Library Carpentry Git lesson
- `git_llm_prototype.ipynb` – Interactive notebook with a simple retrieval-based system
- `requirements.txt` – List of Python dependencies

## Setup

### 1. Create and activate virtual environment

```bash
python3 -m venv llm-env
source llm-env/bin/activate
```

### 2. Install dependencies

`pip install -r requirements.txt`

### 3. Start the local LLM using Ollama

Install Ollama (see [https://ollama.com](https://ollama.com)):

`curl -fsSL https://ollama.com/install.sh | sh`

Start the model (Phi-2):

`ollama run phi`

### 4. Launch the notebook

`jupyter notebook`

Then open `git_llm_prototype.ipynb` and select the kernel that matches your virtual environment.

## License

This project and its contents are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to share and adapt the material, provided that you give appropriate credit.

© 2025 Rabea Müller
