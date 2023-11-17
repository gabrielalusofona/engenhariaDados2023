
Verificar se o docker está a correr:
```docker ps```

Carregar o container com postgres
```docker-compose -f postgres-docker-compose.yaml up ```

"Entrar no seu container"
```docker exec -it database bash```

Apagar containers:
```docker-compose -f postgres-docker-compose.yaml down --volumes --rmi all```
