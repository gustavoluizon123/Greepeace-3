# 🌿 Greepeace SPA

Este projeto é uma evolução do [Greepeace](https://github.com/gustavoluizon123/Greepeace) e do [Greepeace-2](https://github.com/gustavoluizon123/Greepeace-2), agora com um sistema **SPA (Single Page Application)** completo, feito em **JavaScript puro**, sem o uso de frameworks.  
O site continua com o mesmo estilo e propósito original, mas agora com **navegação instantânea**, **validação inteligente** e **máscaras automáticas** para formulários.

---

## 🚀 Funcionalidades

### 🧭 Navegação SPA
- A navegação entre páginas acontece **sem recarregar o navegador**.
- Atualiza automaticamente o **título da página** e a **URL**.
- Funciona com os **botões Voltar e Avançar** do navegador.
- Feito apenas com `fetch()`, `DOMParser()` e `history.pushState()`.

---

### 🧾 Validação de Formulário
- Validação em tempo real (ao sair do campo).
- Exibe mensagens de erro dinâmicas abaixo dos campos inválidos.
- Campos incorretos recebem `aria-invalid="true"`.
- Se houver erro → alerta de verificação.  
- Se tudo estiver certo → alerta de sucesso e o formulário é limpo.

---

### 🔢 Máscaras Automáticas
- **CPF** → `123.456.789-00`  
- **Telefone** → `(11) 98765-4321`  
- **CEP** → `12345-678`  
As máscaras são reaplicadas mesmo após mudar de página.

---

### 📅 Atualização de Ano
O rodapé (`<span id="ano">`) é atualizado automaticamente com o **ano atual**.

---

## ⚙️ Tecnologias Utilizadas
- HTML5  
- CSS3  
- JavaScript (ES6+)

---

## 🧩 Estrutura do Projeto
```bash
/
│── index.html
│── projetos.html
│── cadastro.html
│── css/
│   └── styles.css
│── js/
│   └── script.js
│── img/
│   ├── amazoniar.jpg
│   ├── expedicao.png
|   ├── Greenpeace.jpg
|   ├── proposta.jpg
|   ├── transparencia.jpg
│   └── voluntariado.jpg 
│           
└── README.md

```
<br>

## 📎 Badges

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Status](https://img.shields.io/badge/Status-Desenvolvido-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-Acad%C3%AAmico-green?style=for-the-badge)


<br>

## 📬 Contato

**Autor:** *Gustavo Luizon Camilo Victorio*

📧 Email: [gustavoluizon9cim@gmail.com](gustavoluizon9cim@gmail.com)
💼 Linkedin: [https://linkedin.com/gustavo-luizon](https://www.linkedin.com/in/gustavo-luizon-056b15344/)

> “Unindo código e consciência — desenvolvendo o futuro com propósito.” 💻🌱
