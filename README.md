# To-Do List - EM MANUTENÇÃO!

Este projeto é uma aplicação completa de lista de tarefas (**To-Do List**) desenvolvida em arquitetura **Full Stack**, permitindo que usuários organizem suas atividades diárias de maneira eficiente, com interface intuitiva e API robusta.

---

## 🛠️ Tecnologias Utilizadas

### Backend

- **Node.js**  
  Plataforma JavaScript utilizada para rodar o servidor e manipular requisições de forma eficiente e escalável.

- **Express**  
  Framework para Node.js que facilita o gerenciamento de rotas, requisições, respostas e middlewares, tornando a construção da API mais simples e organizada.

- **TypeScript**  
  Linguagem baseada em JavaScript que adiciona tipagem estática, aumentando a segurança e produtividade no desenvolvimento.

- **MySQL**  
  Banco de dados relacional utilizado para armazenar as tarefas dos usuários de forma persistente e estruturada.

- **Postman**  
  Ferramenta para testar, documentar e automatizar requisições HTTP, utilizada para validar todos os endpoints da API (GET, POST, PUT, DELETE).

### Frontend

- **React**  
  Biblioteca JavaScript para construção de interfaces de usuário reativas e modulares.

- **Vite**  
  Ferramenta moderna para criação de projetos React, focada em desempenho, rapidez na inicialização e recarregamento instantâneo durante o desenvolvimento.

- **TypeScript**  
  Utilizado também no front-end para garantir maior confiabilidade, facilidade de manutenção e redução de bugs.

- **CSS**  
  Responsável pela estilização da interface, proporcionando uma experiência visual agradável e adaptável a diferentes dispositivos.

---

## 📋 Funcionalidades Principais

- Cadastro, edição e remoção de tarefas
- Cadastro e Login de usuários
- Uso de JWT(Jason Web Token) para autenticação de usuários
- Marcação de tarefas como concluídas
- Filtros para exibir tarefas pendentes ou concluídas
- Persistência das tarefas no banco de dados
- Comunicação entre front e back via API RESTful
- Testes de todos os endpoints com Postman

---

## 🚀 Como Executar o Projeto

### Backend

1. **Clone o repositório**
   ```bash
   git clone https://github.com/VINICIUS0098876/To-Do-List-Back.git
   ```
2. **Instale as dependências**
   ```bash
   npm install
   ```
3. **Configure o banco de dados MySQL**
   - Crie um banco de dados e atualize as configurações no arquivo `.env`.
4. **Inicie o servidor**
   ```bash
   npm run dev
   ```

### Frontend

1. **Clone o repositório**
   ```bash
   git clone https://github.com/VINICIUS0098876/To-Do-List-Front.git
   ```
2. **Instale as dependências**
   ```bash
   npm install
   ```
3. **Inicie a aplicação**
   ```bash
   npm run dev
   ```
4. **Acesse no navegador**
   ```
   http://localhost:5173
   ```

---

## 📦 Estrutura das Pastas

### Backend
```
src/
  ├── controllers/
  ├── models/
  ├── routes/
  ├── services/
  ├── config/
  ├── app.ts
  └── server.ts
```
### Frontend
```
src/
  ├── components/
  ├── pages/
  ├── services/
  ├── styles/
  ├── App.tsx
  └── main.tsx
```

---

## 💡 Como Contribuir

1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b minha-feature`
3. Faça suas alterações e commit: `git commit -m 'feat: Minha nova feature'`
4. Envie o push para sua branch: `git push origin minha-feature`
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob licença MIT.

---

## 👨‍💻 Autor

Feito por [VINICIUS0098876](https://github.com/VINICIUS0098876) — entre em contato para dúvidas ou sugestões!

