# 4-Teste de API

## Preparando o ambiente

Foi utilizado para a execução dos testes:

- Docker Desktop 
- MySQL Workbench 8.0 
- Python 3.12
- Flask
- Vue.js
- Node

Execute o docker na pasta dos arquivos com o comando:
```bash
    docker-compose up
```

## Inicializando Back-end

Instale as dependências do Python:

```bash
    pip install flask flask-cors mysqlclient
```

Inicie a API Flask:
```bash
    python api.py
```
Feito isso, o back-end estará rodando em http://localhost:5000


## Inicializando Front-end

Instale as dependências do Vue.js:
```bash
    cd busca-vue
    npm install
```

Inicie a aplicação com:
```bash
    npm run serve
```
Assim, o front-end estará rodando em http://localhost:8080

