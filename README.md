<h1 align="center">
    <img alt="Semana-Omnistack" src="https://carloshayashi.com/wp-content/uploads/2019/10/AirCnC-1024x627.jpg" width="700px" />
</h1>

<h2 align='center'>
    Semana OmniStack 2019
</h2>

## Nome da Aplicação: aircnc (uma aplicação inspirada no airbnb)

A aplicação intermedeia entre as empresas e os programadores de forma gratuita ou remunerada espaços (dependendo da política da empresa de como vai disponibilizar os espaços), onde com isso facilita a contratação de novos programadores dependendo do seu desenpenho e cria um network objetivo 

ele tem a parte Web onde a empresa faz o seu cadastro e depois cria os seus Spots, e o site mantem comunicação com o aplicativo atravez de um webservice que o programador por sua vez solicita a data que gostaria de alugar ou visitar o espaço.

## Stack

- Website
    - ReactJS;
    - Socket.io;
    - Axios;
    - [Outras dependencias](https://github.com/EpifanioD/Semana-Omnstack/blob/master/frontend/package.json)
- Mobile
    - React Native;
    - Expo;
    - Socket.io;
    - Axios;
    - [Outras dependencias](https://github.com/EpifanioD/Semana-Omnstack/blob/master/mobile/package.json)
- Back-end
    - Node.Js;
    - Express;
    - Socket.io;
    - MongoDB;
    - Mongoose;
    - Multer;
    - Dotenv;
    - [Outras dependencias](https://github.com/EpifanioD/Semana-Omnstack/blob/master/backend/package.json)
    
## Para Iniciar o Projeto

    - Website: yarn start;
    - Back-end: yarn dev (lembrando que foi a alteração no scripts do package.json, que faz a inicialização do nodemon);
    - Mobile: yarn start, e ler o QR code se for querer rodar em um dispositivo físico. 
