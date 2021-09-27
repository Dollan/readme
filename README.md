# Autoatendimento Newcon4
 
# Sobre o projeto
 
## Dependências
 
Os seguintes pacotes/softwares devem ser instalados ou atualizados para o sistema rodar corretamente.
- Node.js [node.js](https://nodejs.org/en/).
- Android Studio [android_studio](https://developer.android.com/studio).
- React Native [react-native](https://reactnative.dev/docs/environment-setup).
 
seguir passo a passo do site do React Native para configurar o ambiente android e as dependências adicionais, além disso no site eles mostram como configurar essa parte em diferentes sistemas operacionais.
 
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
 
Na pasta config que fica na raiz do projeto, criar um arquivo chamado local-config.js e copiar o código do local-config.example.js.
 
Executar a linha de comando a baixo. **mudar canopus no comando para o flavor que será testado**.
 
```bash
./run_android.sh canopus
```
 
 

