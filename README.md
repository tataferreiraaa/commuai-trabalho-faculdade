# CommuAI - Assistente de Comunicação Corporativa
https://chatgpt.com/g/g-6a15f13a72308191a0d74714e0e0b006-commuai
![CommuAI](https://via.placeholder.com/800x400?text=CommuAI+-+Assistente+IA)

## 📋 Sobre o Projeto

**CommuAI** é um assistente inteligente baseado em **Custom GPT** que ajuda colaboradores a escreverem textos corporativos de forma rápida, profissional e consistente.

Desenvolvido como trabalho acadêmico para auxiliar na comunicação interna (e-mails, resumos de reunião, comunicados e mensagens de WhatsApp).

## 🎯 Problema Resolvido

- Sobrecarga de RH e colaboradores com redação repetitiva
- Inconsistência no tom e qualidade das comunicações
- Perda de tempo em tarefas administrativas

---
## ✨ Funcionalidades

- Geração de e-mails profissionais
- Resumos automáticos de reuniões
- Comunicados institucionais
- Mensagens para WhatsApp corporativo
- Oferece versões com tons diferentes
- Mantém identidade organizacional

---

## 🛠️ Tecnologias Utilizadas

- **ChatGPT (GPT-4o)** - OpenAI
- **Custom GPT** com Prompt Engineering
- Técnicas: Role Prompting, Regras Estruturadas e Iteração

---

## 📊 Fluxo do CommuAI

```mermaid
flowchart TD
    A[Usuário] --> B[Acessa CommuAI]
    B --> C[Informa: Tipo, Tom, Contexto]
    C --> D{CommuAI Processa}
    D --> E[Gera Texto Estruturado]
    E --> F[Usuário Revisa]
    F -->|Ajustes| D   
    F -->|Aprovado| G[Usa o Texto]
