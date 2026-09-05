# oasys
OASYS - Ollama Agentic System collections. A simple collection of agents, templates, modelfiles. This is to be used as quick reference

# Purpose
A collection of quick agent set ups using Ollama

# Requirement
| Name | Version | Required? |
|---|---|---|
| Ollama || Yes
| git || No(optional)

# Set-up

1. [Install Ollama](https://docs.ollama.com/quickstart)
2. clone this repo - git clone https://github.com/Soumen-No-Hako/oasys.git OR git clone git@github.com:Soumen-No-Hako/oasys.git
3. Run/get some open-weights model's gguf from ollama site or huggingface e.g llama3.2, gemma4 etc.
```bash
ollama run {model-name}
```
4. Run these type of commands to create the Agents/tools
```bash
ollama create {Agent_Name}:{version_number} -f ./Orchestro/orchestro-modelfile
```
5. Run you agents
```bash
ollama run {Agent_name}:{Version_number}
```
