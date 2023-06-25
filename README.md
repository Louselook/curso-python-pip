# Steps

Para correr el juego debes seguir las siguientes instrucciones en la terminal:

```sh
cd game
python3 main.py
```

para crear el entorno virtual se utiliza

```sh
python -m venv env
```
env es el nompre, lo puedes cambiar si gustas

# vsc
para correr el entorno virtual en vsc
primero abre powershell como admin y pon

```sh
Set-ExecutionPolicy Unrestricted
```

le das Y o S dependiendo de el idioma

luego para activar el env en vsc

```sh
.\env\Scripts\activate
```

# Linux

```sh
source env/bin/active
```

para desactivar

```sh
deactivate
```


# docker

para construir el contenedor

```sh
docker-compose build
```

luego para lanzarlo
```sh
docker-compose up -d
```

para deter el 
```sh
docker-compose stop
```

para ver el estado  usamos
```sh
docker-compose ps
```

para ingresar a el ambiente para empesar a desarrollar en el usamos 
```sh
docker-compose exec app-csv bash
```

