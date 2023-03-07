# Store

Store in php

# How to Install


``` shell
git clone https://github.com/YaelGF/Store.git
```

``` shell
cd docker
docker built -t php:v1 .
```

``` shell
cd ..
docker run -it -v $(pwd)/Store:/web -p8080:8080 --name php_conteiner -h php php:v1
```

``` shell
docker start -i php_conteiner
cd web
php -S 0.0.0.0:8080
```

# Run the project

## Main
![main](/assets/main.png)
![main2](/assets/main-result.png)

## Ticket
![ticket](/assets/Ticket.png)

## Data Base
![db](/assets/db.png)

# Sold

![sold](/assets/ventas.png)


# License
[Apache License 2.0](https://github.com/YaelGF/Store/blob/main/LICENSE)