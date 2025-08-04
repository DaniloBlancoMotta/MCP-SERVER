# AI Engineer - Assistente IA com PydanticAI + MCP

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
## MCP Server
## 1. Configuração Base: 
Criamos um agente PydanticAI conectado à API Groq com 4 modelos LLM disponíveis.

## 2. Interface Web: 
Usamos Gradio para criar uma UI elegante com chat, seletor de modelos e status em tempo real.

## 3. Processamento Assíncrono: 
Implementamos timeout de 15s e execução em threads para evitar travamentos.

## 4. Funcionalidades: 
Adicionamos teste de conexão, troca de modelos dinâmica e histórico de conversas.

## 5. Segurança: 
Configuramos variáveis de ambiente para API keys e tratamento robusto de erros.

## Resultado: 
Assistente IA completo rodando em localhost:7862
