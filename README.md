# Proyecto colaborativo de pruebas de API REST con Postman

Proyecto de práctica de QA para diseñar, ejecutar y documentar pruebas sobre la API pública de demostración [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

## Equipo colaborador

- **Sergio Andrés Barragán Caro** — [sergiobarrag-qa](https://github.com/sergiobarrag-qa)
- **Sergio Arturo Marín Contreras** — [sergioarturomc](https://github.com/sergioarturomc)

Este trabajo se realizó en colaboración para compartir el diseño de casos, la ejecución de solicitudes en Postman, la revisión de respuestas HTTP/JSON y el registro de resultados. El perfil de Sergio Arturo: [github.com/sergioarturomc](https://github.com/sergioarturomc).

## Alcance de la entrega colaborativa

- **46 casos principales:** pruebas funcionales sobre los recursos `posts`, `comments`, `albums`, `photos`, `todos` y `users`.
- **20 casos complementarios:** exploraciones de límites, tipos de datos, campos omitidos y manejo de solicitudes.
- **Total: 66 solicitudes** en la colección Postman.

Los 46 casos principales tuvieron las aserciones automatizadas configuradas aprobadas en la ejecución documentada. Esto no significa que se haya validado un contrato funcional completo. Los 20 casos complementarios se registran como exploratorios y no se clasifican automáticamente como defectos.

## Herramientas

- Postman para enviar solicitudes y automatizar comprobaciones.
- JSONPlaceholder como API REST pública de demostración.
- Excel para registrar casos, resultados y conclusiones.
- GitHub para versionar y compartir el trabajo.

## Consideraciones y limitaciones

JSONPlaceholder simula las operaciones de escritura. Las respuestas satisfactorias de POST, PUT, PATCH y DELETE no garantizan persistencia de cambios. Los comportamientos inesperados de escenarios exploratorios se documentan como observaciones hasta contrastarlos con requisitos o criterios de aceptación.

## Entrega

La colección Postman y la matriz de ejecución se encuentran en la carpeta `entrega-colaborativa/`.

## Perfiles del equipo

- [Sergio Andrés Barragán Caro — GitHub](https://github.com/sergiobarrag-qa)
- [Sergio Arturo Marín Contreras — GitHub](https://github.com/sergioarturomc)
