# Github Explorer

![Preview-Screens](https://github.com/andrewmatheus/github_explorer/blob/master/github%20explorer.jpg)


## About this Project

**Github Explorer**, *busca através da [api-github](https://api.github.com/), o repositório pesquisado na aplicação*.

## Functionalities

- Dashboard
  - Visualizar lista de repositórios
  - Campo de pesquisa

  - Botão pesquisar:
    - Pesquisa repositório na api do github e salva as informações no **localStorage**

  - Ação ao clicar nos repositórios listados:
    - Navega para página repositórios, contendo detalhes do _repositório selecionado_

- Página repositório:
  - Visualiza os detalhes do repositório
  - Permite visualizar últimas issues do repositório

  - Ação ao clicar numa issue listada:
    - ao selecionar uma issue, é direcionado direto para o github do mesmo

- Validações de pesquisa
  - Valida se campo de pesquisa está preenchido
  - Valida se repositório realmente existe

## Getting Started

### Prerequisites

[yarn](https://yarnpkg.com/)

### Installing

**Cloning the Repository**

```
$ git clone https://github.com/andrewmatheus/github_explorer.git

$ cd github_explorer
```

**Installing dependencies**

```
$ yarn
```

### Running

> Localhost
```
$ yarn start
```

## Built With

- [Axios](https://github.com/axios/axios) - HTTP Client
- [ESlint](https://eslint.org/) - Linter
- [Prettier](https://prettier.io/) - Code Formatter
- [Babel](https://babeljs.io/) - JavaScript Compiler
- [Styled-Components](https://www.styled-components.com/) - Styles
- [React-Router-Dom](https://reacttraining.com/react-router/web/guides/quick-start) - Roteamento
- [React Icons](https://react-icons.netlify.app/) - Pacote de icons do React

## Contacts

Email: andrewmatheus@gmail.com

Connect with me at [LinkedIn](https://www.linkedin.com/in/andrew-cabral-developer/).

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/steniowagner/mindCast/blob/master/LICENSE) file for details

