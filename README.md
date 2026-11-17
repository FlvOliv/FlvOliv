# Flávio Henrique Oliveira da Silva

**Software engineer, AI products**

Estudante de Ciência da Computação na FECAP (previsão jun/2028). Construo software com LLMs em produção.

## Projeto em destaque: Malu

[chatbot-agencia](https://github.com/FlvOliv/chatbot-agencia) · Assistente de WhatsApp em produção para a agência de viagens Lu Milhas & Viagens. O repo é um fork do protótipo de Gustavo Marcello (v1, maio/2026). A partir de junho/2026 evoluí o projeto e escrevi a maior parte da suíte de testes. A divisão está na seção "Origem e autoria" do README.

- **Roteamento multi-LLM com fallback automático:** Groq → Cerebras (gpt-oss-120b) → Mistral → Gemini. A ordem segue a LGPD: o provedor que treina com os dados fica por último. Falha ou resposta vazia pula para o próximo.
- **Extração estruturada:** briefing de viagem em JSON (29 campos e temperatura do lead), normalização de datas, quantidades e idades, e gate de completude antes do handoff para a agente humana.
- **Robustez de conversa:** anti-loop, anti-amnésia, guarda contra preço inventado, transcrição de áudio e integração com CRM.
- **Testes:** 453 testes automatizados, incluindo uma suíte de conformidade que roda o pipeline real com I/O externo simulado.
- **Avaliação de LLMs:** framework que compara qualidade, custo e latência em 30 conversas sintéticas de 7 categorias, com travas de cota e custo. Rodada em andamento.

Stack: Python 3.12 · FastAPI · Redis · Postgres/Alembic · WhatsApp Cloud API · Railway · pytest

## Experiência

Gentrop (estágio de desenvolvimento, produto com LLM) · Brasil Produção Pró (SaaS full-stack) · Scotiabank (Segurança da Informação) · Red Hat (Sales Operations)

## Stack

Python · TypeScript · SQL · FastAPI · Next.js · React · Bun/ElysiaJS · PostgreSQL/Supabase · Redis · Docker · GCP · Vercel · Railway

## Contato

[LinkedIn](https://www.linkedin.com/in/flavio-henrique-oliveira-090985235/)