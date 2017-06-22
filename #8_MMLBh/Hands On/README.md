Hands On
================

> IBM Watson ná prática com Tiago Valadares

Preparação do Ambiente de Desenvolvimento
-----------------------------------------


1. Criar uma conta no [IBM Bluemix](https://www.ibm.com/br-pt/marketplace/cloud-platform) com 30 dias gratuidos

2. Instale o [Node.Js](https://nodejs.org/).

[Node.Js](https://nodejs.org/en/download/ )
[Package Manager](https://nodejs.org/en/download/package-manager/ )

Após Instalação do Node.Js bem sucedida

```git clone https://github.com/watson-developer-cloud/node-red-bluemix-starter```

```cd node-red-bluemix-starter```

```npm install```

```npm start```

Você deve ter um log parecido com:
----------------------------------

Starting Node-RED on Bluemix bootstrap
Loading bluemix-settings.js
Failed to find Cloudant service: /^node-red-bluemix-watson-starter.cloudantNoSQLDB/
Loading application settings
Starting first-use setup
Waiting for first-use setup to complete

        conda install -c r r-essentials

-   Acesse http://127.0.0.1:1880
-   Next
-   Escolha a opção "Not recommended" para a instalação local apenas
-   Next em todas as outras opções até finalizar

Acesse http://127.0.0.1:1880/red! Sua instalação foi bem sucedida! Até o Meetup!

OBS: tem um bug ao rodar local pela segunda vez, o jeito mais rápido de contornar é comentar as linhas 28 e 29 do bluemix-settings.js, elas vão impedir que você use a ferramenta pela segunda vez.

Caso já queira começar a se familiarizar com o que vamos trabalhar:

https://github.com/watson-developer-cloud/node-red-labs