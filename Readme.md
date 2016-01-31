#### Compilar imagem da aplicação 'dockerizada'
```
docker build -t hellomvc .
```

#### Executar app
```
docker run -t -d -p 80:5004 hellomvc
```
