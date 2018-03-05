# Server CI

***Trabalho para a matéria de engenharia de software***

Para controle de versão e issue tracker, será utilizado uma imagem do GitLab CE (community edition).
Para deploy, está em escolha as aplicações [Jenkins](https://jenkins.io) e [TeamCity](https://www.jetbrains.com/teamcity/), também havendo possibilidade
de escolha para TravisCI.

## Configuração

As aplicações estão separadas por diretórios, para subir o serviço referente a aplicação, basta o comando:

```
docker-compuse up -d
```

dentro do diretório da aplicação. Quaisquer dúvidas sobre configurações, basta ler o arquivo ```docker-compose.yml```
