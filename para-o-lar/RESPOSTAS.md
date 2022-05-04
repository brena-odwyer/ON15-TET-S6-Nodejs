# Respostas
1.Qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
Nível 2.
Existem qutro níveis de maturidade API, eles vão do 0 ao 3. Sendo o 0 o mais desorganizado e que pode gerar mais problemas e o 3, que é o mais organizado. Da mesma forma como pensamos boas práticas internas ao código, devemos pensar a melhor maneira de utilizar os recursos de uma API.
As APIs de nível 0 utilizam apenas o verbo post. O problema deste tipo de API é qu ele precisa de muita documentação para realizar os comandos.
As APIs de nível 1 é um pouco mais orgnizada. Ocorre quando uma URL é criada para cada recurso. Neste nível ainda é utilizado somento o POST.
As APIs de maturidade nível 2 utilizam os verbos HTTP de forma CRUD. Este nível de API é muito mais legível e reduz custos por ser de mais fácil consumo.
As APIs de nível 3 são aquelas que tem o HATEOAS aplicadas.

2.Qual a relação entre os metodos HTTP e o CRUD?
Há uma relação de correspondência, respectivamente:
Os verbos HTTP são: Post, Get, Put, Patch, Delete.
As operações CRUD são: Create, Read, Update/Replace, Updade/Modify, Delete.
O protoclo HTTP funciona com os clintes enviando requests para os servers, e os servers respondendo a estes requests. As operações CRUD são enviadas através de requests HTTP, feitos através dos verbos.
O CRUD é um acronímico que resume as quatro principais formas de intereção entre database e aplicações.

3.O que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
HATEOAS significa Hypermedia as the Enthine of Application State e é uma restrição da arquitetarua das aplicações REST que as distinguem de outras arquiteturas de aplicação. A restrição HATEOAS é parte essencial da interface uniforme do REST.

4.O que quer dizer quando dizemos que uma API é idempotente?
No contexto de APIs REST, a idempotência ocorre quando é possível fazer diversos requests idênticos tendo o mesmo efeito de um único request. é uma forma de deixar os APIs tolerantes aos erros dos consumidores.
Sifnifica que o resultado do request vai ser bem-sucedido independete da quantidade de vezes que for executado.

5.Qual a diferença entre os métodos PUT e PATCH?
O método de requisição HTTP PATCH aplica modificações parciais a um recurso enquanto o método PUT permite substituições completas de um documento. O PUT é idempotente, isto é, aceita requisições sucessivas idênticas.

6.Do arquivo filmes.js retorne no terminal o Titulo, Ano e Genero. (desafio: apresente cada Genero em linhas separadas). 
Feito.

7.Do arquivo colors-rgb retorne no terminal o RGB como no exemplo: "aliceblue RGB: 240, 248, 255, 1".
Feito.

8.Do arquivo estados-cidade dado uma sigla retorne no terminal a lista de cidades.
Feiot.

 <!-- Para subir no git hub a partir da minha branch
 -- git add .
 git commit -m”mensagem”
 git push -u origin brena-odwyer -->