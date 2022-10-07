# Odoo Devel

## Desenvolvimento Odoo com Docker e VsCode

```sh
# Para remover ou destruir a instação existente. rode o comando na pasta atual do projeto. ( Isso irá toda sua instalação e configuração. )
docker compose down -v 

# Para realizar o download ou pull das imagens antes de subir o ambiente, rode o comando abaixo.
docker compose pull odoo db

# Para checar as imagens existentes em sua maquina.
docker images

# Para mostrar os containers ou serviços que estão rodando.
docker compose ps

# Para rodar um serviço ( container ).
docker compose start odoo
```

## Links e Documentações.
- [Tutorial de Configuração do Ambiente](https://www.youtube.com/watch?v=9haSlj0Bqpw)
- [Documentação do Docker compose](https://docs.docker.com/compose/)
- [Download docker destktop](https://www.docker.com/products/docker-desktop/)
- [Download VsCode](https://code.visualstudio.com/Download)
- [Plugin Dev Container](https://code.visualstudio.com/docs/remote/create-dev-container)
