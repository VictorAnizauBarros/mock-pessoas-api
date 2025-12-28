# MockPessoas API

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON_Server-000000?style=for-the-badge&logo=json&logoColor=white)
![Faker.js](https://img.shields.io/badge/Faker.js-00D9FF?style=for-the-badge&logo=javascript&logoColor=white)

## 📋 Descrição

Este projeto é um backend simples desenvolvido como parte do curso de Programação para a Web II. Utiliza o **JSON Server** para simular uma API REST completa, fornecendo endpoints para manipulação de dados de usuários (pessoas). Os dados são gerados dinamicamente utilizando a biblioteca **Faker.js**, garantindo uma experiência realista com informações fictícias em português brasileiro.

O projeto demonstra conceitos fundamentais de desenvolvimento backend, incluindo a criação de APIs RESTful, geração de dados mock e configuração de um servidor local para testes e desenvolvimento.

## ✨ Funcionalidades

- **API REST Completa**: Suporte a operações CRUD (Create, Read, Update, Delete) para entidades de pessoas.
- **Dados Dinâmicos**: Geração automática de 50 perfis de usuários com informações realistas, incluindo nome, sobrenome, avatar, endereço e email.
- **Localização Brasileira**: Dados gerados em português brasileiro para maior relevância regional.
- **Servidor Local**: Execução em porta 3001 para fácil integração com frontends.
- **Estrutura Modular**: Código organizado com scripts de geração de dados separados.

## 🛠️ Tecnologias Utilizadas

- **[Node.js](https://nodejs.org/)**: Ambiente de execução JavaScript no servidor.
- **[JSON Server](https://github.com/typicode/json-server)**: Ferramenta para criar APIs REST mock rapidamente.
- **[Faker.js](https://fakerjs.dev/)**: Biblioteca para geração de dados falsos realistas.
- **[Lodash](https://lodash.com/)**: Utilitário para manipulação de arrays e objetos.

## 📋 Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- **Node.js** (versão 14 ou superior)
- **npm** (geralmente vem com o Node.js)

## 🚀 Instalação e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/VictorAnizauBarros/pm-II-21-03-25.git
cd pm-II-21-03-25
```

### 2. Instale as dependências

```bash
cd backend
npm install
```

### 3. Gere os dados (opcional)

Se desejar regenerar os dados mock, execute:

```bash
node generate.js
```

Este comando criará um novo arquivo `db.json` com 50 perfis de usuários aleatórios.

### 4. Inicie o servidor

```bash
npm start
```

O servidor estará rodando em `http://localhost:3001`.

## 📖 Uso da API

### Endpoints Disponíveis

A API fornece os seguintes endpoints para a entidade `peoples`:

- **GET /peoples**: Retorna todas as pessoas.
- **GET /peoples/:id**: Retorna uma pessoa específica pelo ID.
- **POST /peoples**: Cria uma nova pessoa.
- **PUT /peoples/:id**: Atualiza uma pessoa existente.
- **PATCH /peoples/:id**: Atualiza parcialmente uma pessoa.
- **DELETE /peoples/:id**: Remove uma pessoa.

### Exemplo de Resposta

```json
{
  "id": 1,
  "firstName": "João",
  "lastName": "Silva",
  "avatar": "https://avatars.githubusercontent.com/u/12345678",
  "adress": "Rua das Flores, 123",
  "email": "joao.silva@email.com"
}
```

### Testando a API

Você pode testar os endpoints usando ferramentas como:

- [Postman](https://www.postman.com/)
- [Insomnia](https://insomnia.rest/)
- [curl](https://curl.se/)

Exemplo com curl:

```bash
# Listar todas as pessoas
curl http://localhost:3001/peoples

# Obter uma pessoa específica
curl http://localhost:3001/peoples/1
```

## 📜 Scripts Disponíveis

- `npm start`: Inicia o servidor JSON Server na porta 3001.
- `node generate.js`: Gera novos dados mock e salva em `db.json`.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fork o projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença ISC. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Victor Anizau Barros**

- GitHub: [@VictorAnizauBarros](https://github.com/VictorAnizauBarros)
- LinkedIn: [Victor Hugo Anizau Barros](https://www.linkedin.com/in/victor-hugo-anizau-barros-65a775322/)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no GitHub!</content>
<parameter name="filePath">c:\Users\victo\Desktop\pm-II-21-03-25\README.md
