# WhatsApp AI Chatbot

Projeto desenvolvido para demonstrar conhecimentos em automação, Inteligência Artificial e integrações utilizando n8n.

## Tecnologias

- n8n
- Evolution API
- Groq
- PostgreSQL
- Redis
- Docker

## Funcionalidades

- Atendimento automatizado via WhatsApp
- Memória de conversa utilizando Redis
- Registro completo de logs em PostgreSQL
- Tratamento de erros
- Controle de usuários autorizados
- Output estruturado em JSON
- Pré-triagem para agendamento de consultas

## Fluxo

WhatsApp

↓

Evolution API

↓

Webhook (n8n)

↓

Validação do usuário

↓

Groq (IA)

↓

Output Parser

↓

PostgreSQL

↓

Evolution API

↓

WhatsApp

## Recursos implementados

- Estrutura preparada para produção
- Logs completos
- Persistência de memória
- Tratamento de exceções
- Respostas estruturadas
- Integração entre múltiplos serviços

## Observações

Por questões de segurança, credenciais e chaves de API não foram incluídas neste repositório.
