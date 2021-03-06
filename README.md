# Ecoleta

## Propósito

    Aplicação para conexão via whatsapp ou e-mail entre pessoas que 
    desejam oferecer items a serem coletados para que o descarte seja 
    feito de forma correta, e os pontos de coletas que recebem e coletam
    items e assim como dão o destino correto pra cada item.
    Com o app web Ecoleta os locais de pontos de coleta se cadastram com 
    nome, foto e endereço(clicando no mapa) e adicionam os items aos quais
    coletam.
    Já o app mobile qualquer pessoa que instalar no smartphone pode 
    acessar uma listagem de pontos de coleta, filtrado pelos items aos quais
    desejam descartar, acessando via os pontos do mapa indicados pela foto
    e nome previamente cadastrado pelo ponto de coleta, acessando os detalhes
    do ponto de coleta o usuário tem a disposição os botões de E-mail e 
    Whatsapp do ponto para por fim poder entrar em contato para combinar 
    a coleta.   

## Design  

![logo](https://github.com/cezarcozta/ecoleta/blob/master/frontend/src/assets/logo.svg)
![background](https://github.com/cezarcozta/ecoleta/blob/master/frontend/src/assets/home-background.svg)

## Techs  

- **Language:** JS + TS  
- **Database:** SQLite3 + KNEX.js ORM  
- **Back-end:** Node.js + Express.js  
- **Front-end:** React.js + Styled Components + Celebrate  
- **Mobile:** React Native + Expo  
- **Tests:** JEST  
- **Operational System:** Ubuntu 18.04 LTS  

## Getting Started  

**Precondition: yarn package manager.**  
>**clone the repository**  

```git clone https://www.github.com/cezarcozta/ecoleta```  

>**access project folder**  

```cd /be-the-hero```  

>## **/backend**  

`cd /backend`  
`yarn`  
`yarn start`  
  
`url: http://localhost:3333/`  
  
>## **/frontend**  
  
`cd /front-end`  
`yarn`  
`yarn start`  
  
`url: http://localhost:3000/`  
  
>## **/mobile**  
  
`cd /mobile`  
`yarn`  
`yarn start`  
  
> Download and install EXPO in your smartphone, access the EXPO app and scan the QRCode from the terminal or scam from [http://localhost:19002/](http://localhost:19002/)  
>**Adjusting access to the api**  
  
`/mobile/src/services/api.js`  
  
![trocaip](https://github.com/cezarcozta/be-the-hero/blob/master/mobile/src/assests/tela.png)  
  
```const api = axios.create({ baseURL: 'http://192.168.1.105:3333'});```  
  
### Desenvolvido por  

- :rocket::rocket::rocket: [RocketSeat](https://rocketseat.com.br/)  
    Next Level Week #1  

### Apresentado por  

- [Diego Fernandes](https://github.com/diego3g)  

### Reproduzido por  

- César Augusto Costa :sunglasses: :sunglasses: :sunglasses:  
:: cezarcozta@gmail.com  
:: [Linkedin/cezarcozta](www.linkedin.com/in/cezarcozta)  
:: [Twitter@cezarcozta](www.twitter.com/cezarcozta)  
:: [Instagram@cezarcozta](www.instagram.com/cezarcozta)  
:: [Facebook/cezarcozta](www.facebook.com/cezarcozta)  
