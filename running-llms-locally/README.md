# Local LLMs Running Guide

This README provides a guide on how to run Large Language Models (LLMs) locally using tools such as Ollama, LM Studio, and NVIDIA ChatRTX. Each tool caters to different system capabilities and user preferences.

## Tools Overview

### 1. **Ollama**
- **Description**: Ollama is a command-line tool that simplifies the management of LLMs. It is suitable for MacOS and Linux systems with Windows support coming soon.
- **Installation**:
  ```bash
  # Visit https://ollama.ai to download and install for your OS.
  # Example command to pull and run a model:
  ollama pull llama2-uncensored
  ollama run llama2-uncensored
