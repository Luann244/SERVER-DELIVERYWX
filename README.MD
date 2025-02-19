<h1 align="center"> DeliveryWX.</h1>

<div align="center">
  <img src="logo.png">
</div>

<br/>

### 🎯 Sobre:

O **DeliveryWX** é uma plataforma WEB e MOBILE para comprar de qualquer tipo de comida ou bebida, isso fica a preferência do usário.

A API do **DeliveryWX** irá servir os daods para a plataforma WEB e Mobile disponível para Android.
</br></br>

### Importar Rotas da Aplicação:

Todas as rotas foram testadas utilizando o [Insomnia](https://insomnia.rest/download/). Para importar as rotas testadas para o Insomnia clique no botão:

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=GoBarber&uri=https%3A%2F%2Fraw.githubusercontent.com%2Frodrigorgtic%2Fbackend-gobarber-typescript%2Fmaster%2Finsomnia-api-routes.json)

### Recursos da API:

:busts_in_silhouette: **Criação de perfil de usuário**

- [x] Permite que um usuário consiga criar a sua conta no sistema;
- [x] Permite que um usuário consiga criar a sua conta sem cadastrar uma foto de perfil;
- [x] Permite que um usuário consiga criar a sua conta sem cadastrar uma cartão de crédito;

:lock: **Recuperação de senha**

- [x] Permite que um usuário consiga recuperar a senha informando o e-mail cadastrado;
- [x] A API envia para o usuário um e-mail con instruções de recuperação de senha;
- [x] A API envia um link com token por e-mail para resetar a senha e por segurança o token enviado expira em 2h;
- [x] Cadastro e autenticação de usuários com geração de JwToken;
- [x] Autenticação de usuários com JwToken;

:busts_in_silhouette: **Atualização de perfil de usuário**

- [x] Permite usuário cadastrar-se no sistena e atualizar seu perfil (incluindo imagem de avatar);
- [x] Validação de e-mails no cadastro, não é possível cadastrar dois usuários com mesmo e-mail;
- [x] Para atualizar a senha, o usuário deve informar a senha antiga e a nova senha;

:date: **Agendamento de serviços**

- [x] Usuário poderá está fazendo agendamento para receber um pedido em terderminado horário;

:shope: **Fazeer Comprar no sistema**

- [x] Usuário poderá está fazendo uma compra de um ou mais produtos em nosso sistema;
- [x] Usuário para fazer uma comprar no sistema ele terá que está cadastrado e deverá está autenticado na hora de fazer seu pedido;
- [x] Usuário poderá fazer uma comprar, e ele poderá estar passando seu pedido no crédito ate 3x;
- [x] Usuário poderá está escolhendo o produto de preferência e adicinar ao carrionho e comprar mais tarde ou ate no outro dia;
- [x] Usuário poderá está fazendo sua escolha, receber o pedido em casa ou ir fazer sua própia retirada no estabelecimento;
- [x] Usuário quando fizer seu pedido, durante os primeiro 5 minutos ele poderá está fazendo o cancelamento sem ser cobrado algum valor sobre o pedido;
- [x] Usuário quando fizer seu pedido, ele será capaz de está acompanhando a entrega do pedido atè a sua casa em tempo real;
- [x] Usuário quando seu pedido estiver a caminho ele poderá está fazendo uma ligação para o motoboy ou estabelecimento;

### Banco de Dados e Estratégias de Armazenamento:

Para banco de dados, foi utilizado o **Mysql** para armazenar os dados que envolvem relacionamentos da regra de negócio da aplicação.

### Ferramentas, Técnicas e Bibliotecas da API:

- [x] Aplicação da metodologia MVC (Model-View-Controller);
- [x] Utilização do [typescript](https://github.com/microsoft/tsyringe) fazer tipagem em noso código.
- [x] Utilizado o [mailtrap](https://mailtrap.io/) para testar o envio de e-mails em ambiente de testes;

## 👨🏻‍💻 Roda Projeto em Sua Máquina:

- Clone the project

```bash
  git clone https://github.com/Luann244/SERVER-DELIVERYWX
```

- Go to the project directory

```bash
  cd deliverywx
```

- Install dependencies

```bash
  npm install
```

<div align="center">
  <small>Weverson Luan Sousa - 2022</small>
</div>
