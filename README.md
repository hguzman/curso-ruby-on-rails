# curso-ruby-on-rails
Curso ruby on rails

1. [Active Record](active_record/readme.md)
    1. Herencia
2. [Active Job](active_job/readme.md)
3. [API REST](api/readme.md)


## Manejador de Versiones

[Manejador de versiones](https://blog.makeitreal.camp/manejadores-de-versiones-en-ruby/#:~:text=Un%20manejador%20de%20versiones%20para,y%20cambiar%20entre%20versiones%20fácilmente.&text=Existen%20dos%20manejadores%20de%20versiones,Ruby%20Version%20Manager)

## Rutas

| Method | URL | Controller | Comment |
| --- | --- | --- | --- |
| GET | personas | index | Muestra todas las personas |
| POST | personas | create | Crea una persona |
| GET | personas/:id | show | Muestra una persona |
| PUT | personas/:id | update | Actualiza persona |   
| PATCH | personas/:id | update | Actualiza persona |   
| DELETE | personas/:id | destroy | Borra persona |   

## Rutas Anidadas

| Method | URL | Controller | Comment |
| --- | --- | --- | --- |
| GET | personas/:persona_id/celulares | index | Muestra celulares asociados a una persona |
| POST | personas/:persona_id/celulares | create | Crea un celular a una persona |
| GET | personas/:persona_id/celulares/:id | show | Muestra un celular de una persona |
| PUT | personas/:persona_id/celulares/:id | update | Actualiza celular de una persona |   
| PATCH | personas/:persona_id/celulares/:id | update | Actualiza celular de una persona |   
| DELETE | personas/:persona_id/celulares/:id | destroy | Borra Celular de una persona |   


## Inicial ngrok

`ngrok http [port] -host-header="localhost:[port]"`
