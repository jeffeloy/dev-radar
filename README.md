# DevRadar
> Aplicação desenvolvida durante a Semana Ominstack 10.0 da RocketSeat.

A aplicação consiste no cadastro de desenvolvedores utilizando a api do Github para obter algumas informações destes. E também utiliza funcionalidades do browser para obter dados de geolocalização dos devs cadastrados. Os dados da localização dos devs são usados no app mobile.

### Aplicação Web
![](https://github.com/Jeffer5504/DevRadar/blob/master/DevRadar.gif)

### Aplicação Mobile
![](https://github.com/Jeffer5504/DevRadar/blob/master/Mobile.gif)
# Funcionamento da API do github

A funcionalidade é bem simples basta solicitar na url abaixo no local do username o seu username que como resultado terar um JSON com os dados como podemos ver no no exemplo do [link](https://api.github.com/users/Jeffer5504).

```
  https://api.github.com/users/username
 ```
 ## 👨🏼‍💻 Desenvolvedor 

- [Jefferson Eloy](https://www.linkedin.com/in/jefferson-eloy-6321a81a8/)

 
# Tecnologias Utilizadas
- [Node.js](https://nodejs.org/en/) BackEnd
- [React](https://reactjs.org) FrontEnd
- [React Native](https://facebook.github.io/react-native/) Mobile
- [Expo](https://expo.io/) Mobile
- [MongoDB](https://www.mongodb.com) Banco de Dados

## Como usar
1. Faça um clone desse repositório;
2. Entre na pasta `cd DevRadar`;

## Backend
1. Entre na pasta `cd backend`;
2. Rode `yarn` para instalar as dependências;
3. Rode `yarn dev` para iniciar o servidor.

## Frontend 
1. Entre na pasta `cd frontend/web`
2. Rode `yarn` para instalar as dependências;
3. Rode `yarn start` para iniciar a aplicação;

## Padrões de commit

- Usar modo imperativo ("Adiciona feature" não "Adicionando feature" ou "Adicionada feature")
- Primeira linha deve ter no máximo 70 caracteres
- Considere descrever com detalhes no corpo do commit
- Obrigatório usar um emoji no início da mensagem de commit

| Emoji          | Código           | Tipo do commit                                |
| -------------- | ---------------- | --------------------------------------------- |
| :tada:         | `:tada:`         | initial commit                                |
| :art:          | `:art:`          | quando melhorar a estrutura/formato do código |
| :racehorse:    | `:racehorse:`    | quando melhorar a performance                 |
| :memo:         | `:memo:`         | quando escrever alguma documentação           |
| :bug:          | `:bug:`          | quando corrigir um bug                        |
| :fire:         | `:fire:`         | quando remover código ou arquivos             |
| :lock:         | `:lock:`         | quando melhorar a segurança                   |
| :poop:         | `:poop:`         | deprecated                                    |
| :construction: | `:construction:` | em construção                                 |
| :sparkles:     | `:sparkles:`     | nova feature                                  |
| :see_no_evil:  | `:see_no_evil:`  | gambiarra                                     |
| :gift:         | `:gift:`         | nova versão                                   |

### Exemplo

```bash
git commit -m ":memo: Adiciona instruções de contribuição
>
> Foi criado o arquivo README.md com as instruções de
> como fazer um bom commit
```
