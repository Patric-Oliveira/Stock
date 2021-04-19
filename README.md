# Stock
 **Sistema de estoque para lojas de autopeças e oficina de carros.**

 Inicialmente ainda está nos rabiscos, mas a ideia é crescer o projeto a longo prazo. Tudo aqui é experimental e é pra quem está iniciando na área. 
 
## Recursos e frameworks sendo utilizados
 
 A ideia do sistema após a conclusão é que o mesmo atenda uma grande demanda de usuários ao qual ele será hospedado em nuvem para o seu funcionamento. Inicialmente iremos implementar o sistema na plataforma do [Heroki](https://www.heroku.com/) para hospedagem, porém, com o decorrer da demanda e experiencia que tivermos, podemos hospedar em serviços como o [Google Cloud](https://cloud.google.com/?hl=pt-br) ou [AWS](https://aws.amazon.com/pt/).

 Algumas rotas do sistema já se encontram funcional, outras ainda estão em desenvolvimento. Atualmente estamos focando no back-end do sistema com o node.js.

 Veja abaixo os frameworks que estamos utilizando: 
 
 - body-parser (1.19.0)
 - express (4.17.1)
 - express-handlebars (5.3.0)
 - handlebars (4.7.7)
 - morgan (1.10.0)
 - mysql2 (2.2.5)
 - nodemon (2.0.7)
 - sequelize (6.6.2)

Como banco de dados, que atualmente executamos tudo localmente, nesse projeto estamos utilizando o MySQL 8.0.23.

## Telas do sistema

Inicialmente o projeto terá as seguintes telas:
 - **Cadastro**
    - *Clientes*
    - *Funcionários*
    - *Produtos*
- **Vendas**
    - *Venda direta*
    - *Ordem de Serviço (O.S)*
- **Relatórios**
    - *Relatórios de vendas com filtros de período*
    - *Balanço do estoque*
    - *Comissão de mecânicos*

## Sistema sendo projetado com o padrão REST e RESTFULL
O rest é um padrão que definirá as características fundamentais para a contrução de um projeto Web para que as APIs utilizadas consigam interligar diferentes frameworks, tanto no back-end como no front-end.

## Verbos HTTP
GET = Recebe dados
POST = Enviar dados dos formulários
PUT = Atualizar dados
DELETE = Deletar dados
