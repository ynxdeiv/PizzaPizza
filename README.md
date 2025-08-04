# 🍕 PizzaPizza | PlugInfo 2025.2

Este projeto é uma aplicação web de pizzaria, criada para o processo seletivo do **PlugInfo 2025.2**. A aplicação demonstra habilidades em front-end e integração de dados, gerenciando o menu de forma dinâmica através de um **CMS headless**.

---

### 🚀 Tecnologias Utilizadas

A aplicação foi desenvolvida com as seguintes tecnologias:

* **Next.js**: Framework React para renderização do lado do servidor e otimização de performance.
* **React**: Biblioteca JavaScript para a construção da interface do usuário.
* **TypeScript**: Adiciona tipagem estática, garantindo um código mais robusto e seguro.
* **Prismic**: CMS headless utilizado para gerenciar e editar o conteúdo do menu de forma dinâmica.
* **db.json**: Usado como um banco de dados local para simular dados durante o desenvolvimento.
* **JSON Server**: Biblioteca para criar uma API REST falsa, usando o arquivo `db.json` como base.

---

### ✨ Recursos

* **Conteúdo Dinâmico**: O menu de pizzas e outras informações são carregados diretamente do Prismic. Isso permite que o conteúdo seja atualizado facilmente sem a necessidade de alterar o código.
* **Design Responsivo**: O layout do site se adapta a diferentes tamanhos de tela, garantindo uma ótima experiência de navegação em qualquer dispositivo.
* **Código Robusto**: A utilização de TypeScript oferece maior segurança e estabilidade, facilitando a manutenção e a escalabilidade do projeto.

---

### ⚙️ Como Executar o Projeto Localmente

Para rodar a aplicação em sua máquina, siga os passos abaixo:

1.  **Clone este repositório:**
    ```sh
    git clone [https://github.com/ynxdeiv/PizzaPizza](https://github.com/ynxdeiv/PizzaPizza)
    ```

2.  **Instale as dependências do projeto:**
    ```sh
    npm install
    # ou yarn install
    ```

3.  **Inicie o servidor de desenvolvimento e o JSON Server:**
    ```sh
    npm run dev
    # e em outro terminal
    json-server --watch db.json --port 3001
    ```

4.  Abra seu navegador e acesse `http://localhost:3000` para ver o projeto em execução.
5.  O servidor de dados estará disponível em `http://localhost:3001`.
