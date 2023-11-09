# Propuesta BlueSoft Bank

En el repositorio se encuentra el archivo ```BlueSoft.png``` donde se propone el diagrama de clases para resolver la nueva aplicación de clientes y sus transacciones

## Arquitectura y tecnologías

- Se propone utilizar la arquitectura en capas o de cebolla (DDD)
- Utilizar una API RestFull en C# para el backend usando patrones de diseño como Mediator, Injection Depency, CQRS, Unit Of Work, Specification, Decorator y MVC.
- Para el login y manejo de usuario usar Identity de ASP.NET con tokens y refresh token para todos los enpoints.
- Trabajar los enpoints en base a roles.
- Utilizar Angular para crear un sitio web que consuma ese servicio y muestre dichos datos segun el perfil que haya iniciado sesión.
