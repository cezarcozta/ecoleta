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

## Identidade Visual  

![](https://github.com/cezarcozta/ecoleta/blob/master/frontend/src/assets/home-background.svg)

![](https://github.com/cezarcozta/ecoleta/blob/master/frontend/src/assets/logo.svg)  

## Tecnologias envolvidas  

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

'git clone https://www.github.com/cezarcozta/ecoleta'  

>**access project folder**  

'cd /be-the-hero'  

>## **/backend**  

```zsh
cd /backend  
yarn  
yarn start  
```

>url: http://localhost:3333/

>## **/frontend**  

```zsh
cd /frontend  
yarn  
yarn start
```  

>(http://localhost:3000/)  

>## **/mobile**  

```zsh
cd /mobile  
yarn
yarn start
```  

> Baixe e instale o EXPO no seu smartphone, acesse o EXPO e escaneie o QRCode do terminal ou escaneie em http://localhost:19002/  
>**Ajustando acesso a api**  

```zsh
/mobile/src/services/api.js
```

![](https://github.com/cezarcozta/be-the-hero/blob/master/mobile/src/assests/tela.png)  

```javascript
const api = axios.create({
    baseURL: 'http://192.168.1.105:3333',
});
```  

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
