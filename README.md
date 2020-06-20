<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Solução desafio 04: Conceitos do React Native
</h3>

<blockquote align="center"><a href="https://github.com/Rocketseat/gostack-template-conceitos-react-native">Template para iniciar o desafio</a></blockquote>

  
  
<p align="center">
 <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/jonascastro/conceitos-react-native?color=%2304D361">
  
  <a href="https://www.linkedin.com/in/jonas-castro-b4044111a/">
    <img alt="Made by JonasCastro" src="https://img.shields.io/badge/made%20by-JonasCastro-blue">
  </a>
  
  <a href="https://rocketseat.com.br">
    <img alt="Template by Rocketseat" src="https://img.shields.io/badge/Template%20by-Rocketseat-%2304D361">
  </a>
 
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#funcionalidades-da-aplicação">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#checkered_flag-execute-o-projeto-localmente">Execute o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#testes-da-aplicação">Testes da aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, foi criado uma aplicação para treinar os conceitos de React Native!

Essa é a continuação da aplicação que armazena repositórios de portfólio, com <a href="https://github.com/JonasCastro/conceitos-nodejs">backend</a> utilizando o Node.js, e <a href="https://github.com/JonasCastro/conceitos-reactjs">front</a> com ReactJS.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a> com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item da <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a> através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Testes da aplicação

Em cada teste, tem uma breve descrição no que a aplicação deve cumprir para que o teste passe.

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

### :checkered_flag: Execute o projeto localmente:

```bash
# Clone este repositório
$ git clone https://github.com/JonasCastro/conceitos-react-native.git

# Acesse a pasta do projeto no terminal/cmd
$ cd conceitos-react-native

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
# Caso esteja EMULANDO VIA USB 
$ yarn start
$ yarn android


# Para executar os testes da aplicação
$ yarn test
 
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

- Feito com :blue_heart: by Jonas Castro :wave: [Stay in touch!](https://www.linkedin.com/in/jonas-castro-b4044111a/)
- Desafio feito com 💜 by Rocketseat :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)
