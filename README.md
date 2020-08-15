# Estrutura basica para projetos

## Executando o Projeto
Substitua no arquivo docker-compose.yaml os parâmetros `_PORTA_` pela porta em que deseja executar o sistema

- Execute o comando no Power Shell
```shell
docker volume create --name=postgresql-volume
```
Esse comando irá criar um volume chamado Postgresql para você.

Após isso, execute no terminal o comando:
```shell
docker-compose up -d
```

Será gerado um container com PHP,Postgresql e PGAdmin