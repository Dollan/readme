# Autoatendimento Newcon4
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE)

# Sobre o projeto

https://wmazoni-sds1.netlify.app

Big Game Survey é uma aplicação full stack web e mobile construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma pesquisa de preferência de games, onde os dados são coletados no app mobile, e depois são listados no app web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Dependencias

Os seguintes pacotes/softwares devem ser instalatos ou atualizados para o sistema rodar corretamente.

*Node.js [node.js](https://nodejs.org/en/).
*Android Studio [android_studio](https://developer.android.com/studio).
*React Native [react-native](https://reactnative.dev/docs/environment-setup).

seguir passo a passo do site do React Native para configurar o ambiente android e dependencias adicionas, alem disso no site eles mostram como configurar essa parte em diferentes sistemas operacionais.

# Como executar o projeto
Na pasta clonado do projeto rode o comando npm install.

```bash
npm install
```
Abra o projeto no Android studio para terminar de compilar e escolher a versão do gladle que será utilizada.

Rodar o comando do yarn abaixo.

```bash
yarn add @react-native-community/netinfo
```
Abri o arquivo run_android.sh da raiz e alterei a linha 10 para config-teste em vez de config-develop

Na pasta config que fica na raiz do projeto, criar um arquivo chamado local-config.js e copiar o codigo do local-config.example.js.

Executar a linha de comando a baixo. **mudar canopus no comando para o flavor que será testado**.

```bash
./run_android.sh canopus
```

## Modelo conceitual
![Modelo Conceitual](https://github.com/acenelio/assets/raw/main/sds1/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Wellington Mazoni de Andrade

https://www.linkedin.com/in/wmazoni

