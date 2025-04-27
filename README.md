# Vinyl API

API RESTful para gestionar un sistema de vinilos, desarrollada en **Go** utilizando el framework **Gin**.

## Características

- Crear, obtener, actualizar y eliminar vinilos.

## Tecnologías

- [Go](https://golang.org/)
- [Gin](https://github.com/gin-gonic/gin)

## Instalación

```bash
git clone https://github.com/dev-elliotesco/vinyl-api.git
cd vinyl-api
go mod tidy
```

## Uso

```bash
go run main.go
```

El servidor se levantará en `http://localhost:8080`.

## Endpoints

| Método | Ruta             | Descripción                   |
|--------|------------------|-------------------------------|
| GET    | `/vinyls`         | Listar todos los vinilos      |
| GET    | `/vinyls/:id`     | Obtener un vinilo por ID      |
| POST   | `/vinyls`         | Crear un nuevo vinilo         |

## Ejemplo de entidad Vinyl

```json
{
  ...
}
```

## Estructura básica de carpetas

```bash
vinyls-api/
├── controllers/
├── models/
├── routes/
├── main.go
├── go.mod
```


## Autor

- Elliot Escovicth Riaño 
- [Github](https://github.com/dev-elliotesco)
- [LinkedIn](https://https://www.linkedin.com/in/elliot-escovitch-580007205/)
- Correo electrónico: dev.elliot.escovitch@gmail.com
