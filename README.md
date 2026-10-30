# 🤖 GuiIA — Agente Especialista em Engenharia de Prompt

<p align="center">
  <img src="https://github.com/Guiia-chat/Guiia_Oficial/blob/main/Gui%20IA/static/GUIA_IA.png" alt="Logo GuiIA" width="300"/>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-diferenciais-e-acessibilidade">Diferenciais</a> •
  <a href="#-arquitetura-e-tecnologias">Tecnologias</a> •
  <a href="#-estrutura-do-repositório">Estrutura</a> •
  <a href="#-como-executar-o-projeto">Como Executar</a> •
  <a href="#-equipe">Equipe</a>
</p>

---

## 📖 Sobre o Projeto

O **GuiIA** é uma plataforma inteligente desenvolvida como projeto acadêmico (voltado para o segundo semestre de faculdade), com o propósito de democratizar o acesso e o conhecimento sobre a **Engenharia de Prompt**. 

A aplicação funciona como um assistente virtual especializado em orientar estudantes e o público geral a interagirem de maneira eficiente, clara e assertiva com modelos de Inteligência Artificial. O diferencial pedagógico da ferramenta reside no fato de que o comportamento e a base de conhecimento do agente foram moldados através de uma **apostila exclusiva** desenvolvida pela equipe ao longo do semestre.

---

## ♿ Diferenciais e Acessibilidade

Mais do que ensinar sobre IA, o GuiIA nasceu com um forte compromisso social:
* **Democratização do Conhecimento:** Facilita o aprendizado de técnicas de prompt para iniciantes e não-estudantes.
* **Foco em Inclusão:** O projeto foi idealizado pensando na acessibilidade para **pessoas com deficiência visual**, incorporando suporte a formatos de materiais acessíveis, como interatividade por voz e recursos de áudio.
* **Base de Conhecimento Especializada:** O agente consome conteúdos direcionados (apostilas temáticas), evitando respostas genéricas e focando no aprendizado prático.

---

## 🚀 Tecnologias Utilizadas

O ecossistema do projeto foi divido em camadas para garantir modularidade e performance:

### Front-End
* **HTML5:** Estruturação semântica e esqueleto das páginas.
* **CSS3:** Estilização responsiva e identidade visual do assistente.
* **JavaScript:** Dinamismo da interface, manipulação de DOM e gerenciamento de formulários/envio de mensagens.

### Back-End
* **Python:** Linguagem central para o processamento de rotinas de IA e manipulação de dados.
* **Flask:** Microframework web leve utilizado para gerenciar as rotas e integrar a interface com os modelos de IA.
* **Java:** Utilizado em serviços complementares, incluindo a integração segura da tela de autenticação/login com o banco de dados relacional.

### Banco de Dados
* **MySQL / MySQL Workbench:** Armazenamento estruturado de dados de usuários e credenciais de acesso.

---

## ⚙️ Arquitetura do Sistema

```text
[ Front-End (HTML/CSS/JS) ] 
       │
       ▼ (Requisições HTTP / Fetch)
[ Back-End Flask (Python) ] ──> [ Modelos de IA / RAG (Apostila GuiIA) ]
       │
       ▼ (Autenticação / Credenciais)
[ Serviço Java ] ──> [ Banco de Dados MySQL ]
