# Active Job

## Delayed Job

### Manejo de trabajos por consola

Dentro de la consola de rails, se puede administrar la información de los trabajos de la siguiente forma:

```shell
Delayed::Job.destroy_all
Delayed::Job.destroy_all
Delayed::Job.delete_all
Delayed::Job.find(4).destroy
```
