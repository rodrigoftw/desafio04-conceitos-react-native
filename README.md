# Desafio 04 - Conceitos React Native
<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

## :rocket: Sobre o desafio

Nesse desafio, deve-se criar uma aplicação para treinar o que foi aprendido até agora no React Native.

Agora deve-se continuar desenvolvendo a aplicação que irá armazenar repositórios de um portfólio, que já foi desenvolvido o **[backend](https://github.com/rodrigoftw/desafio02-conceitos-nodejs)** utilizando o Node.js, e no **[último desafio](https://github.com/rodrigoftw/desafio03-conceitos-reactjs)** em ReactJS.

### Funcionalidades da aplicação

Deve-se abrir o arquivo **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Em cada teste, há uma breve descrição no que a aplicação deve cumprir para que o teste passe.

Para esse desafio existe o seguinte teste:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, a aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.
