# dio-docker

### Construindo as imagens

Acesse a pasta raíz do projeto e construa as duas imagens (API spring + proxy nginx)

```
docker build -t api-image -f api/Dockerfile .
```

```
docker build -t proxy-image -f proxy/Dockerfile .
```
