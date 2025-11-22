# Ginástica 04 – Câmera Fullscreen com Alternância Frontal/Traseira

Este repositório contém uma página web simples e responsiva que utiliza a câmera do dispositivo (desktop ou smartphone) em **tela cheia (fullscreen)**, permitindo alternar entre a **câmera frontal** e a **câmera traseira** com apenas um clique.

Ideal para aplicações de:
- ginástica e exercícios
- análise postural
- visão computacional
- detecção de movimentos
- captura de imagem para IA
- demonstrações de câmera no navegador

---

## 🚀 Funcionalidades

- 📷 **Captura da câmera em tempo real**
- 📱 **Tela cheia (fullscreen) automática**
- 🔄 **Botão para alternar câmera frontal ↔ traseira**
- 🧭 **Indicação visual da câmera ativa**
- 🖥️ Funciona em **Android, iPhone, Windows, Mac e Linux**
- 🔒 Roda 100% no navegador, sem backend (compatível com GitHub Pages)

---

## 📸 Demonstração (GitHub Pages)

Acesse a versão online:

👉 **https://paulosergioimmersivescience.github.io/ginastica04/**

---

## 📁 Estrutura do projeto

/
├── index.html # Página principal (fullscreen + troca de câmera)
├── style.css # Estilos da interface
└── README.md # Este arquivo


---

## 🧩 Tecnologias utilizadas

- **HTML5** (elemento `<video>`)
- **CSS3** (fullscreen, sobreposições, responsividade)
- **JavaScript** (getUserMedia + controle de câmeras)
- **MediaDevices API**
- Hospedagem pelo **GitHub Pages**

---

## 🛠️ Como funciona

O JavaScript utiliza a API:

```js
navigator.mediaDevices.getUserMedia({ video: { facingMode: "user" } })

Isso permite escolher a câmera padrão (frontal) e alternar para:

facingMode: "environment"

📌 Requisitos

Browser moderno (Chrome, Firefox, Edge, Safari)

HTTPS (necessário para acesso à câmera)

Permissão de câmera habilitada


Desenvolvido por Prof. Paulo Sergio Rodrigues
📧 Email: pslucano@gmail.com

🔗 GitHub: https://github.com/PauloSergioImmersiveScience





