
# Setup Docker Com Laravel 10 e  PHP 8.1

### Passo a passo
- Clone o projeto
- Acesse a pasta raiz


Suba os containers do projeto
```sh
docker-compose up -d
```


Acesse o container app
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```

Acesse o projeto
[http://localhost:8989](http://localhost:8989)



