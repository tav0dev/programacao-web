# 📘 Resumo --- Aula 03

## Introdução ao Versionamento e Deploy

------------------------------------------------------------------------

## 🎯 Objetivo da Aula

Compreender os fundamentos do **controle de versão de software**,
incluindo versionamento semântico, uso do **Git para gerenciamento de
código**, estratégias de colaboração com **branches e merge**, e o
processo de **deploy de aplicações web**, conectando o desenvolvimento
local ao ambiente de produção.

------------------------------------------------------------------------

## 📚 Conteúdos abordados

### 📂 Versionamento vs Backup

Embora frequentemente confundidos, **versionamento** e **backup**
possuem finalidades diferentes no desenvolvimento de software.

**Versionamento** - Registra **cada alteração** realizada no código. -
Mantém histórico detalhado de **quem alterou, quando e por quê**. -
Permite **colaboração simultânea entre desenvolvedores**. - Possibilita
**reversão granular** para versões anteriores.

**Backup** - Apenas cria uma **cópia pontual do estado atual do
sistema**. - Não registra autoria ou histórico de mudanças. - Não
permite integração de múltiplas alterações. - Recuperação ocorre somente
restaurando todo o backup.

Sem versionamento, projetos frequentemente sofrem com: - múltiplas
versões de arquivos (ex: `versao_final_agora_sim2.zip`); - perda de
código importante; - conflitos entre desenvolvedores; - ausência de
histórico de mudanças.

------------------------------------------------------------------------

### 🔢 Versionamento Semântico (SemVer)

O **Versionamento Semântico (Semantic Versioning)** é um padrão
amplamente utilizado para identificar mudanças em softwares.

Estrutura padrão:

    MAJOR.MINOR.PATCH

**MAJOR (ex: 2.0.0)** - Mudanças incompatíveis com versões anteriores.

**MINOR (ex: 1.1.0)** - Novas funcionalidades compatíveis com versões
anteriores.

**PATCH (ex: 1.0.1)** - Correções de bugs sem alteração de
funcionalidade.

Exemplo de evolução:

-   **1.0.0** → primeira versão estável
-   **1.1.0** → adição de nova funcionalidade
-   **1.1.1** → correção de bug
-   **2.0.0** → mudança incompatível

Antes da versão estável: - **0.x.x** indica software em desenvolvimento.

------------------------------------------------------------------------

### 🔧 Tipos de Alterações em um Software

Durante o desenvolvimento, diferentes tipos de mudanças podem ocorrer:

-   **Bug Fix** -- correção de erros
-   **New Feature** -- nova funcionalidade
-   **Feature Enhancement** -- melhoria de funcionalidades existentes
-   **Refactoring** -- reorganização do código para maior qualidade
-   **Performance** -- otimização de desempenho
-   **Security Patch** -- correção de vulnerabilidades
-   **Dependency Update** -- atualização de bibliotecas
-   **Adding Tests** -- inclusão de testes automatizados

Essas mudanças ajudam a manter a **evolução organizada do software**.

------------------------------------------------------------------------

### 🧰 Git e Controle de Versão

O **Git** é um sistema distribuído de controle de versão utilizado para
gerenciar alterações no código.

Principais funcionalidades:

-   registrar histórico completo de alterações;
-   restaurar versões anteriores do projeto;
-   sincronizar código com repositórios remotos;
-   permitir colaboração entre múltiplos desenvolvedores.

Fluxo básico de utilização:

1.  Instalar o Git
2.  Configurar usuário e e-mail
3.  Criar um repositório
4.  Realizar commits para registrar alterações
5.  Publicar o projeto em plataformas como GitHub

------------------------------------------------------------------------

### 🏷️ Tags no Git

**Tags** são marcadores utilizados para identificar versões importantes
no histórico do projeto.

Tipos:

**Lightweight tag** - Apenas um nome associado a um commit.

**Annotated tag** - Inclui informações adicionais como: - autor - data -
descrição da versão.

Uso comum: - marcar **releases ou versões estáveis do software**.

Exemplo:

    git tag 1.0.0
    git push origin 1.0.0

------------------------------------------------------------------------

### 🌿 Branches no Git

**Branches** são ramificações do código que permitem desenvolver novas
funcionalidades sem afetar a versão principal do projeto.

Estrutura comum:

**main (ou master)** - contém a versão estável do software.

**develop** - integra novas funcionalidades antes de entrar na versão
principal.

**feature branches** - criadas para desenvolver funcionalidades
específicas.

**hotfix branches** - utilizadas para correções urgentes em produção.

Esse modelo permite **desenvolvimento paralelo seguro**.

------------------------------------------------------------------------

### 🔀 Merge e Conflitos

**Merge** é o processo de integração entre branches.

Durante o merge podem ocorrer **conflitos**, quando duas alterações
modificam a mesma parte do código.

Boas práticas para evitar problemas:

-   atualizar a branch antes de realizar merge;
-   resolver conflitos manualmente com cuidado;
-   manter commits pequenos e frequentes;
-   utilizar mensagens de commit claras e descritivas.

------------------------------------------------------------------------

### 🚀 Deploy de Aplicações

**Deploy** é o processo de **publicar uma aplicação para que usuários
possam acessá-la**.

Ele conecta o desenvolvimento ao ambiente real de uso.

Ambientes típicos:

**Desenvolvimento** - ambiente local do programador - erros são
esperados e fazem parte do processo.

**Staging** - ambiente de testes semelhante à produção.

**Produção** - versão final acessada pelos usuários.

Etapas comuns de deploy:

1.  compilação do código
2.  configuração do ambiente
3.  execução de testes
4.  publicação da aplicação

------------------------------------------------------------------------

### ☁️ Deploy com Vercel

**Vercel** é uma plataforma moderna para hospedagem e deploy de
aplicações web.

Principais características:

-   integração automática com repositórios Git
-   deploy automático a cada push
-   suporte a frameworks modernos (React, Next.js, Vue)
-   CDN global para alta performance
-   deploys rápidos e rollback de versões
-   suporte a **serverless functions**

Isso facilita a publicação rápida e escalável de aplicações web.

------------------------------------------------------------------------

## 📌 Atividade da Aula

A atividade prática consistiu em:

1.  Criar um repositório no GitHub.
2.  Desenvolver um projeto simples (ex: página HTML básica).
3.  Versionar o código utilizando Git.
4.  Criar **tags para marcar versões estáveis**.
5.  Conectar o repositório ao **Vercel**.
6.  Realizar o **deploy da aplicação**.
7.  Documentar todo o processo incluindo:
    -   justificativas de design;
    -   prints das telas;
    -   link do repositório no GitHub;
    -   link do site publicado.

> 🔗 **Projeto concluído:** O link do repositório é [https://github.com/tav0dev/fish-academy](https://github.com/tav0dev/fish-academy). Toda a documentação do processo e o link do site publicado estão disponíveis neste repositório!

------------------------------------------------------------------------

## ✅ Conclusão

A aula 03 apresentou os fundamentos de **controle de versão e publicação
de aplicações web**, destacando o papel do Git na organização do
desenvolvimento colaborativo. Além disso, demonstrou como ferramentas
modernas de deploy, como o Vercel, permitem transformar rapidamente um
projeto local em uma aplicação acessível online, reforçando práticas
essenciais do fluxo profissional de desenvolvimento de software.
