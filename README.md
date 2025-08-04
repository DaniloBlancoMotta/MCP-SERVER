# 🤖 MCP Server - Assistente IA

Interface web elegante para interação com modelos de IA via **PydanticAI** e **Groq API**.

## ✨ Características

- 🎯 **Interface intuitiva** com Gradio
- 🔄 **Múltiplos modelos** Groq disponíveis
- ⚡ **Respostas rápidas** com timeout de 15s
- 📊 **Status em tempo real** da conexão
- 💬 **Chat interativo** com histórico

## 🚀 Instalação

# Instale as dependências
pip install gradio pydantic-ai python-dotenv

# Configure sua API key
echo "GROQ_API_KEY=sua_chave_aqui" > .env
```

## 🎮 Uso

```bash
python PydanticAI_MCP.py
```

Acesse: `http://localhost:7862`

## 🔧 Modelos Disponíveis

- `llama-3.3-70b-versatile` (padrão)
- `llama-3.1-8b-instant`
- `gemma2-9b-it`
- `llama3-70b-8192`

## 📋 Requisitos

- Python 3.8+
- Chave API do Groq
- Conexão com internet

---

*Desenvolvido com usando PydanticAI*
