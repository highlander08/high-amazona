# MERN AMAZONA

![amazona](/frontend/public/images/amazona.jpg)

# React Tutorial - Build ECommerce in 6 Hours [2022]

Welcome to my React and Node tutorial to build a fully-functional e-commerce website exactly like amazon. Open your code editor and follow me for the next hours to build an e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).

Watch it on Youtube:
[https://www.youtube.com/watch?v=CDtPMR5y0QU](https://www.youtube.com/watch?v=CDtPMR5y0QU)

## Demo Website

- 👉 Heroku : [https://mern-amazona-app.herokuapp.com](https://mern-amazona-app.herokuapp.com)

## You Will Learn

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Context API: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:basir/mern-amazona.git
$ cd mern-amazona
```

### 2. Create .env File

- duplicate .env.example in backend folder and rename it to .env

### 3. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - In .env file update MONGODB_URI=mongodb://localhost/amazona
- OR Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

### 4. Run Backend

```
$ cd backend
$ npm install
$ npm start
```

### 5. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 6. Seed Users and Products

- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 7. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

## Support

- Contact Instructor: [Basir](mailto:basir.jafarzadeh@gmail.com)

# Lessons

1. Introdução
2. Instalar Ferramentas
3. Crie o aplicativo React
4. Crie um repositório Git
5. Listar produtos
   1. criar matriz de produtos
   2. adicione imagens do produto
   3. renderizar produtos
   4. produtos de estilo
6. Adicionar roteamento de página
   1. npm i react-router-dom
   2. crie uma rota para a tela inicial
   3. crie um roteador para a tela do produto
7. Criar servidor Node.JS
   1. execute npm init na pasta raiz
   2. Atualize o tipo de conjunto package.json: módulo
   3. Adicione .js às importações
   4. npm instalar expresso
   5. crie server.js
   6. adicione o comando start como nó back-end/server.js
   7. exigir expresso
   8. Criar rota para / backend de retorno está pronto.
   9. mova o products.js do front-end para o back-end
   10. crie uma rota para /api/products
   11. devolver produtos
   12. execute npm start
8. Buscar produtos do back-end
   1. defina o proxy em package.json
   2. npm instala axios
   3. use o gancho de estado
   4. use gancho de efeito
   5. use o gancho redutor
9. Gerenciar o estado pelo gancho do redutor
   1. definir redutor
   2. atualizar dados de busca
   3. obtenha o estado de usReducer
10. Adicionar estrutura de interface do usuário de bootstrap
    1. npm install react-bootstrap bootstrap
    2. atualize o App.js
11. Criar Produto e Componente de Classificação
    1. criar componente de classificação
    2. Criar componente de produto
    3. Use o componente Classificação no componente Produto
12. Tela Criar Detalhes do Produto
    1. buscar produto do back-end
    2. crie 3 colunas para imagem, informação e ação
13. Criar Componente de Carregamento e Mensagem
    1. criar componente de carregamento
    2. use o componente giratório
    3. Criar componente de mensagem
    4. crie utils.js para definir a função getError
14. Criar contexto de reação para adicionar item ao carrinho
    1. Criar contexto de reação
    2. definir redutor
    3. criar provedor de loja
    4. implemente o gerenciador de cliques do botão adicionar ao carrinho
15. Complete Adicionar ao Carrinho
    1. verifique se existe um item no carrinho
    2. verifique a contagem em estoque no back-end
16. Tela Criar Carrinho
    1. crie 2 colunas
    2. exibir lista de itens
    3. criar coluna de ação
17. Tela Completa do Carrinho
    1. clique no manipulador para item inc/dec
    2. clique no manipulador para remover o item
    3. clique no gerenciador para finalizar a compra
18. Criar tela de login
    1. criar formulário de login
    2. adicione e-mail e senha
    3. Adicionar botão de login
19. Conecte-se ao banco de dados MongoDB
    1. criar banco de dados atlas monogodb
    2. instale o banco de dados mongodb local
    3. npm instala mangusto
    4. Conecte-se ao banco de dados mongodb
20. Produtos de Amostra de Sementes
    1. criar modelo de produto
    2. criar rota de semente
    3. use a rota em server.js
    4. produto de amostra de sementes
21. Usuários de amostras de sementes
    1. criar modelo de usuário
    2. usuários de amostras de sementes
22. Criar API de back-end de login
    1. crie uma API de login
    2. npm instala jsonwebtoken
    3. defina gerarToken
23. Tela de login completa
    1. lidar com a ação de envio
    2. salve o token na loja e no armazenamento local
    3. mostre o nome de usuário no cabeçalho
24. Criar tela de envio
    1. criar entradas de formulário
    2. lidar com salvar endereço de entrega
    3. adicione a barra do assistente de checkout
25. Criar tela de inscrição
    1. criar formulários de entrada
    2. lidar com envio
    3. crie uma API de back-end
26. Implementar a tela de seleção de método de pagamento
    1. criar formulários de entrada
    2. lidar com envio
27. Tela Criar pedido de colocação
    1. mostre os itens do carrinho, pagamento e endereço
    2. calcular o resumo do pedido
28. Implementar Ação de Encomenda
    1. lidar com a ação do pedido
    2. criar pedido criar api
29. Tela Criar Pedido
    1. crie uma API de back-end para order/:id
    2. buscar a API de pedidos no frontend
    3. mostre as informações do pedido em 2 cloumns
30. Ordem de pagamento por PayPal
    1. gerar id de cliente paypal
    2. crie uma API para retornar o ID do cliente
    3. instale react-paypal-js
    4. use o PayPalScriptProvider em index.js
    5. use usePayPalScriptReducer na tela de pedidos
    6. Implemente a função loadPaypalScript
    7. botão de renderização do paypal
    8. implementar a função de pagamento onApprove
    9. crie a API de ordem de pagamento no back-end
31. Exibir histórico de pedidos
    1. criar tela de pedido
    2. crie a API do histórico de pedidos
    3. use api no frontend
32. Tela Criar Perfil
    1. obtenha informações do usuário a partir do contexto
    2. mostrar informações do usuário
    3. crie a API de atualização do usuário
    4. atualizar as informações do usuário
33. Publicar no Heroku
    1. criar e configurar o projeto do nó
    2. servir a pasta de compilação na pasta de front-end
    3. Crie uma conta heroku
    4. conecte-o ao github
    5. Crie o banco de dados do atlas mongodb
    6. Defina a conexão do banco de dados nas variáveis ​​​​env do heroku
    7. Comprometa-se e empurre
34. Adicionar Barra Lateral e Caixa de Pesquisa
    1. adicionar barra lateral
    2. adicionar caixa de pesquisa
35. Criar tela de pesquisa
    1. Mostrar filtros
    2. crie uma API para pesquisar produtos
    3. exibir resultados
36. Criar Menu Admin
    1. definir componente de rota protegida
    2. definir o componente de rota de administrador
    3. adicionar menu para admin no cabeçalho
37. Criar tela do painel
    1. crie a interface do usuário do painel
    2. implemente a API de back-end
    3. conecte a interface do usuário ao back-end
38. Gerenciar Produtos
    1. crie a interface do usuário da lista de produtos
    2. implemente a API de back-end
    3. buscar dados
39. Criar Produto
    1. botão criar produtos
    2. implemente a API de back-end
    3. manuseie ao clicar
40. Criar Edição do produto
    1. criar botão de edição
    2. crie editar a interface do usuário do produto
    3. exiba informações do produto nas caixas de entrada
41. Implementar Produto de Atualização
    1. crie a API de back-end do produto de edição
    2. lidar com o clique de atualização
42. Carregar imagem do produto
    1. crie uma conta cloudinary
    2. use a chave api no arquivo env
    3. lidar com o arquivo de upload
    4. implemente a API de back-end para fazer upload
43. Excluir Produto
    1. mostrar o botão excluir
    2. implemente a API de back-end
    3. manuseie ao clicar
44. Listar Pedidos
    1. criar tela de lista de pedidos
    2. implemente a API de backen
    3. buscar e exibir pedidos
45. Entregar Pedido
    1. adicionar botão de entrega
    2. lidar com a ação de clique
    3. Implemente a API de backen para entrega
46. ​​Excluir pedido
    1. adicionar botão de exclusão
    2. lidar com a ação de clique
    3. Implemente a API de backen para exclusão
47. Listar usuários
    1. criar tela de lista de usuários
    2. implemente a API de backen
    3. buscar e exibir usuários
48. Editar usuário
    1. criar botão de edição
    2. crie editar a interface do usuário do produto
    3. exiba informações do produto nas caixas de entrada
    4. Implemente a API de back-end
    5. lidar com o clique de edição
49. Excluir usuário
    1. adicionar botão de exclusão
    2. lidar com a ação de clique
    3. Implemente a API de backen para exclusão
50. Escolha o endereço no mapa do Google
    1. crie credenciais do Google Maps
    2. atualize o arquivo .env com a chave de API do Google
    3. crie uma API para enviar a API do Google para o frontend
    4. criar tela de mapa
    5. buscar a API do Google
    6. getUserLocation
    7. instale @react-google-maps/api
    8. use-o na tela de envio
    9. aplique o mapa na tela de checkout
51. Recibo de pedido por e-mail por arma postal
    1. crie uma conta de espingarda
    2. adicione e verifique seu domínio no mailgun
    3. instale mailgun-js
    4. defina a chave api no arquivo env
    5. alterar a ordem de pagamento em orderRouter
    6. enviar recibo de pedido por e-mail
52. Revisar Produtos
    1. criar formulário de revisão de envio
    2. lidar com envio
    3. Implemente a API de back-end para revisão
53. Faça upload de várias imagens
    1. adicione imagens ao modelo do produto
    2. obtenha imagens na tela de edição
    3. mostre imagens na tela do produto
