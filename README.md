## ## Passos realizados para criar uma API em Node.js

# Iniciar a aplicação Node.js

yarn init -y

# Fazer a instalação do Typescript na pasta do projeto, como uma dependência de desenvolvimento.

yarn add typescript ts-node-dev @types/node -D

# Criar o arquivo "tsconfig.json" que conterá as configurações do Typescript, com o comando:

npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true

# Instalação do ESLint no projeto:

yarn add -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin

# Instalação e Configuração do Prettier:

yarn add prettier -D

# Configurando o Prettier para trabalhar com ESLint

yarn add eslint-config-prettier@6.15.0 eslint-plugin-prettier@3.2.0 -D

# tsconfig-paths

yarn add -D tsconfig-paths

# INSTALAÇÃO DAS LIBS

yarn add express cors express-async-errors
yarn add -D @types/express @types/cors

# Banco de dados

yarn add typeorm reflect-metadata pg

....

# Como funciona o multer ?

- O multer é uma lib que permite o usuário ...
  Após a instalação é necessário criar um arquivo de configuração para informar ao multer qual será o diretório para guardar as imagens enviadas ao servidor etc.
