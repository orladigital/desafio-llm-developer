# Desafio Técnico – LLM Developer

Assistente Inteligente para Site Orla.tech

## Descrição

Sua missão é desenvolver um **LLM Agent** que seja capaz de **indexar todo o conteúdo do site [https://www.orla.tech](https://www.orla.tech/)** e criar um **assistente virtual** que responda com precisão e segurança a **qualquer pergunta baseada nas informações do site**.

---

## O que você deve construir

- Um **pipeline de RAG (Retrieval-Augmented Generation)** completo:
  - Crawling e parsing das páginas do site.
  - Indexação em uma **base vetorizada**.
  - Criação de um **chatbot** que utilize a base vetorizada para responder às perguntas do usuário.

- Um mecanismo de **validação da eficácia das respostas**:
  - Pode utilizar datasets sintéticos ou perguntas reais baseadas no conteúdo.

- Implementação de **guardrails** para:
  - Impedir respostas com vieses antiéticos, discriminatórios ou que divulguem informações falsas.
  - Bloquear respostas que envolvam **concorrentes diretos da Orla.tech** ou especulações sobre eles.

---

## Requisitos

- Utilizar um modelo LLM local ou via API (por exemplo: OpenAI, Mistral, GROQ, etc.).
- Utilizar **uma técnica de RAG** com embeddings e busca vetorial.
- O agente deve ser capaz de **responder perguntas em linguagem natural** como:
  - "O que a Orla.tech faz?"
  - "Quais serviços a empresa oferece?"
  - "Quem são os parceiros da Orla?"
  - "Como entrar em contato com a equipe?"
---

## Critérios de Avaliação

- Eficiência na indexação do conteúdo do site
- Precisão e completude das respostas
- Implementação da técnica de RAG 
- Guardrails implementados (ética + concorrentes)

## Entregáveis

- Código-fonte completo em repositório público no seu GitHub.
- `README.md` com instruções claras para:
  - Rodar o projeto localmente.
  - Testar o agente e enviar perguntas.


## Dicas e Considerações

- Evite usar apenas scraping bruto — tente extrair o conteúdo mais semântico possível.

---

## Como submeter

3. Envie o link do seu repositório para o recrutador.

Boa sorte! 🍀
