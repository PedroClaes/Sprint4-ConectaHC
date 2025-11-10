# 🏥 **ConectaHC**  
> Sistema web de gerenciamento de pacientes e consultas – *Sprint 4 – FIAP*

---

## 🧠 **Descrição do Projeto**

O **ConectaHC** é uma aplicação web desenvolvida para facilitar o gerenciamento de **pacientes** e **consultas** em clínicas médicas.  
O sistema oferece uma **API RESTful em Java (Spring Boot)** e uma **interface moderna em React**, conectadas ao **banco Oracle da FIAP**.

O projeto integra **frontend**, **backend** e **banco de dados** com **deploy completo em nuvem** (Render + Vercel).  

---

## 🛠️ **Tecnologias Utilizadas**

### **Frontend**
- ⚛️ React + Vite  
- 🎨 TailwindCSS  
- 🌐 Axios (requisições HTTP)  
- 🧱 React Router DOM  

### **Backend**
- ☕ Java 17  
- 🧩 Spring Boot  
- 🗄️ Oracle Database (FIAP Cloud)  
- 🐳 Docker (para deploy no Render)  

### **Infraestrutura**
- ☁️ **Render** → Deploy do backend  
- 🚀 **Vercel** → Deploy do frontend  
- 🧰 GitHub → Versionamento e colaboração  

---

## 👥 **Integrantes**

| Nome | RM | Turma |
|------|----|--------|
| Artur Pioli | RM565597 | 1TDSPV |
| Pedro Gabriel | RM566058 | 1TDSPV |

---

## 🧩 **Estrutura de Pastas (Frontend)**

Sprint4-ConectaHC/
│
├── public/ # Ícones e imagens públicas
├── src/
│ ├── assets/ # Imagens e logos usados no projeto
│ ├── components/ # Componentes reutilizáveis (botões, cards, tabelas, etc)
│ ├── pages/ # Páginas principais (Pacientes, Consultas, Home, etc)
│ ├── services/ # Arquivos de integração com a API (Axios)
│ ├── App.jsx # Componente raiz da aplicação
│ └── main.jsx # Ponto de entrada da aplicação React
│
├── .env # Variáveis de ambiente (API base URL)
├── package.json # Dependências e scripts
└── README.md # Documentação do projeto

yaml
Copiar código

---

## 🖼️ **Imagens do Projeto**

### 💻 Tela Inicial
![Tela inicial do ConectaHC](https://i.imgur.com/Z4G6w0Z.png)

### 👩‍⚕️ Tela de Pacientes
![Listagem de pacientes](https://i.imgur.com/xvtu6LD.png)

*(Imagens ilustrativas — substitua pelas prints reais do seu projeto!)*

---

## 🔗 **Links Importantes**

- 🧭 **Repositório no GitHub:**  
  👉 [https://github.com/PedroClaes/Sprint4-ConectaHC](https://github.com/PedroClaes/Sprint4-ConectaHC)

- ⚙️ **Deploy da API (Render):**  
  👉 [https://sprint4-q8od.onrender.com/conectahc/api](https://sprint4-q8od.onrender.com/conectahc/api)

- 🌐 **Deploy do Frontend (Vercel):**  
  👉 [https://conectahc.vercel.app](https://conectahc.vercel.app)

- 🎥 **Vídeo de Apresentação (YouTube):**  
  👉 _(adicionar link do vídeo aqui)_

---

## 🚀 **Como Executar o Projeto Localmente**

### 🔧 **Backend**
```bash
# Clonar repositório
git clone https://github.com/poiuytrewq01/sprint4.git
cd sprint4

# Rodar o projeto (IDE ou terminal)
mvn spring-boot:run
A API ficará disponível em http://localhost:8080/conectahc/api

💻 Frontend
bash
Copiar código
# Clonar repositório
git clone https://github.com/PedroClaes/Sprint4-ConectaHC.git
cd Sprint4-ConectaHC

# Criar arquivo .env
VITE_API_BASE_URL=https://sprint4-q8od.onrender.com/conectahc/api

# Instalar dependências e rodar
npm install
npm run dev
Acesse em http://localhost:5173

🧾 Objetivo Acadêmico
Este projeto foi desenvolvido como parte da Sprint 4 do curso Análise e Desenvolvimento de Sistemas (FIAP),
disciplina Advanced Business Development with .NET & Java.

O objetivo é demonstrar a integração completa entre:

Frontend em React

Backend em Java Spring Boot

Banco de dados Oracle

Deploy em nuvem

💬 Autores
© 2025 – ConectaHC
Desenvolvido por Artut Pioli e Pedro Gabriel – FIAP