# Cardápio Digital

Este projeto é um protótipo de um **Cardápio Digital**, composto por duas partes:
1. **Frontend** - Desenvolvido com **React** e **TypeScript**.
2. **Backend** - Construído com **Java Spring** e **Spring MVC**.

## 🖥️ Frontend

### Tecnologias Utilizadas
- **React** para a interface de usuário.
- **TypeScript** para a tipagem estática e melhorias no desenvolvimento.
- **React Query** para o gerenciamento de estados assíncronos.

<h2 align="center">
    <img src="./public/home.png" width="300"/>
    <img src="./public/modal.png" width="300"/>
</h2>

### 💻 Requisitos
Antes de começar, certifique-se de ter instalado:
- **Node.js** 
- **NPM** (gerenciador de pacotes do Node)

### 🚀 Instalando o Frontend

1. Clone o repositório do frontend:
    ```bash
    git clone git@github.com:vvc-git/cardapio-digital-frontend.git
    cd frontend-cardapio
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute o projeto:
    ```bash
    npm run dev
    ```

### 🔧 Compilando para Produção

Para gerar uma versão otimizada da aplicação:

```bash
npm run build
```
Isso irá gerar uma versão otimizada da aplicação na pasta `dist`.

# 💻 Backend

Essa aplicação foi desenvolvida utilizando:
- **Java Spring** e **Spring MVC** para criação do servidor.
- **Spring Data JPA** para manipulação e persistência de dados.
- **Lombok** para geração de boilerplates.
- **Postgres Driver** para realizar a conexão com banco de dados PostgreSQL.

## 💻 Requisitos

Para rodar esse projeto, você precisa ter o **Java** instalado em sua máquina.

## 🚀 Instalando o projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/fernandakipper/crud-java-back
    cd crud-java-back
    ```

2. Abra o projeto no **IntelliJ IDEA** e instale as dependências com o **Maven**.

    <img width="300px" src="./.github/instalar-deps.png">

3. Navegue até o arquivo da classe `CardapioApplication` para executar o projeto.

    <img width="300px" src="./.github/executar.png">
