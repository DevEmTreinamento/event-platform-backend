<!-- Título -->
<h4 align="center">
  🎯 Um desafio para alavancar seus conhecimentos em Backend 🚀
</h4>
<!-- /Título -->

<!-- Badges -->
<div align="center">
  <br>

  ![Challenge](https://img.shields.io/badge/Desafio-Back--end-f1e05a)
  ![GitHub made by](https://img.shields.io/badge/Made%20By-Kaique%20Covo-ff69b4)
</div>
<!-- /Badges -->

<!-- Menu -->
<p align="center">
  <a href="#desafio">Desafio</a> •
  <a href="#contexto-do-desafio">Contexto do desafio</a> •
  <a href="#avaliação">Avaliação</a> •
  <a href="#dúvidas">Dúvidas</a>
</p>
<!-- /Menu -->


# Desafio

Eae Dev! Tudo bem?

Nesse desafio você construirá o back-end de uma plataforma de eventos


# Contexto do desafio

O objetivo desse desafio é criar uma API GraphQL que irá possibilitar a criação de eventos pelos usuários, além disso outros usuários poderão visualizar esses eventos e se inscrever neles

- Os eventos deverão ser criado com os seguintes dados:

| Atributo                |  Tipo  | Nullable |
| ----------------------- | :----: | :------: |
| id                      | number | false    |
| name                    | string | false    |
| additional_information  | string | true     |
| start_date              | Date   | false    |
| start_date_registration | Date   | false    |
| end_date_registration   | Date   | false    |
| link                    | string | false    |
| participants_limit      | number | true     |
| updated_at              | Date   | false    |
| created_at              | Date   | false    |

- Uma vez criado, os eventos deverão ser exibidos para que o usuários possam se inscrever, para isso será necessário ser criado com os seguintes dados:

| Atributo          | Tipo   | Nullable |
| ----------------- | :----: | :------: |
| event_id          | number |  false   |
| user_id           | number |  false   |
| subscription_date | Date   |  false   |

## Requisitos

### Funcionais

- O usuário deve conseguir se cadastrar na API;<br>
- O usuário deve conseguir se logar na API;<br>
- O usuário logado deve conseguir listar os eventos criados;<br>
- O usuário logado deve conseguir ciar um evento;<br>
- O usuário logado deve conseguir increver-se em um evento;<br>
- O usuário logado deve conseguir listar os eventos que está inscrito;<br>
- O usuário logado não deve conseguir inscrever-se em eventos após expiração de data ou limite de inscrição.<br>


### Não funcionais

- A API deverá ser construída usando o GraphQL;
- A tabela de usuários fica ao seu critério; 
- Os dados deverão persistir em algum DB Relacional;
- Configurar Style Guide no projeto;
- As consultas deverão ser feitas usando o seguinte header de autenticação, para isso será necessário usar o JWT:
  `Authentication: Bearer <JWT TOKEN>`;
- Escreva um README do projeto.


### Bônus

- Fazer cache das consultas de listagem dos eventos;
- Construir testes unitários da API;
- Usar o Docker para rodar o projeto;
- Fazer a hospedagem da API;


## Tecnologias

Você tem liberdade para utilizar as tecnologias que estiver confortável, mas também deixamos algumas sugestões para você:

- [Nest.js](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeORM](https://typeorm.io/)
- [Apollo Server](https://github.com/apollographql/apollo-server)
- [Jest](https://jestjs.io/pt-BR/)
- [Docker](https://www.docker.com/)
- [Redis](https://redis.io/)
- [PostgreSQL](https://www.postgresql.org/)


# Avaliação

Para que possamos avaliar o seu desafio pedimos que você abra uma `ISSUE` com o link do repositório que você criou.


# Dúvidas

Caso você tenha dúvidas, pode ser aberta uma `ISSUE` nestre repositório.

---

Made with 💚 by [Dev em treinamento](https://www.devemtreinamento.com.br) 👋