# 🎯 Agente de Classificação de Sentimentos com Análise Automática de Texto (n8n)

Este repositório contém o workflow completo desenvolvido no **n8n** para análise automática de sentimentos usando **Inteligência Artificial (OpenAI GPT-4o-mini)** e persistência em uma planilha do **Google Sheets**.

O sistema recebe textos via **Webhook**, realiza a análise de sentimento, identifica o tema principal, gera um nível de confiança e salva tudo de forma automática em uma planilha na nuvem.

---

## 🎥 Vídeo Demonstrativo do Projeto

👉 **Assista ao vídeo completo aqui:**  
📌 *[Apresentação n8n](https://youtu.be/elhmm7-OnNY)*


---

## 📋 1. Resumo do Projeto

Este projeto implementa um workflow automatizado que:

- Recebe textos enviados via API/Webhook
- Analisa o sentimento usando IA (OpenAI GPT-4o-mini)
- Classifica como **positivo, negativo ou neutro**
- Identifica o **tema central** do texto
- Calcula um **nível de confiança** (high, medium, low)
- Salva automaticamente todos os resultados em uma planilha Google Sheets
- Retorna uma resposta JSON padronizada ao cliente

---

## 🏗️ 2. Arquitetura do Workflow

Fluxo principal:

1. **Webhook Trigger** → Recebe o texto  
2. **Workflow Configuration** → Prepara os dados  
3. **Sentiment Analysis Agent (OpenAI)** → Classifica o texto  
4. **Parse AI Response** → Extrai JSON corretamente  
5. **Google Sheets** → Salva ou atualiza os dados  
6. **Respond to Webhook** → Retorna o resultado ao usuário

---

## Participantes

- Anna Isabelle
- César Rodrigues
- Evily Maria
