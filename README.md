# :rocket: Sobre o desafio

Nesse desafio foi criado uma aplicação para treinar conceitos de ReactJS!

É uma aplicação para armazenar repositórios do portfólio que já foi desenvolvido o backend no desafio anterior usando Node.js.

:arrow_right: [Acessar backend com Node.js](https://github.com/marciofrancalima/desafio-conceitos-node)

## Funcionalidades da aplicação

Caso queira ver o código para atingir os objetivos de cada funcionalidade, abra o arquivo `src/App.js`.

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

## Específicação dos testes

Em cada teste tem uma breve descrição no que a aplicação deve cumprir para que o teste passe. Os arquivos estão em `src/__tests__`.

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `<li>`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `<li>` do repositório adicionado, o item seja removido da listagem.

## :calendar: Entrega

Esse desafio foi entregue pela plataforma Skylab da Rocketseat.

## :computer: Rodar a aplicação

Caso queira rodar a aplicação, basta seguir as instruções abaixo.

**Dica**: Os testes não precisam do backend rodando, mas para ver a aplicação no navegador web, rode-o antes.

```bash
# Clone this repository
$ git clone https://github.com/marciofrancalima/desafio-conceitos-reactjs.git (or use ssh)

# Go into the repository
$ cd desafio-conceitos-reactjs

# Install dependencies
$ yarn install

# Run the tests
$ yarn test

# Run the app
$ yarn start
```

---

Made with ♥ by Márcio França Lima. [Contact me](https://www.linkedin.com/in/m%C3%A1rcio-fran%C3%A7a-lima-916454187/)
