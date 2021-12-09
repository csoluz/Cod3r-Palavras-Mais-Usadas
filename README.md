# Cod3r-Palavras-Mais-Usadas
Projeto desenvolvido em VueJs e Electron - Palavras mais usadas em Legendas de filmes em formato .srt

## Links Úteis

[Link da Biblioteca vuetify](https://vuetifyjs.com/en/)

## Configurando o Projeto

1o - Instalando o Vue Cliente, caso não tenha sido instalado previamente:

     C:\> sudo npm i -g @vue/cli
     
     C:\> vue   --> verifica se o vue foi instalado
    
2o - Criando um projeto Vue:

      C:\> vue create most-used-words3
      
      C:\> cd most-used-words3
      
      C:\most-used-words3> vue add vuetify  ---> adicionando vuetify (biblioteca de componente do vue)
      
      C:\most-used-words3> vue add electron-builder  ---> adicionando framework electron ao VueJs (Utilize a versão do Electron ^5.0.0)
       
      C:\most-used-words3>type package.json
     
          {
            "name": "most-used-words3",
            "version": "0.1.0",
            "private": true,
            "scripts": {
              "serve": "vue-cli-service serve",
              "build": "vue-cli-service build",
              "lint": "vue-cli-service lint",
              "electron:build": "vue-cli-service electron:build",
              "electron:serve": "vue-cli-service electron:serve",   --> servidor utilizado para desenvovimento
              "postinstall": "electron-builder install-app-deps",
              "postuninstall": "electron-builder install-app-deps"
            }, ...
            
        C:\most-used-words3>npm run electron:serve    --> inicia o servidor e abre a aplicação vue utilizando o electron
      
      
