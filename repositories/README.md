# Repositories

Los **Repositories** actúan como una capa de abstracción entre los modelos y la lógica de negocio de la aplicación. Los repositorios son responsables de manejar todas las interacciones con la base de datos, proporcionando una interfaz sencilla para las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sin que los servicios o controladores tengan que preocuparse por los detalles de la base de datos.

## Funciones principales:
- **Abstracción de la base de datos**: Los repositorios encapsulan las consultas y operaciones sobre la base de datos, proporcionando una interfaz limpia.
- **Manejo de datos**: Se encargan de crear, leer, actualizar y eliminar datos.
- **Separación de responsabilidades**: Mantienen los servicios y controladores libres de la lógica de interacción directa con la base de datos.
