# Proyecto colaborativo de pruebas de API REST con Postman

Proyecto de práctica de QA enfocado en el diseño, ejecución y documentación de pruebas sobre la API pública de demostración [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

## Equipo colaborador

- **Sergio Andrés Barragán Caro** — [sergiobarrag-qa](https://github.com/sergiobarrag-qa)
- **Sergio Arturo Marín Contreras** — [sergioarturomc](https://github.com/sergioarturomc)

Este trabajo se realizó de manera colaborativa, compartiendo el diseño de casos de prueba, la ejecución de solicitudes en Postman, la revisión de respuestas HTTP/JSON y el registro de resultados.

## Alcance de la entrega colaborativa

- **46 casos principales:** pruebas sobre los recursos `posts`, `comments`, `albums`, `photos`, `todos` y `users`.
- **20 casos complementarios:** exploraciones de límites, tipos de datos, campos omitidos y comportamiento de las solicitudes.
- **Total: 66 solicitudes** en la colección de Postman.

En la ejecución documentada, las aserciones automatizadas configuradas para los 46 casos principales fueron aprobadas. Esto no significa que se haya validado un contrato funcional completo. Los 20 casos complementarios se registran como exploratorios y sus resultados no se clasifican automáticamente como defectos.

## Herramientas

- **Postman:** envío de solicitudes y automatización de comprobaciones.
- **JSONPlaceholder:** API REST pública de demostración.
- **Excel:** registro de casos, resultados, observaciones y conclusiones.
- **GitHub:** almacenamiento, documentación y publicación del proyecto.

## Consideraciones y limitaciones

JSONPlaceholder simula las operaciones de escritura. Las respuestas satisfactorias de POST, PUT, PATCH y DELETE no garantizan la persistencia de los cambios.

Los comportamientos inesperados encontrados en escenarios exploratorios se documentan como observaciones, hasta que puedan contrastarse con requisitos o criterios de aceptación definidos.

## Entrega

La colección de Postman y la matriz de ejecución se encuentran en la carpeta [`entrega-colaborativa/`](./entrega-colaborativa/).

## Perfiles del equipo

- [Sergio Andrés Barragán Caro — GitHub](https://github.com/sergiobarrag-qa)
- [Sergio Arturo Marín Contreras — GitHub](https://github.com/sergioarturomc)
