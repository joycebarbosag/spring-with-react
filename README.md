# Site React Estático no Spring

## Como fazer?

1. Criar um projeto React básico, com os comandos:
   - a. `npx create-react-app nome-do-seu-projeto`
   - b. Edite em `App.js` o conteúdo do seu site. Fique à vontade para criar componentes e paginações mais complexas.
   - c. Rode `npm start` para verificar no browser seu projeto React.

2. Criar um arquivo `build` do seu projeto React, com os comandos:
   - a. `npm run build`
   
   Esse comando criará, dentro do diretório do seu projeto React, uma pasta `build`. Copie todo o seu conteúdo, pois vamos utilizá-lo no Spring.

3. Colar o conteúdo da pasta `build` do React no path `/src/main/resources/static/`

4. Rode o projeto Spring e acesse a URL `http://localhost:8080/`. Você deve ver seu projeto React!

   ![image](https://github.com/user-attachments/assets/dc6ee403-81dc-4555-86c6-732857b6c053)
