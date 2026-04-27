# 🍔 Food Commerce - Plataforma de Pedido Online

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON%20Server-000000?style=for-the-badge&logo=json&logoColor=white)

Uma aplicação moderna de delivery de comida que simula a experiência completa de um e-commerce. O projeto foi desenvolvido com foco em performance, tipagem rigorosa com TypeScript e uma interface totalmente responsiva.

---

## 📸 Demonstração

| Página Principal | Carrinho e Checkout |
| :---: | :---: |
| ![Desktop Preview](public/desktop-preview.png) | ![Mobile Preview](public/mobile-preview.png) |


---

## ✨ Funcionalidades

* **Cardápio Dinâmico:** Consumo de dados via API simulada para listagem de hambúrgueres, pizzas, bebidas e sobremesas.
* **Gestão de Carrinho:** Adição, remoção e atualização de quantidades com cálculo de subtotal em tempo real.
* **Feedback Visual:** Implementação de *Skeletons* para estados de carregamento (UX).
* **Fluxo de Pagamento:** Formulário de checkout completo com validações e simulação de envio de pedido.
* **Responsividade:** Layout adaptado para dispositivos móveis e desktop.

---

## 🛠️ Tecnologias e Ferramentas

* **Framework:** React.js (Hooks e Context API)
* **Linguagem:** TypeScript (Interfaces e Tipagem Estática)
* **Estilização:** Styled Components
* **Requisições:** Axios
* **Backend (Mock):** JSON Server

---

## 🚀 Como Executar o Projeto

Este projeto utiliza uma arquitetura separada para o Frontend e para o "Banco de Dados" (JSON Server). Siga os passos abaixo:

### 1. Clonar e Instalar
```bash
git clone [https://github.com/juanndev/Plataforma-de-Pedido-Online.git](https://github.com/juanndev/Plataforma-de-Pedido-Online.git)
cd Plataforma-de-Pedido-Online
npm install
```

### 2. Configurar Variáveis de Ambiente
```bash

Crie um arquivo .env na raiz do projeto:
REACT_APP_API_BASE_URL=http://localhost:3004
```

### 3. Rodar o Banco de Dados (Terminal 1)
```bash

É necessário subir a API para que os produtos apareçam na tela:
npx json-server --watch db.json --port 3004
```
#### 4. Rodar o Frontend (Terminal 2)
```bash

Em uma nova aba do terminal, inicie a aplicação:
npm start

Acesse http://localhost:3000 para visualizar o projeto.
```
---