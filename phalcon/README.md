# Exemplo de aplicação Phalcon

```
docker run -d -v $PWD/tutorial:/var/www/phalcon -p 80:80 eboraas/phalcon
```

Neste exemplo:

  * docker run roda um container
  * eboraas/phalcon é a imagem que você quer rodar
  * parâmetro -d coloca o container em background (libera o terminal)
  * parâmetro -v mapeia a pasta tutorial do host (local) com a pasta /var/www/phalton dentro do container
  * parâmetro -p mapeia a porta 80 do host com a porta 80 do container
