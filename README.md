# chasqui-api

## User Locations

1. GET  /users/:user_id/locations
  Params: `:user_id`
2. POST /users/:user_id/locations -> Agregar ubicacion actual
  Params: `:user_id`, `latitude`, `longitude`
  
## Locations
1. GET /locations -> retorna todas las ubicaciones
  Params: -
2. GET /locations/:id -> retorna una ubicacion.
  Params: `:id`

## Marcador

1. GET  /marcadores
2. GET  /marcadores/:id
3. DELETE /marcadores/:id

## Alertas

1. POST /alertas

## Solicitudes

1. POST /solicitudes
2. GET /solicitudes

## Chasquis
1. GET /chasquis ->retorna todos los chasquis
2. GET /chasquis/:id -> retorna data de un chasqui en especifico
