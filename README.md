# Landing page produto - Mini Car Phone Holder

Repositório de código de uma página para venda do produto Mini Car Phone Holder.

Uma versão online para visualização está disponível clicando [aqui](https://mini-car-phone-holder.davischoll.vercel.app/).

Desenvolvido em HTML5 e CSS3, com Boostrap.

## Rodar localmente para desenvolver:

Para rodar a aplicação na máquina com um servidor local, pode-se utilizar uma imagem do PHP8, através do Docker.
Para isso, basta atualizar o arquivo "docker-compose.yml", colocando o caminho local do projeto em "volumes",
navegar pelo terminal até o diretório do projeto e rodar o comando abaixo. Ele vai baixar a imagem do docker
e criar um container do PHP8.

```
docker-compose up
```

Com o container startado, a página poderá, então, ser acessada no navegador, através da porta 8080:
```
http://localhost:8080/
```
