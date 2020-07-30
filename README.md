#  <img  width='30' src='https://uploads-ssl.webflow.com/5e790d30d198385b09366d8f/5efbb5055f2478ba2bc322d0_icone_gif.gif'> Labenu | Full-Stack Web Development Bootcamp
Desenvolvimento de aplicações completas, incluindo frontend Web com React e backend com Node.js.
<br><br>

## Projeto: 4eddit

[Site do projeto](http://milky-scent.surge.sh/)
<br>
**Desenvolvido por:** [Milene Taborda](https://www.linkedin.com/in/milene-taborda/) e Gabriela Salvo.
<br><br>


### Escopo do projeto
Implementar uma rede social com cadastro, login, posts, likes e comentários. Para isso, iremos nos basear no reddit.com.


[Documentação da API 4eddit](https://documenter.getpostman.com/view/674905/SzYXXKEE?version=latest#08adf102-4d87-4f70-9dc3-b3c321b29739)
<br><br>


#### Requisitos obrigatórios

A rede social terá 4 páginas:
<br>
- Página de login: A página de login possui dois campos de texto: email e senha. O comportamento será o mesmo da página de login feita semana passada. Ao fazer o login, o usuário deverá ser redirecionado para a página de feed. A página possui também um botão "Cadastrar", que leva o usuário para a página de cadastro. <br>

- Página de cadastro: A página de cadastro possui 3 campos: nome de usuário, email e senha. O endpoint de cadastro retornará as mesmas informações do endpoint de login. Portanto, após cadastrar, o usuário deverá ser redirecionado para a página de feed, já estando logado (ou seja, com o token salvo no LocalStorage).<br>

- Página de feed (lista de posts): A página de feed deverá mostrar todos os posts, além de um formulário para a criação de post. O formulário possui apenas o campo de texto. Cada post mostrará o nome de usuário que postou, o texto do post, o número de votos (positivo ou negativo) e o número de comentários. Caso o usuário tenha votado positiva ou negativamente, isso deverá estar indicado. Todas essa informações serão fornecidas pela API. Quando o usuário clicar em um post, ele deverá ser redirecionado para a página do respectivo post. Quando um usuário clicar em votar (positiva ou negativamente), uma requisição deverá ser feita indicando a "direção" do voto. Um voto positivo é indicado com o número 1. Um voto negativo é indicado com o número -1. Para remover um voto, a direção deve ser 0. Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login. <br>

- Página de post: A página de um post mostrará o mesmo card de post da página de feed, com o usuário, texto, curtidas e número de comentários. Abaixo, terá um formulário para criação de comentários e os cards de comentários. A estrutura é muito similar à do post, mas comentários não possuem outros comentários dentro deles. A lógica de votos é a mesma do post. Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.
<br>

## Principais tecnologias/ferramentas utilizadas

1. React
2. Redux
3. Redux-Thunk: Integração do redux com requisições assíncronas.
4. Autenticação
5. Estilização Avançada com CSS
6. Uso de bibliotecas de UI (MaterialUI)
7. Aplicações com múltiplas rotas utilizando React Router
8. Formulários com Validação
9. Responsividade e adaptação de aplicação web para front.
<br><br>

## Como rodar a aplicação

No terminal, clone o projeto:
```
git clone 
```

Entre na pasta do projeto:
```
cd 4eddit
```

Instale as dependências:
```
npm install
```

Execute a aplicação:
```
npm start 
```

<br>
