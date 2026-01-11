# 🛒 Loja Online – Projeto React (E-commerce)

## 👥 Autores
- **Tomás Noronha** — a042458  
- **Duarte Rocha** — a047439  

---

## 📌 Descrição
Este projeto consiste no desenvolvimento de uma aplicação frontend em **React** que simula uma loja online (e-commerce), consumindo uma **API REST pública**.  
O objetivo é demonstrar o uso de React, Hooks, React Router, gestão de estado global e boas práticas de organização de código.

---

## 🌐 API Utilizada

Foi utilizada a **FakeStore API**, uma API REST pública de e-commerce.

🔗 https://fakestoreapi.com

### Endpoints usados:
- `GET /products` – Listagem de produtos
- `GET /products/:id` – Detalhe de um produto específico
- `GET /products/categories` – Listagem de categorias para filtro

O consumo da API está centralizado no ficheiro:

src/services/api.js

---

## ⚙️ Tecnologias Utilizadas

- React (componentes funcionais)
- React Hooks (`useState`, `useEffect`, `useContext`, `useMemo`)
- React Router DOM
- Context API
- Vite
- JavaScript
- LocalStorage (persistência do carrinho)

---

## 📁 Organização do Projeto

src/
├── components/ # Componentes reutilizáveis (Navbar, ProductCard, CartItem)
├── pages/ # Páginas associadas às rotas (Home, ProductDetail, Cart)
├── services/ # Consumo da API
├── context/ # Context API para o carrinho
├── hooks/ # Hooks personalizados

Esta estrutura garante separação de responsabilidades e código limpo.

---

## 🛠️ Funcionalidades Implementadas

- ✅ Listagem de produtos (imagem, nome, preço)
- ✅ Página de detalhe do produto
- ✅ Filtro por categoria
- ✅ Pesquisa por nome e descrição
- ✅ Carrinho de compras:
  - Adicionar produtos
  - Remover produtos
  - Alterar quantidades
  - Cálculo de subtotal e total
- ✅ Persistência do carrinho com localStorage
- ✅ Navegação com React Router
- ✅ Gestão de estados de loading e erro
- ✅ Proteção contra dados indefinidos
- ✅ Interface simples e funcional

---

## ▶️ Instalação e Execução

### Pré-requisitos
- Node.js instalado

### Passos para correr o projeto localmente:

1. Clonar o repositório:
```bash
git clone <https://github.com/Karapuco/trabalhop-React-pweb>

```

2.  Entrar na pasta do projeto:
```bash
cd ecommerce-react

```

3.  Instalar as dependências:
```bash
npm install

```

4.  Iniciar o servidor de desenvolvimento:
```bash
npm run dev


```

5.  Abrir no browser:
```bash
http://localhost:5173

```
