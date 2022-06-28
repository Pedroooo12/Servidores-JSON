# Servidores-JSON

## ¿Cómo levantar un servidor JSON en tu ordenador?

1. Creamos un archivo json:

```
//archivo.json
{
    "usuarios": [
        {
            "id": 1,
            "email": "test1@test.com",
            "username": "test1"
        },
        {
            "id": 2,
            "email": "test2@test.com",
            "username": "test2"
        },
        {
            "id": 3,
            "email": "test3@test.com",
            "username": "test3"
        }
    ]
}
```

2. vamos al cmd y vamos a nuestra carpeta y ponemos

```
json-server --watch archivo.json
```
