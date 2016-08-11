# Exemplo básico

```
$ docker run -t -i ubuntu /bin/bash
```

Neste exemplo:

  * docker run roda um container
  * ubuntu é a imagem que você quer rodar
  * parâmetro -t atribui um terminal no interior do novo container
  * parâmetro -i permite que você faça uma conexão interativa e visualizar o STDIN do container
  * /bin/bash abre um shell Bash dentro do container
