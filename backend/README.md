<h1 align="center">
    <img alt="Tindev" src="../.github/logo.png" />
</h1>

<h4 align="center">
  🚀 Semana OmniStack 8.0 by RocketSeat
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/guuhx97/tindev">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

## 📰 Back-end

No back-end ou API, é onde de fato as funções de cadastro, busca, login, entre outras são executadas. É responsabilidade dele também realizar a integração com bando de dados insirindo e buscando informações. Por default, a API está utilizando a porta `3333`, mas que pode ser alterada no arquivo **server.js**.


## 🌱 Rotas
| Rota | Método | Função | Descrição |
| :--- | :--- | :--- | :---|
| `/devs` | `GET` | `DevController.index` | `Busca as DEVs que estão cadastradas no Banco de dados.` |
| `/devs` | `POST` | `DevController.store` | `Cadastra um novo DEV ao sistema.` |
| `/devs/:devId/likes` | `POST` | `LikeController.store` | `Cadastrar os likes que o usuário deu.` |
| `/devs/:devId/dislike` | `POST` | `DislikeController.store` | `Cadastrar os dislikes que o usuário deu.` |

-------------------------



## 🔄 Executar
- Entrar na pasta `backend`;
 - Executar `yarn install` para instalar dependências do projeto;
 - Executar `yarn dev` para que o projeto seja executado;

 ## 📝 Licença
Este projeto está sobre a licença MIT. Veja o arquivo [LICENSE](../LICENSE.md) para mais detalhes.


---
<h4 align="center">
  Feito com ❤️ by Gustavo Souza
</h4>
