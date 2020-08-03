# Coleta-residuos
  

<a href='https://github.com/gustavobrierre/Coleta-residuos'>
</a>

## :computer: Web Images

  <p align="center" style="border-radius:6px">
    <kbd>
    <img width="450" height="auto" src='https://github.com/gustavobrierre/Coleta-residuos/blob/master/Home.png'>    
    </kbd> 
    <kbd>
    <img width="450" height="auto" src='https://github.com/gustavobrierre/Coleta-residuos/blob/master/Cadastro.png'>    
    </kbd>
  </p>

## :iphone: Mobile Images
  
  <p align="center" style="border-radius:6px">
  <kbd>
    <img width="200" height="auto" src='https://github.com/gustavobrierre/Coleta-residuos/blob/master/Início.png'>
  </kbd>  
  <kbd>
    <img width="200" height="auto" src='https://github.com/gustavobrierre/Coleta-residuos/blob/master/Home%20(1).png'>
  </kbd>
  <kbd>
    <img width="200" height="auto" src='https://github.com/gustavobrierre/Coleta-residuos/blob/master/Detalhes.png'>
    </kbd>
  </p>
  

## :rocket: Technologies
  - [NodeJs](https://nodejs.org/en/)
  - [React](https://pt-br.reactjs.org/)
  - [React Native](https://reactnative.dev/)
  - [Expo](https://expo.io/)
  - [Knex](http://knexjs.org/)
  - [MySQL](https://www.mysql.com/)
  - [Leaflet](https://leafletjs.com/)

## :information_source: Installation

You'll need to have installed on your computer before starting the project:
[yarn](https://yarnpkg.com/getting-started), 
[NodeJs](https://nodejs.org/en/).

```bash
# Clone the repository
$ git clone https://github.com/gustavobrierre/Coleta-residuos.git
```
 
### Configuring the DataBase and Server
```bash
$ cd server/knexfile.ts
$ cd server/src/database/connection.ts
```
 Change the password '******' in those two files to be your database password .

### :computer: API
```bash
# Go to server directory
$ cd server

# To install the dependencies
$ yarn install

# Create the DataBase
$ yarn knex:migrate
$ yarn knex:seed

# Run the server
$ yarn dev
```
### :computer: Web 
 ```bash
# Go to web directory
$ cd web

# To install the dependencies
$ yarn install

# Run the web application
$ yarn start
```

### :iphone: Mobile 
For this part, it's recommend to install Expo on your cellphone and use it. But you can also use a Android/IOS simulator.
 ```bash
# Go to mobile directory
$ cd mobile

# To install the dependencies
$ yarn install

# Run the mobile application
$ yarn start
```
