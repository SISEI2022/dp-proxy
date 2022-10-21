# Proxy - Caso práctico

### Intención

Ofrece un objeto sustituto (subrogado) para otro objeto con el fin de controlar el acceso al mismo.

### Clasificación

Patron estructural

### Vista Estructural

![image](https://user-images.githubusercontent.com/55771796/173483124-d3bcf1a8-9479-48b0-98c6-b0607809819f.png)

### Vista Dinámica

![image](https://user-images.githubusercontent.com/55771796/173483172-ad597daf-466c-4140-ba00-8912cd3d0971.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Proxy crearemos un mecanismo de seguridad, el cual intercepte las ejecuciones de procesos para validar si el usuario que intenta ejecutar cuenta con los privilegios necesarios, evitando que usuarios no autorizados los ejecuten, además, una vez que el proceso es ejecutado, se auditara la ejecución y quedará un registro de la ejecución. Todo esto se realizará sin que el usuario se dé cuenta, pues el proxy envolverá la lógica de seguridad.

![image](https://user-images.githubusercontent.com/55771796/173483277-090819fc-693c-4d30-87af-92443799d05b.png)

![image](https://user-images.githubusercontent.com/55771796/174158380-af1a017d-ccdb-4c4a-9149-b65eab27f4cc.png)

### Ejecucion

```
gradle run
```
