# calortrack-lite

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Local LLM chat interface using Ollama with support for custom GGUF model files and Chainlit UI.

## bootstrap-data-table
- Install Ollama: https://ollama.com
- Browse models: https://ollama.com/library
- Chainlit docs: https://docs.chainlit.io/get-started/overview

## Rest-Server
```bash
ollama run mistral
ollama list
ollama rm <modelname>
```

## dream-background-remover
```bash
conda create --name llmenv python=3.9
conda activate llmenv
pip install -r requirements.txt
pip install transformers==4.20.0
```

GPU acceleration (Apple Silicon):
```bash
conda install pytorch torchvision torchaudio -c pytorch-nightly
```

## vendor_motorola_titan
```bash
huggingface-cli download org/ModelName file.gguf --local-dir .
ollama create mymodel -f Modelfile
ollama run mymodel
```

## ya-shri-bem-pract
```bash
chainlit run chat-medical.py    # medical domain
chainlit run chat-code.py       # code generation
```

## BestPY
Clean up cached models:
```bash
cd ~/.cache/huggingface/hub
huggingface-cli delete-cache
```

## droidbrute
- What are the symptoms of the common cold?
- Wie importiert man ein Package in Java?
- Schreibe mir einen Python Flask Server

## salesforce_bulk_api
Contributions welcome. Fork → branch → pull request.
