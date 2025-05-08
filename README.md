# 🎉 Chá do Noah 💙

Este projeto foi desenvolvido para celebrar a chegada do Noah, com um convite virtual interativo, bonito e funcional! 
Tudo utilizando tecnologias gratuitas e acessíveis.

## ✨ Sobre o projeto

Um site simples e responsivo de convite de chá de bebê, hospedado via **GitHub Pages**, com recursos como:

- 🎨 Tela de boas-vindas animada
- 📋 Formulário de confirmação de presença (nome, celular e acompanhantes)
- 🕒 Contagem regressiva para o evento
- 📍 Mapa com a localização
- 🎶 Música de fundo com botão de controle
- 🎁 Sugestão de presentes e observações (com direito a open cooler 😄)

## 🚀 Tecnologias utilizadas

- **HTML5** e **CSS3** para estrutura e estilo
- **JavaScript (puro)** para interatividade
- **SweetAlert2** para alertas elegantes
- **AOS (Animate On Scroll)** para animações leves
- **IMask.js** para máscara de campo de celular
- **Google Apps Script + Google Sheets** para receber os dados do formulário (backend serverless)
- **GitHub Pages** para hospedagem gratuita do site

## 📦 Como funciona

1. O usuário acessa o link do convite
2. Uma tela de boas-vindas aparece com botão “Entrar”
3. A música começa a tocar e o convite é exibido com todas as informações do evento
4. O usuário preenche o formulário para confirmar presença
5. Os dados são enviados de forma segura para uma planilha do Google

## 🔐 Segurança

Foi implementada uma **chave secreta (secretKey)** na comunicação entre o front-end e o Google Apps Script para evitar acessos indesejados.  
Nenhum dado sensível é exposto no front-end ou retornado nas respostas.

## 💡 Por que esse projeto é especial?

Além de comemorar uma nova vida, esse projeto mostra como é possível usar ferramentas simples e gratuitas para criar soluções funcionais e elegantes, sem precisar de back-end complexo ou infraestrutura paga.

----------------------------------------------------

Se você quiser adaptar esse modelo para seu próprio evento ou outro uso, fique à vontade! 😄
