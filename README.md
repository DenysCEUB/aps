# 
Projeto de Sistema Computacional do software "Termômetro da Felicidade".

Modelo para o repositório do Projeto de Sistema Computacional para as equipes de alunos da disciplina Análise e Projeto de Sistemas.  

O grupo deverá criar um repositório no GitHub

O grupo deverá seguir no mínimo os tópicos abaixo para o seu projeto.



# 📘 Projeto de Sistema Computacional - "Termômetro da Felicidade"
<img width="192" height="89" alt="image" src="https://github.com/user-attachments/assets/9f00c432-def4-4de7-8b12-439b34ca8b9c" />

Curso: Superior de Tecnologia em Análise e Desenvolvimento de Sistemas

Disciplina: Análise e Projeto de Sistemas

Orientador: Prof. Me. Denys Alves da Silva

Alunos: RA Nome completo e-mail sempreceub


---

## 📑 Sumário
1. [Documento de Visão do Sistema](#1-documento-de-visão-do-sistema)  
2. [Diagrama de Caso de Uso](#2-diagrama-de-caso-de-uso)  
3. [Especificação de Caso de Uso](#3-especificação-de-caso-de-uso)  
4. [Diagrama de Classe](#4-diagrama-de-classe)  
5. [Documento de Arquitetura do Sistema](#5-documento-de-arquitetura-do-sistema)  
6. [Protótipo do Sistema](#6-protótipo-do-sistema)  

---

## 1. Documento de Visão do Sistema

📌 **O que é:**  
Documento inicial que descreve **objetivos, escopo, usuários e restrições** do sistema.  

📌 **Como preencher:**  
- Introdução: breve resumo do sistema.  
- Objetivos do sistema: problemas que resolve.  
- Stakeholders: usuários e clientes.  
- Escopo: principais funcionalidades.  
- Restrições: limitações técnicas, prazos etc.  
- Critérios de sucesso: como medir se o sistema atendeu ao objetivo.  

📄 **Exemplo (preencher no projeto real):**  
Sistema: Gestão de Biblioteca Online
Objetivo: Permitir cadastro e empréstimo de livros digitalmente.
Stakeholders: Alunos, Bibliotecários, Professores.
Escopo: Cadastrar usuários, gerenciar livros, controlar empréstimos e devoluções.
Restrições: Disponível apenas via web.
Critérios de sucesso: 90% dos empréstimos realizados pelo sistema no 1º mês.

---

## 2. Diagrama de Caso de Uso

📌 **O que é:**  
Representação UML das **funcionalidades principais** e **atores envolvidos**.  

📌 **Como preencher:**  
- Identificar os atores (usuário, administrador, sistemas externos).  
- Identificar os casos de uso (funcionalidades).  
- Criar o diagrama em UML (PlantUML, Lucidchart, StarUML, Draw.io).  

📄 **Exemplo de atores e casos de uso:**  
- Atores: Usuário, Bibliotecário.  
- Casos de Uso: Realizar Login, Consultar Livro, Efetuar Empréstimo, Cadastrar Livro.  

📷 **Adicionar aqui o diagrama:**  
/docs/02-diagrama-caso-uso.png

---

## 3. Especificação de Caso de Uso

📌 **O que é:**  
Descrição detalhada do **fluxo principal e alternativo** de cada caso de uso.  

📌 **Modelo de Tabela:**  

| Item                  | Descrição |
|-----------------------|-----------|
| **Nome**              | Realizar Login |
| **Ator Principal**    | Usuário |
| **Pré-condições**     | Usuário já cadastrado no sistema |
| **Fluxo Principal**   | 1. Usuário insere login e senha <br> 2. Sistema valida credenciais <br> 3. Sistema libera acesso |
| **Fluxos Alternativos** | Senha incorreta → Sistema exibe mensagem de erro |
| **Pós-condições**     | Usuário autenticado no sistema |
| **Regras de negócio** | Senha deve ter no mínimo 8 caracteres |

📄 Criar uma tabela como esta **para cada caso de uso** identificado.

---

## 4. Diagrama de Classe

📌 **O que é:**  
Representação estática em UML das **classes, atributos, métodos e relacionamentos**.  

📌 **Como preencher:**  
- Listar classes principais (Ex.: Usuário, Livro, Empréstimo).  
- Definir atributos e métodos.  
- Relacionar com UML (herança, associação, composição, agregação).  

📷 **Adicionar aqui o diagrama:**  

/docs/04-diagrama-classes.png

---

## 5. Documento de Arquitetura do Sistema

📌 **O que é:**  
Definição da **estrutura técnica** do sistema.  

📌 **Como preencher:**  
- Visão geral da arquitetura (camadas ou microsserviços).  
- Tecnologias utilizadas (linguagem, frameworks, banco de dados).  
- Integrações externas (APIs, serviços).  
- Segurança (autenticação, criptografia).  
- Requisitos de desempenho e escalabilidade.  

📄 **Exemplo (preencher no projeto real):**  
Arquitetura em 3 camadas:

Apresentação (JavaFX ou ReactJS)

Negócio (Java - Spring Boot)

Persistência (MySQL)

Integrações: API de Pagamento
Segurança: Autenticação com JWT

---

## 6. Protótipo do Sistema

📌 **O que é:**  
Protótipo visual ou navegável que representa a interface do sistema.  

📌 **Como preencher:**  
- Criar esboços das telas principais (login, cadastro, dashboard).  
- Pode ser feito no **Figma, Balsamiq, Draw.io ou PowerPoint**.  
- Salvar em PDF ou imagem.  

📷 **Adicionar protótipo aqui:**  
/docs/06-prototipo.pdf

---

## ✅ Organização no GitHub
Estrutura de diretórios sugerida:

/Arquivos de Markdown do GitHub para o aluno utilizar obrigatoriamente no seu projeto.

├── [1. Documento de Visão do Sistema](01-visao-sistema.md)

├── [2. Diagrama de Caso de Uso](02-diagrama-caso-uso.md)

├── [3. Especificação de Caso de Uso](03-especificacao-caso-uso.md)

├── [4. Diagrama de Classe](04-diagrama-classes.md)

├── [5. Documento de Arquitetura do Sistema](05-arquitetura-sistema.md)

├── [6. Protótipo do Sistema](06-prototipo.md)

---
