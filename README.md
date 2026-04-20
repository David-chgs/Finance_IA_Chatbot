# 💰 Finance AI Assistant — Chatbot de Educação Financeira

## 🧠 Visão Geral

O **Finance AI Assistant** é um agente conversacional baseado em IA desenvolvido para explicar conceitos financeiros de forma simples, didática e acessível.

A aplicação utiliza modelos de linguagem (LLMs) para simular um **assistente educacional**, capaz de responder dúvidas, fornecer exemplos práticos e manter contexto ao longo da conversa.

> 🎯 Objetivo: facilitar o aprendizado de finanças por meio de uma experiência interativa em linguagem natural.

---

## 🚀 Funcionalidades

* 💬 Chat interativo via terminal ou notebook
* 🧠 Respostas inteligentes com contexto de conversa (memória)
* 📚 Explicações didáticas sobre finanças pessoais e investimentos
* 🔁 Conversa contínua (context-aware)
* 🌎 Estrutura preparada para múltiplos idiomas

---

## 🧩 Arquitetura da Solução

```text
Usuário (texto)
   ↓
Prompt especializado (finanças)
   ↓
LLM (Groq / Llama 3.1)
   ↓
Resposta contextual
   ↓
Exibição no chat
```

---

## 🧰 Tecnologias Utilizadas

* **Python 3**
* **Groq API**
* **Modelos LLM (Llama 3.1)**
* **Jupyter Notebook / Terminal**

---

## 🎯 Casos de Uso

* Educação financeira básica
* Explicação de conceitos como:

  * Inflação
  * Juros compostos
  * CDI / Selic
  * Renda fixa vs renda variável
* Apoio a iniciantes em investimentos
* Simulação de assistente educacional

---

## 💡 Exemplos de Interação

**Usuário:**

> O que são juros compostos?

**Assistente:**

> Juros compostos são quando os juros são aplicados sobre o valor inicial + os juros acumulados.
> Exemplo: investir R$1000 a 10% ao ano gera R$1100 no primeiro ano e R$1210 no segundo.

---

## ⚙️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/finance-ai-assistant.git
cd finance-ai-assistant
```

---

### 2. Instale as dependências

```bash
pip install groq
```

---

### 3. Configure a API Key

Crie uma variável de ambiente:

```bash
export GROQ_API_KEY=your_api_key_here  # Linux/Mac
setx GROQ_API_KEY your_api_key_here    # Windows
```

---

### 4. Execute o notebook ou script

Se estiver usando notebook:

```bash
jupyter notebook
```

Ou execute via script Python:

```bash
python main.py
```

---

## 🧠 Engenharia de Prompt

O sistema utiliza um prompt estruturado para garantir respostas:

* Simples e didáticas
* Com exemplos práticos
* Sem excesso de jargões técnicos
* Curtas e objetivas

**Exemplo:**

```text
Você é um especialista em finanças pessoais.
Explique conceitos de forma simples, com exemplos e linguagem acessível.
```

---

## 📊 Diferenciais do Projeto

* 🎯 Foco em educação financeira (caso de uso real)
* 🧠 Uso de memória de contexto (chat contínuo)
* ⚡ Integração com modelos modernos via Groq
* 🧩 Arquitetura simples e extensível
* 💼 Aplicação prática de IA generativa

---

## 🚀 Possíveis Evoluções

* 📈 Simulação de investimentos
* 📊 Geração de exemplos numéricos dinâmicos
* 🌐 Interface web com Streamlit
* 📱 Integração com aplicações mobile
* 🧠 RAG com base de conhecimento financeira
* 🌎 Suporte multilíngue (PT/ES/EN)



> 💬 "Aprender finanças nunca foi tão simples quanto conversar."
