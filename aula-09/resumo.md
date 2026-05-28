# 📘 Resumo — Aula 09  
## Introdução a Frameworks Back-end

---

## 🎯 Objetivo da Aula

Introduzir os conceitos fundamentais de desenvolvimento back-end, incluindo a importância e as características dos frameworks, arquitetura de software, construção de APIs RESTful utilizando **Express.js** e o funcionamento do protocolo HTTP.

---

## 📚 Conteúdos abordados

### ⚙️ Frameworks Back-end
Um framework back-end fornece um conjunto de ferramentas e convenções para padronizar o desenvolvimento da lógica de servidor, APIs e acesso a banco de dados. 
- **Vantagens:** Rotas organizadas, gerenciamento simplificado, segurança integrada e otimização de desempenho.
- **Características:**
  - Estrutura organizada (como MVC - Model, View, Controller).
  - Componentização (microsserviços, middlewares).
  - Programação assíncrona (não-bloqueante).
  - Padrões de segurança embutidos (proteção contra SQL Injection, etc).
  - Sistema de rotas e APIs intuitivo.

### 🏛️ Arquitetura de Software e Design Patterns
A arquitetura determina a escalabilidade, manutenção e desempenho do sistema.
- **Design Patterns:** Padrões de projeto divididos em Criacionais (ex: Singleton, Factory), Estruturais (ex: Adapter, Proxy) e Comportamentais (ex: Observer, Strategy).
- **Monolito vs Microsserviços:** 
  - *Monolito:* Única aplicação, desenvolvimento simples, difícil de escalar isoladamente.
  - *Microsserviços:* Serviços independentes, altamente escaláveis, porém com maior complexidade operacional.
  - *Estudo de Caso:* A Amazon Prime Video migrou de microsserviços serverless para monolito para reduzir gargalos e custos (economia de 90%), demonstrando que cada projeto tem necessidades específicas.

### 🌐 Protocolo HTTP e APIs
- **HTTP:** Protocolo de comunicação baseado no modelo cliente-servidor (stateless).
- **Métodos Principais:** `GET` (recuperar), `POST` (criar), `PUT/PATCH` (atualizar), `DELETE` (remover).
- **API REST:** Interface baseada em URIs (endpoints) usando métodos HTTP para comunicação padronizada.
- **JSON:** JavaScript Object Notation. Formato leve de troca de dados (objetos e arrays) ideal para integrações.

### 🚀 Framework Express.js
- Framework minimalista e rápido para **Node.js**.
- Simplifica a criação de rotas, middlewares e APIs.
- Ideal para APIs REST, mas deve ser evitado em processos muito pesados de CPU (onde recomenda-se usar Workers).
- **CORS:** Mecanismo de segurança que permite requisições de domínios diferentes. Essencial para conectar um Front-end e um Back-end em servidores distintos.

### ☁️ Render
Plataforma de hospedagem na nuvem que permite o deploy contínuo integrado ao GitHub. Ideal para simular e hospedar Web Services e APIs gratuitamente, inclusive fornecendo certificado SSL.

---

## 📌 Atividade da Aula

1. Criar uma API utilizando **Express.js** contendo uma rota de consulta para retornar a **data e a hora** atual.
2. Realizar o deploy do Back-end no **Render**.
3. Desenvolver uma aplicação **Front-end** em um repositório separado que consuma essa API e exiba a data e hora na tela.
4. Fazer o deploy do Front-end (ex: na Vercel).
5. Documentar todo o processo com prints e os respectivos links.

---

## ✅ Conclusão

A aula 09 marcou a transição para o lado do servidor, explorando o uso do Express.js para criar Web Services robustos. A prática evidenciou a dinâmica real do mercado: um front-end (cliente) solicitando dados a um back-end (API) hospedado em um serviço como o Render.

---

> 🔗 **Projetos concluídos (Deploy e Repositórios):**
> *(A documentação com os prints de funcionamento encontra-se **nos respectivos repositórios de cada projeto no GitHub**).*
> 
> **Back-end (API Express):**
> - Repositório: [https://github.com/tav0dev/meu-projeto-express](https://github.com/tav0dev/meu-projeto-express)
> - Web Service (Render): [https://meu-projeto-express.onrender.com/](https://meu-projeto-express.onrender.com/)
> 
> **Front-end:**
> - Repositório: [https://github.com/tav0dev/meu-projeto-frontend](https://github.com/tav0dev/meu-projeto-frontend)
> - Site publicado (Vercel): [https://meu-projeto-frontend-six.vercel.app/](https://meu-projeto-frontend-six.vercel.app/)

---

### 💡 Observações do Aluno

> Finalmente no backend! Achei que o Express ia ser um bicho de sete cabeças, mas até que é tranquilo (tirando o CORS 😅). O deploy no Render salvou demais!

![Hacker Cat](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXVmd2xwczhmbzR6ZzU5ZDRrY2RyMDNkeGNwa2djZHB3cnJiaDJocCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/B4dt6rXq6nABilHTYM/giphy.gif)
