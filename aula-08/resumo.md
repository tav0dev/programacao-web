# 📘 Resumo — Aula 08  
## Atividade com Projetos Front-end

---

## 🎯 Objetivo da Aula

Aprofundar o conhecimento prático na criação e configuração de projetos utilizando os três principais frameworks/bibliotecas front-end do mercado: **React**, **Angular** e **Vue.js**. Além disso, a aula explora a importação de projetos e templates prontos para acelerar o desenvolvimento.

---

## 📚 Conteúdos abordados

### 🟢 Node.js (Revisão)
O Node.js é essencial como ambiente de execução JavaScript no backend e atua como base para rodar as ferramentas de build (via NPM/NPX) dos frameworks front-end abordados.

### ⚛️ Criando um Projeto React
- **Requisitos:** Node.js, conhecimentos em JSX e Hooks (`useState`, `useEffect`).
- **Destaques:** Flexibilidade (não impõe estrutura rígida), grande ecossistema, componentização e Virtual DOM.
- **Criação e Execução:** 
  - `npx create-react-app meu-projeto-react`
  - `npm start`
- **Estrutura básica:** `node_modules`, `public` (arquivos estáticos como `index.html`), `src` (código fonte: `App.js`, `index.js`), `.gitignore` e `package.json`.

### 🅰️ Criando um Projeto Angular
- **Requisitos:** Node.js, conhecimentos em Programação Orientada a Objetos (POO) e TypeScript.
- **Destaques:** Framework completo (inclui roteamento, HTTP client), TypeScript nativo, arquitetura MVC (separação clara de responsabilidades) e uma CLI poderosa.
- **Criação e Execução:** 
  - Instalar CLI: `npm install -g @angular/cli`
  - Criar projeto: `ng new meu-app-angular`
  - Iniciar servidor: `ng serve`
- **Conceitos Fundamentais:** Componentes (`@Component`), Módulos (`@NgModule`), Serviços (`@Injectable`), Data Binding (ex: `[(ngModel)]`) e Roteamento.
- **Estrutura básica:** Pasta `app` com componentes, `main.ts` (inicialização do módulo raiz), `angular.json` (configuração principal do Angular) e configurações de TypeScript (`tsconfig.json`).

### 🖖 Criando um Projeto Vue
- **Requisitos:** Node.js, conhecimentos em JavaScript/TypeScript e programação reativa.
- **Destaques:** Framework progressivo (pode ser adotado gradualmente), reatividade eficiente, Single-File Components (SFC - unindo HTML, CSS e JS em arquivos `.vue`) e curva de aprendizado suave.
- **Criação e Execução:** 
  - `npm create vue@latest`
  - Instalar dependências: `npm install`
  - Iniciar servidor: `npm run dev`
- **Estrutura básica:** Pasta `assets` (arquivos processados pelo Vite), `components`, `App.vue` (componente raiz) e `main.js` (montagem no DOM). Utiliza o Vite como ferramenta de build (`vite.config.js`).

### 📦 Importando Projetos e Templates
Para não começar sempre do zero, pode-se buscar templates prontos desenvolvidos com boas práticas pela comunidade open source. Ferramentas sugeridas:
- **GitHub:** Busca por repositórios (`git clone <url>`).
- **Vercel:** Busca por templates.
- **CodeSandbox:** Busca por ambientes e templates prontos online.

---

## 📌 Atividade da Aula

1. Criar três projetos utilizando os frameworks React, Angular e Vue.
2. Versionar e realizar o commit dos projetos em três repositórios no GitHub.
3. Pesquisar, importar e alterar um template pronto, enviando para um quarto repositório.
4. Fazer o deploy de todos os repositórios na Vercel.
5. Documentar as etapas.

> 📝 **Nota sobre a atividade:** A etapa envolvendo a busca e alteração de um **projeto de template** não foi realizada neste escopo.

---

## ✅ Conclusão

A aula 08 teve um forte caráter prático, demonstrando desde a criação por linha de comando até a exploração das estruturas de pastas e arquivos gerados por padrão nos três maiores ecossistemas front-end atuais (React, Angular e Vue).

---

> 🔗 **Projetos concluídos (Repositórios e Deploy):**
> 
> **Angular:**
> - Repositório: [https://github.com/tav0dev/meu-projeto-angular](https://github.com/tav0dev/meu-projeto-angular)
> - Site publicado: [https://meu-projeto-angular-eight.vercel.app/](https://meu-projeto-angular-eight.vercel.app/)
> 
> **Vue:**
> - Repositório: [https://github.com/tav0dev/meu-projeto-vue](https://github.com/tav0dev/meu-projeto-vue)
> - Site publicado: [https://meu-projeto-vue-blush.vercel.app/](https://meu-projeto-vue-blush.vercel.app/)
>
> *(O projeto em React correspondente a esta atividade foi documentado na aula 07)*

---

### 💡 Observações do Aluno

> Fazer o deploy de 3 projetos ao mesmo tempo me fez sentir uma verdadeira máquina produtiva! Vercel é vida.

<img src="https://media.giphy.com/media/l1AsAMOkYjwteLRkc/giphy.gif" width="250">
