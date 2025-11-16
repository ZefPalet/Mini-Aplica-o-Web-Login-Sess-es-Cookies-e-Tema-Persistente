🟦 Título do Projeto

Mini Aplicação Web – Login, Sessões, Cookies e Tema Persistente

📝 Descrição Geral do Projeto (para portfólio)

Este projeto é uma mini aplicação web desenvolvida com HTML, CSS e JavaScript puro, criada para demonstrar conceitos essenciais de autenticação simples, gerenciamento de sessões, uso de cookies e práticas básicas de segurança em aplicações front-end.

Ele simula uma área autenticada, onde o usuário realiza login, tem suas informações armazenadas temporariamente na sessão e pode personalizar o tema da interface (claro/escuro), com a preferência sendo mantida mesmo após recarregar a página.

O objetivo é mostrar domínio de manipulação do DOM, validação de formulários, controle de acesso e persistência de dados no navegador, sem utilizar frameworks nem backend.

🧪 Objetivos de Aprendizado

Aplicar validações reais em formulários.

Criar e gerenciar sessões usando sessionStorage.

Gravar preferências do usuário com cookies.

Implementar proteção de rota no front-end.

Desenvolver uma UI simples, funcional e responsiva com HTML e CSS.

Tratar fluxo de logout e limpeza de dados persistidos.

⚙️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript puro (Vanilla JS)

sessionStorage

Cookies

Boas práticas de segurança no front-end

🚀 Principais Funcionalidades
✔️ 1. Tela de Login com Validação Real

Validação de email com regex

Senha mínima de 6 caracteres

Impede envio com campos vazios

Salva a “sessão” no sessionStorage

✔️ 2. Área Autenticada com Proteção de Rota

Se não existir sessionStorage.email, o usuário é redirecionado para o login

Exibe o email do usuário logado

Separa logicamente página pública e privada

✔️ 3. Sistema de Tema com Cookies

Botões para escolher tema claro ou escuro

Preferência salva em um cookie que dura 1 ano

Tema reaplicado automaticamente ao recarregar a página

✔️ 4. Logout Completo

Limpa sessionStorage

Apaga cookies

Redireciona para a tela de login

🧰 Arquitetura do Projeto

index.html — tela de login

pagina-logada.html — tela protegida com sistema de tema

style.css — estilos gerais, temas e layout

script.js — validações, sessões, cookies e lógica principal

📦 Resultado Final

Uma aplicação estática, leve, objetiva e pronta para deploy em GitHub Pages, Netlify ou Vercel.
