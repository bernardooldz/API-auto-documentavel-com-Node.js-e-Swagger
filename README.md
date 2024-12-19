# 🚀 **API RESTful com Fastify, TypeScript, Zod e Swagger UI**

Este é um projeto de **API RESTful** desenvolvido com **Fastify**, **TypeScript**, **Zod** para validação de tipos e **Swagger UI** para gerar a documentação automática da API.

---

## 📝 **Descrição**

A API foi construída para fornecer um serviço simples e eficiente de gerenciamento de usuários. Ela é **auto-documentável**, ou seja, a documentação da API é gerada automaticamente via **Swagger UI**, facilitando a interação e compreensão de como a API funciona.

---

## 🛠 **Tecnologias Utilizadas**
- **Fastify**: Framework web rápido e altamente eficiente para construir APIs RESTful.
- **TypeScript**: Linguagem que adiciona tipagem estática ao JavaScript, garantindo maior segurança e escalabilidade.
- **Zod**: Biblioteca para validação de tipos e esquemas em TypeScript.
- **Swagger UI**: Interface de documentação automática para APIs, permitindo testar os endpoints diretamente pela interface.
- **pnpm**: Gerenciador de pacotes rápido e eficiente.

---

## 📸 **Fotos do Projeto**

Abaixo estão algumas capturas de tela que mostram o funcionamento da API e da interface Swagger UI:

1. **Tela inicial da Swagger UI**  
   Aqui você pode ver a interface de documentação gerada automaticamente pela Swagger UI, que permite testar os endpoints diretamente.

   ![Swagger UI - Tela inicial](https://github.com/user-attachments/assets/6c5b4588-b210-4030-b69b-15a17d3dc2e0)


2. **Exemplo de requisição GET /users**  
   Exibe o retorno de todos os usuários cadastrados ao realizar uma requisição GET para o endpoint `/users`.

   ![GET /users](https://github.com/user-attachments/assets/96b7e07b-fe68-48ab-99f9-55124d4ae73d)


3. **Exemplo de requisição POST /users**  
   Mostra o formulário de envio de dados para criação de um novo usuário via requisição POST.

   ![POST /users](https://github.com/user-attachments/assets/81efc96a-ab16-4f9e-863d-09b493fcd707)


---

## 📡 **EndPoints Disponíveis**

- **GET /users**  
  Retorna todos os usuários cadastrados.

- **POST /users**  
  Cria um novo usuário. O corpo da requisição deve seguir o modelo definido para criação de usuários.
---

## 🔧 **Instruções de Instalação**

### 1. Clone o repositório:
```bash
git clone https://github.com/bernardooldz/api-fastify-typescript.git
```

### 2. Navegue até o diretório do projeto:
```bash
cd api-fastify-typescript
```

### 3. Instale as dependências utilizando o pnpm:
```bash
pnpm install
```

### 4. Para rodar o projeto localmente:
```bash
pnpm run dev
```

---

## 📑 **Documentação da API**

A documentação da API está disponível via **Swagger UI** e pode ser acessada no seguinte endereço:

[Documentação da API](http://localhost:3333/docs)

---

## 🤝 **Contribuições**

Contribuições são bem-vindas! Se você deseja melhorar o projeto ou corrigir algum erro, sinta-se à vontade para fazer um **fork** e enviar **pull requests**.

---

💡 **Sugestões e feedbacks são sempre bem-vindos!** 🚀
