☕Node Fundamentals
-----------------------------------------------------------

Este repositório é destinado a projetos práticos de NodeJs com a DIO.<br>
Neste readme, vou descrever as principais funcionalidades.

-----------------------------------------------------------

☕ Arquivos que compoem uma estrutura NodeJs:<br><br>
1 - Package.json<br>
2 - App.js<br>
3 - Server.js<br>
4 - logger.js<br>
5 - controller.js<br>
6 - middleware.js<br>
7 - logginServer.js<br>

-----------------------------------------------------------

☕ Iniciando Projeto Node:<br><br>
1 - npm init ( Iniciar um projeto, solicitando informações )<br>
2 - npm init-y ( Não solicita informações iniciais )<br>
3 - Package.json ( Neste arquivo, determinamos nosso arquivo principal em "Main")
  > Licença MIT é uma das mais utilizadas<br>

-----------------------------------------------------------

☕Pasta Src
1 - Todos os arquivos que ficarem dentro da pasta "src", serão os arquivos a serem codificados.<br>
2 - Arquivos fora da pasta "src" são arquivos de configuração<br>
3 - Dentro da pasta "src", criamos o nosso entry point, no caso "index.js"<br>
4 - Para executar o arquivo "index.js" é necessário apontar o caminho. Exemplo: node src/index.js<br>

-----------------------------------------------------------

☕Instalando o Nodemon para sincronização de updates
1 - No terminal , inserir o comando npm install -g nodemon<br>
2 - Acessar o "package.json" e em "scripts" inserir o exemplo "dev": "nodemon index.js"<br>
3 - Verificar o caminho correto do arquivo index.js
