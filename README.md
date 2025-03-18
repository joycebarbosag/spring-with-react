# Site react stático no Spring
## Como fazer?
- 1) Criar um projeto react básico, com os comandos:
     a. npx create-react-app nome-do-seu-projeto;
     b. Edite em App.js o conteúdo do seu site. Fique à vontade para criar componentes e paginações mais complexas;
     c. Rode "npm start" para verificar no browser seu projeto react.
- 2) Criar um arquivo build do seu projeto react, com os comandos:
     a. npm run build;
     Esse comando criará, dentro do diretório do seu projeto react, uma pasta "build". Copie todo seu conteúdo, pois vamos utilizá-lo no spring.
- 3) Colar o conteúdo da pasta build do react no path /src/main/resources/static/
  4) Rode o projeto spring e acesse a url http://localhost:8080/. Você deve ver seu projeto react!

   ![image](https://github.com/user-attachments/assets/dc6ee403-81dc-4555-86c6-732857b6c053)
