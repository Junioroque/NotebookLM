# O Poder do NotebookLM

## Objetivo

Criar uma aplicação web utilizando C#.

---

## Perguntas Utilizadas nos Prompts

1. O que é uma aplicação web?
2. Me dê um passo a passo para criar uma aplicação web usando C#.

---

## O que é uma Aplicação Web?

Uma aplicação web é um sistema de software que permite a interação entre diferentes sistemas e usuários através da internet, utilizando protocolos como HTTP ou HTTPS.

Diferente de um site estático simples, as aplicações web são dinâmicas. Isso significa que o conteúdo pode mudar com base nas informações do usuário ou em dados vindos de um banco de dados, como:

- saldo bancário;
- lista de produtos de uma pizzaria;
- informações de login;
- pedidos realizados pelo usuário.

---

## Funcionamento de uma Aplicação Web

O funcionamento de uma aplicação web baseia-se em dois pilares principais:

### Lado do Cliente (Client-side)

É a parte que roda diretamente no navegador do usuário, como Chrome ou Edge.

Tecnologias como:

- JavaScript
- Blazor WebAssembly

são utilizadas para criar interfaces interativas que podem ser atualizadas sem recarregar toda a página, como acontece nas chamadas **SPAs (Single Page Applications)**.

### Lado do Servidor (Server-side)

É onde o código é processado em um computador remoto, chamado servidor.

Tecnologias como o **ASP.NET Core** permitem:

- processar regras de negócio;
- gerenciar segurança;
- acessar bancos de dados;
- enviar respostas para o navegador do usuário.

---

## Modelos de Aplicações Web no Ecossistema .NET

### 1. MVC (Model-View-Controller)

Padrão de arquitetura que separa a aplicação em três camadas:

- **Model** → dados;
- **View** → interface visual;
- **Controller** → lógica da aplicação.

---

### 2. Razor Pages

Modelo mais simples e focado em páginas.

O código C# e o HTML são combinados para gerar conteúdo dinâmico diretamente no servidor.

---

### 3. Web API

Modelo que não possui interface visual própria.

Funciona como um “garçom” que entrega dados, geralmente em formato JSON, para outras aplicações, como:

- aplicativos mobile;
- sites em React;
- aplicações Angular.

---

### 4. Blazor

Tecnologia moderna que permite desenvolver tanto o front-end quanto o back-end utilizando apenas C#.

Em muitos casos, elimina a necessidade de utilizar JavaScript diretamente.

---
### 5. Mapa mental da aplicação
<img width="875" height="926" alt="image" src="https://github.com/user-attachments/assets/855048a8-a3e9-4ffa-a8fb-bc43f7d76772" />


# Fontes de Vídeos

- https://www.youtube.com/watch?v=-v0sfER0po8
- https://www.youtube.com/watch?v=OC6QrEf9qME
- https://www.youtube.com/watch?v=SZtfSOvRi10
- https://www.youtube.com/watch?v=2TxePNK0kc8
- https://www.youtube.com/watch?v=ji_Ew1GlExw
- https://www.youtube.com/watch?v=r6AcjjNvI8w

---

# Fontes de Sites

- https://learn.microsoft.com/pt-br/visualstudio/get-started/csharp/tutorial-aspnet-core?view=visualstudio
- https://www.reddit.com/r/dotnet/comments/v5ybbd/the_best_c_net_web_application_tech_stack/?tl=pt-br
- https://www.devmedia.com.br/crie-uma-aplicacao-completa-passo-a-passo-com-csharp-visual-studio-e-asp-net-revista-easy-net-16-parte-7/22562
- https://dotnet.microsoft.com/pt-br/apps/ai
