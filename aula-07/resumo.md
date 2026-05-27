# 📘 Resumo — Aula 07  
## Introdução a Frameworks Front-end

---

## 🎯 Objetivo da Aula

Introduzir os conceitos de Frameworks Front-end, apresentar as diferenças entre um Framework e uma Biblioteca, além de introduzir o **React**. A aula também aborda a instalação do Node.js e o passo a passo para a criação de um novo projeto em React.

---

## 📚 Conteúdos abordados

### 🌐 O que é um Framework Front-end

Um framework front-end é um conjunto de ferramentas, bibliotecas e convenções que padronizam o desenvolvimento de interfaces web. Ele fornece uma estrutura pré-definida, acelerando a criação de aplicações complexas. Em comparação com o Vanilla JS, o uso de frameworks permite componentes reutilizáveis, gerenciamento de estado e atualizações eficientes.

### ⚖️ Framework vs Biblioteca

**Framework:**
- Controla o fluxo (inversão de controle).
- Exige uma estrutura definida.
- Exemplos: Angular, Vue.

**Biblioteca:**
- Você controla quando chamar.
- Flexível, sem imposições de estrutura.
- Exemplos: React, jQuery.

**Por que Utilizar um Framework?**
- **Produtividade Aumentada:** Evita reinventar a roda.
- **Melhores Práticas:** Código organizado em componentes.
- **Manutenção Facilitada:** Virtual DOM, Change Detection, etc.
- **Comunidade e Suporte:** Extensa documentação e soluções prontas.

---

### ⚛️ Introdução ao React

- Desenvolvida pelo Facebook em 2013, o **React** não é um framework, mas sim uma **biblioteca JavaScript** para construir interfaces de usuário de forma interativa.
- **Virtual DOM:** Uma representação em árvore da estrutura da página. O React cria uma cópia rápida desse modelo, atualiza as mudanças e aplica apenas as diferenças no DOM real, tornando o processo mais rápido.
- **Hooks Principais:** 
  - `useState`: Gerencia o estado de um componente.
  - `useEffect`: Lida com efeitos colaterais como chamadas de API.
- **JSX:** Permite o uso de expressões JavaScript em conjunto com HTML, exigindo uso de *camelCase* para atributos (ex: `className`) e tags sempre fechadas (ex: `<img />`).

---

### ⚙️ Node.js e NPM

- **Node.js:** Ambiente de execução JavaScript no lado do servidor (backend).
- **NPM (Node Package Manager):** Gerenciador de pacotes instalado junto ao Node.js. Facilita o controle de dependências, que são registradas no arquivo `package.json`.

---

### 🚀 Criando um Projeto React

Para inicializar um projeto, utiliza-se a ferramenta `create-react-app`, que já vem com configurações de build e ambiente local prontas.

**Passo a passo:**
1. Criar o projeto: `npx create-react-app meu-projeto-react`
2. Acessar a pasta: `cd meu-projeto-react`
3. Abrir o VS Code: `code .`
4. Iniciar o servidor local: `npm start`

**Estrutura básica de arquivos:**
- `node_modules`: Pasta com pacotes e dependências.
- `public`: Arquivos estáticos (HTML, JSON, imagens).
- `src`: Arquivos JS e CSS do React.
  - `index.js`: Ponto de entrada que renderiza o App no DOM.
  - `App.js`: Componente raiz.

---

## 📌 Atividade da Aula

1. Criar um projeto React com um cabeçalho que liste as funcionalidades: To-Do List, Contador de Cliques, Jogo da Velha, Calculadora e Buscador de CEP.
2. Utilizar o Git para realizar o commit no GitHub.
3. Realizar o deploy no Vercel conectando ao repositório para o site ficar online.
4. Documentar os elementos e a escolha da estilização.

---

## ✅ Conclusão

A aula introduziu a necessidade e o funcionamento das bibliotecas e frameworks modernos. O foco foi capacitar o início do desenvolvimento com **React**, instalando o ambiente necessário e compreendendo a estrutura de componentes que ele exige.

---

> 🔗 **Projeto concluído:** O link do repositório é [https://github.com/tav0dev/meu-projeto-react](https://github.com/tav0dev/meu-projeto-react) e o site publicado está em [https://meu-projeto-react-bay.vercel.app/](https://meu-projeto-react-bay.vercel.app/).

---

### 💡 Observações do Aluno

> Adeus Vanilla JS, olá React! A componentização muda tudo.

<img src="https://media.giphy.com/media/11P7GoTttUE1HO/giphy.gif" width="250">
