# chatbox_ml
📄🤖 Chatbot com IA Generativa para responder perguntas sobre conteúdo de PDFs.
# 📄🤖 Chatbot Inteligente para Consulta de PDFs (Projeto TCC Assistant)

## 📌 Sobre o Projeto

Este projeto é uma resposta ao desafio de criar um **chat interativo capaz de responder perguntas com base no conteúdo de arquivos PDF fornecidos pelo usuário**. Inspirado no cenário de um estudante de Engenharia de Software preparando seu Trabalho de Conclusão de Curso (TCC), o objetivo é facilitar a revisão e correlação de informações contidas em múltiplos artigos científicos ou documentos extensos.

À medida que a quantidade de documentos aumenta, a tarefa de localizar dados específicos e conectar ideias se torna complexa. Este projeto utiliza **Inteligência Artificial Generativa**, **embeddings** e **busca vetorial** (formando um sistema de Retrieval-Augmented Generation - RAG) para criar uma solução de busca inteligente e conversacional.

O resultado é um assistente virtual personalizado, focado em um conjunto de informações proprietárias (os PDFs carregados), capaz de interpretar o conteúdo, organizar informações semanticamente e gerar respostas contextualmente relevantes.

## 🎯 Objetivos

O desenvolvimento deste projeto visa capacitar o usuário a:

✅ **Carregar múltiplos arquivos PDF** que sirvam como base de conhecimento para o chatbot.
✅ **Implementar um sistema de busca vetorial** eficiente para indexar o conteúdo textual dos PDFs e permitir a recuperação rápida de trechos relevantes com base na semântica da pergunta.
✅ **Utilizar modelos de linguagem de IA Generativa (LLMs)** para processar os trechos recuperados e formular respostas coesas e informativas, fundamentadas exclusivamente nos documentos fornecidos.
✅ **Desenvolver uma interface de chat interativa** onde o usuário possa fazer perguntas em linguagem natural e receber respostas contextuais diretamente do conteúdo dos seus PDFs.

## 🔑 Conceitos Chave

* **IA Generativa:** Uso de modelos de linguagem grandes (LLMs) para gerar texto (respostas) de forma criativa e coerente.
* **Embeddings:** Representações numéricas (vetores) do significado semântico do texto, permitindo que a máquina "entenda" a similaridade entre palavras e frases.
* **Busca Vetorial:** Técnica para encontrar os vetores (e, portanto, os trechos de texto) mais similares a um vetor de consulta (a pergunta do usuário) dentro de um banco de dados vetorial.
* **Retrieval-Augmented Generation (RAG):** Arquitetura que combina a recuperação de informações relevantes (Retrieval) de uma base de conhecimento com a capacidade de geração de texto (Generation) de um LLM para produzir respostas mais precisas e contextualizadas.

## 🛠️ Tecnologias Potenciais (Exemplo)

* **Linguagem:** Python
* **Processamento de PDF:** PyPDF2, PyMuPDF
* **Frameworks de Orquestração (RAG):** LangChain, LlamaIndex
* **Embeddings:** Modelos da Hugging Face (Sentence Transformers), OpenAI Embeddings (via API), Azure OpenAI Embeddings
* **Vector Stores (Bancos de Dados Vetoriais):** FAISS, ChromaDB, Pinecone, Azure AI Search
* **Modelos de Linguagem (LLM):** Modelos da Hugging Face (Flan-T5, Llama), OpenAI GPT (via API), Azure OpenAI Service
* **Interface do Chat:** Streamlit, Gradio, Flask/Django

