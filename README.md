## 👨‍💻 Autor

<div align="center">
  <img src="https://avatars.githubusercontent.com/ninomiquelino" width="100" height="100" style="border-radius: 50%">
  <br>
  <strong>Onivaldo Miquelino</strong>
  <br>
  <a href="https://github.com/ninomiquelino">@ninomiquelino</a>
</div>

---

# 📲 Gerador Dinâmico de QR Codes (vCard, PIX, Wi-Fi)

![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white)
![License MIT](https://img.shields.io/badge/License-MIT-green)
![Status Stable](https://img.shields.io/badge/Status-Stable-success)
![Version 1.0.0](https://img.shields.io/badge/Version-1.0.0-blue)
![GitHub stars](https://img.shields.io/github/stars/NinoMiquelino/qr-code-generator-js?style=social)
![GitHub forks](https://img.shields.io/github/forks/NinoMiquelino/qr-code-generator-js?style=social)
![GitHub issues](https://img.shields.io/github/issues/NinoMiquelino/qr-code-generator-js)

Este projeto é uma ferramenta web de código aberto para criação de QR Codes altamente personalizados. Foi desenvolvido com foco total na usabilidade e na capacidade de adaptação dos campos de entrada, garantindo a formatação correta dos dados para serviços complexos como PIX, vCard e conexões Wi-Fi. A solução é inteiramente executada no lado do cliente (browser), utilizando uma API pública para a geração da imagem.

---

## ✨ Destaques do Projeto
 * Formulário Adaptativo: O JavaScript manipula o DOM para injetar apenas os campos necessários (ex: SSID e Senha para Wi-Fi, ou Nome e Telefone para vCard), simplificando a interface para o usuário.
 * Formatadores de Dados Complexos: Lógica avançada para formatar strings de dados complexos (como BEGIN:VCARD ou WIFI:T:WPA;...) no padrão exigido pelo QR Code.
 * Client-Side Only: Solução leve e rápida, sem necessidade de backend. Toda a lógica de interação e formatação é feita em JavaScript puro, aumentando a performance.
 * Download Assíncrono: Utiliza fetch para converter a imagem QR Code da API em um Blob, permitindo o download direto da imagem em formato PNG, sem abrir novas abas.

---

## 🧠 Tecnologias utilizadas
 * Frontend: HTML5, JavaScript Vanilla (Manipulação do DOM, fetch API), Tailwind CSS (CDN).
 * API Externa: api.qrserver.com (API de geração de QR Code).

---

## 🧩 Estrutura do Projeto

```
qr-code-generator-js/
├── index.html    
└── README.md
```

---

## ⚙️ Configuração e Instalação

Pré-requisitos
Nenhum pré-requisito especial. O projeto é executado inteiramente no navegador.
Execução
 * Salve o código fornecido como index.html.
 * Abra o arquivo index.html diretamente em qualquer navegador web moderno.

---

## 📝 Instruções de Uso
 * Escolha o Tipo: No menu suspenso, selecione o tipo de conteúdo desejado (e.g., PIX, vCard).
 * Preencha os Campos: Os campos de entrada aparecerão dinamicamente. Preencha todos os campos obrigatórios.
 * Ajuste: (Opcional) Defina o tamanho do QR Code em pixels.
 * Gere e Baixe: Clique em "Gerar QR Code". A prévia será exibida e o botão "Baixar QR Code (PNG)" será ativado.

---

## 🤝 Contribuições
Contribuições são sempre bem-vindas!  
Sinta-se à vontade para abrir uma [*issue*](https://github.com/NinoMiquelino/qr-code-generator-js/issues) com sugestões ou enviar um [*pull request*](https://github.com/NinoMiquelino/qr-code-generator-js/pulls) com melhorias.

---

## 💬 Contato
📧 [Entre em contato pelo LinkedIn](https://www.linkedin.com/in/onivaldomiquelino/)  
💻 Desenvolvido por **Onivaldo Miquelino**

---
