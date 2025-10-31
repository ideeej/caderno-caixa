# 💻 Caderno Caixa - Frontend

O `caderno-caixa-frontend` é a interface de usuário do projeto **Caderno Caixa**. Ele oferece a experiência de **PDV (Ponto de Venda)** e **ERP (Gestão)**, sendo desenvolvido com foco em **simplicidade, flexibilidade e acessibilidade** para microempreendedores (MEI).

A interface é projetada para ser **intuitiva**, permitindo que pessoas com pouca experiência tecnológica controlem vendas, estoque e pedidos facilmente.

---

## ✨ Design e Stack Tecnológica

O design é construído para ser leve e responsivo, visando uma experiência prática, ideal para uso em tablets ou celulares (no futuro, no formato "caderno digital").

| Categoria       | Tecnologia       | Badge                                                                                                                                                                                            |
| :-------------- | :--------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Framework**   | **Vue.js**       | ![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)                                                                                             |
| **Estilização** | **HTML5 / CSS3** | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Testes**      | **Jest**         | ![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)                                                                                                   |

---

## 💡 Recursos de Interface

A interface do Caderno Caixa está sendo desenvolvida para suportar as complexidades do backend com a máxima simplicidade para o usuário:

- **Design Minimalista:** Prioriza o essencial para a venda e gestão, com foco em usabilidade.
- **Controle de Abas:** Implementação visual para gerenciar as **Múltiplas Vendas Abertas** do backend.
- **Edição Direta:** Interfaces modais no PDV que permitem a **edição rápida de preço e produto** (mediante permissão).
- **Fluxo de Pedidos:** Interface dedicada para criar, acompanhar e fechar **Pedidos** (para negócios de _delivery_ ou serviços).

---

## 🚀 Como Executar o Frontend

Este projeto requer o backend rodando para funcionar corretamente. Certifique-se de que o `caderno-caixa-backend` esteja ativo (geralmente em `http://localhost:3000`).

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/ideeej/caderno-caixa.git
    cd caderno-caixa-frontend
    ```

2.  **Instale Dependências:**

    ```bash
    npm install
    ```

3.  **Configure o Backend API:**

    - Verifique o arquivo de configuração .env e ajuste a variável `VUE_APP_API_URL` (ou similar) para o endereço do seu backend (ex: `http://localhost:3000`).

4.  **Execute o Aplicativo:**
    ```bash
    npm run dev  # ou npm run serve, dependendo da sua configuração Vue
    ```

O aplicativo estará disponível em `http://localhost:8080` (ou a porta exibida no console).

---

## 🧪 Testes

Execute os testes da interface com:

```bash
npm run test:unit
```
