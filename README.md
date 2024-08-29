# Projeto apresentado a disciplina de Processamento de Linguagem Natural

Tecnologias envolvidas:
1. ChatGPT
2. LangChain
3. Python

## Gerador de notícias automatica

A proposta desse exemplo foi a criação de reportagem de maneira automatizada, utilizando o framework LangChain.
* O ChatGPT (versão 3.5) foi a LLM, utilizamos a API da OpenAi para fazer a ligação, essa configuração esta no arquivo de configuração de ambiente (.env)
* LangChain é o framework mais utilizado para a criação de aplicações baseada em LLMs e também para melhorar o contexto da solução apresentada (RAG).
  Nesse caso foi utilizado uma base de dados vetorial, contendo reportagens atualizadas sobre alguns assuntos.

### Prompt
Criamos um prompt que era uma jornalista com algumas caracteristicas especificas. Foi solicitado o desenvolvimento de noticias atuais.



