#  miniredesocial
Marcos Pereira

Criando uma mini rede social em tempo real com a plataforma NodeJS.

A aplicação é uma mini rede social chamada de RAMBook, onde será possível criar posts, comentá-los e curti-los em tempo real, porém, cujos dados não serão persistidos em uma base de dados ou sistema de arquivos.

Devido a essa característica de não persistir os dados, qualquer usuário poderá se conectar à mini rede social sem precisar se autenticar, e sempre que um novo usuário entrar, será exibida a sua timeline vazia, um campo de texto para criar novos posts e a lista de usuários conectados

Na camada cliente, serão utilizadas as seguintes ferramentas:

    Twitter Bootstrap;
    RequireJS;
    MustacheJS;
    Bower.


Na camada server do NodeJS utilizaremos:

    Socket.IO;
    ExpressJS;
    Nodemon.

Baixando as dependências do backend.
   npm install Socket.IO
   npm install express
   npm install nodemon -g
   npm install bower -g
Baixando as dependências da camada client
  bower install jquery
  bower install bootstrap
  bower install mustache
  bower install requirejs



Para executar a aplicação vai para o diretorio raiz e execute o comando nodemon index.js
http://localhost:9000

Se você abrir uma nova aba em seu browser e acessar a aplicação, poderá logar com um usuário de nome diferente e verá dois usuários conectados à mini rede social, com isso voce verá o que cada usuários posta podendo curtir e descurtir os comentários.Você poderá notar que as informações estarão atualizadas em tempo real em ambas as abas do browser.






