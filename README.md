
Food Explorer - Rocketseat 
Este é o resultado do desafio final do Explorer, o Food Explorer.
Nele realizei a criação do FrontEnd e do BackEnd completo da aplicação.

ℹ️ Sobre
O Food Explorer é uma aplicação web de um restaurante. Após se cadastrar na plataforma, você estará apto a criar os pedidos e acompanhar o status deles. Há ainda uma personalização de perfil, filtragem de favoritos, campo de busca e uma seção de contato com o restaurante. O carrinho é 100% funcional e você pode escolher entre 2 formas de pagamento (cartão ou Pix). O administrador tem a capacidade de criar, editar e remover os pratos de acordo com a sua preferência. Além disso, ele pode alterar o status dos pedidos, de acordo com a linha de preparo dos mesmos na cozinha. Esse status será imediatamente atualizado na tela dos consumidores. O projeto conta com diversos "extras" que adicionei, como a possibilidade de mudança de tema da página e customização do perfil do usuário (avatar, nome e senha). Além disso, possui diversos efeitos visuais e é responsivo para a utilização em diversos tipos de dispositivos!

🎨 Layout
A página inicial em formato desktop é vista na imagem abaixo:

foodexplorer

⚙️ Tecnologias
As seguintes tecnologias foram empregadas na criação deste projeto:

ReactJs
Node.js
Javascript
Vite
Express
Nodemon
SQLite
Knex
BCryptjs
JSON Web Token
Multer
CORS
Axios
Styled Components
React Icons
Swiper
React Router Dom
🚀 Como utilizar
Clone o projeto para o local desejado em seu computador.

ruby
Copy code
$ git clone git@github.com:albertoscholzFood-Explorer.git
🛠️ Executando o BackEnd

No BackEnd, insira uma porta e um secret no arquivo .env vazio:
makefile
Copy code
AUTH_SECRET=
PORT=
Navegue até o diretório do BackEnd:
shell
Copy code
$ cd food-explorer-backend
Instale as dependências necessárias:
ruby
Copy code
$ npm install
Inicie o servidor do BackEnd:
arduino
Copy code
$ npm run dev
💻 Executando o FrontEnd

Navegue até o diretório do FrontEnd:
shell
Copy code
$ cd food-explorer-frontend
Instale as dependências necessárias:
ruby
Copy code
$ npm install
Inicie o servidor do FrontEnd:
arduino
Copy code
$ npm run dev
O terminal exibirá o endereço local onde a aplicação está sendo executada. Basta digitar o mesmo endereço em seu navegador preferido. O endereço usado na criação do projeto foi este:
arduino
Copy code
http://localhost:5173/
🔑 Quer ver como a aplicação funciona vista pelo Admin? Use a conta a seguir:

E-mail: admin@foodexplorer.com
Senha: 123456
Este BackEnd foi hospedado diretamente no Render. Já o Frontend foi hospedado diretamente no Netlify.

Obs.: Por estar hospedado em um serviço gratuito, o BackEnd
