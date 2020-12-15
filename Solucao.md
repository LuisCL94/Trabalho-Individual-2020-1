# Docker

Foi ultilizado tanto Docker quanto Docker-compose para a containerização e orquestração de containers do trabalho.

### Para rodar a aplicação

```bash
sudo docker-compose build
sudo docker-compose run api rake db:create
sudo docker-compose run api rake db:migrate
sudo docker-compose up
```

# Integração Contínua

Foi ultilizado a aplicacao web [buddy.works](https://app.buddy.works/) para as etapas de build do front-end e
back-end, na qual são instaladas as dependências e os testes são rodados.
