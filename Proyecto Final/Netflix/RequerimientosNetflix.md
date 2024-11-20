///////////////////////////////////////////////////
                         ENUNCIADOS

## Create

#### Enunciado 1: Creación de una Nueva Cuenta

**Descripción:** Desarrollar una función que permita a un usuario crear una nueva cuenta en la aplicación. La función debe solicitar:

- **Nombre de usuario:** El nombre de usuario que el usuario desea utilizar.
- **Correo electrónico:** La dirección de correo electrónico del usuario.
- **Contraseña:** La contraseña para la cuenta.
- **Plan de suscripción:** El tipo de plan de suscripción (básico, estándar, premium).

**Resultado:** La función debe almacenar la nueva cuenta y confirmar su creación al usuario.

---

#### Enunciado 2: Agregar una Nueva Película o Serie

**Descripción:** Desarrollar una función que permita a un administrador agregar una nueva película o serie a la biblioteca. La función debe solicitar:

- **Título:** El título de la película o serie.
- **Descripción:** Una breve descripción del contenido.
- **Género:** El género de la película o serie (acción, comedia, drama, etc.).
- **Año de lanzamiento:** El año en que se lanzó la película o serie.
- **Clasificación:** La clasificación por edades (G, PG, R, etc.).
- **URL de la portada:** La URL de la imagen que servirá como portada.

**Resultado:** La función debe almacenar la nueva película o serie y confirmar su creación al administrador.

---

#### Enunciado 3: Agregar una Reseña

**Descripción:** Desarrollar una función que permita a un usuario agregar una reseña a una película o serie existente. La función debe solicitar:

- **ID de la película o serie:** El identificador de la película o serie a la que se desea agregar la reseña.
- **Texto de la reseña:** El contenido de la reseña.
- **Calificación:** La calificación (por ejemplo, de 1 a 5 estrellas).

**Resultado:** La función debe almacenar la nueva reseña y confirmar su creación al usuario.

---

## Read

#### Enunciado 1: Visualización de Cuentas

**Descripción:** Desarrollar una función que permita a un administrador ver todas las cuentas de usuarios en la aplicación. La función debe mostrar:

- **Lista de cuentas:** Incluir la siguiente información para cada cuenta:
  - **Nombre de usuario:** El nombre de usuario del perfil.
  - **Correo electrónico:** La dirección de correo electrónico asociada.
  - **Plan de suscripción:** El tipo de plan de suscripción.
  - **Estado de la cuenta:** Activa o inactiva.

**Resultado:** La función debe permitir al administrador buscar cuentas por nombre de usuario o correo electrónico.

---

#### Enunciado 2: Visualización de Películas y Series

**Descripción:** Desarrollar una función que permita a un usuario ver todas las películas y series disponibles en la biblioteca. La función debe mostrar:

- **Lista de películas y series:** Incluir la siguiente información para cada título:
  - **Título:** El título de la película o serie.
  - **Descripción:** Una breve descripción del contenido.
  - **Género:** El género de la película o serie.
  - **Año de lanzamiento:** El año en que se lanzó.
  - **Clasificación:** La clasificación por edades.

**Resultado:** La función debe permitir al usuario filtrar títulos por género, año de lanzamiento o clasificación.

---

#### Enunciado 3: Visualización de Reseñas

**Descripción:** Desarrollar una función que permita a un usuario ver todas las reseñas de una película o serie específica. La función debe solicitar:

- **ID de la película o serie:** El identificador de la película o serie de la que se desean ver las reseñas.

**Resultado:** La función debe mostrar:

- **Lista de reseñas:** Incluir la siguiente información para cada reseña:
  - **Nombre de usuario:** El nombre de usuario del que escribió la reseña.
  - **Texto de la reseña:** El contenido de la reseña.
  - **Calificación:** La calificación dada por el usuario.

---

## Update

#### Enunciado 1: Actualización de la Información de la Cuenta

**Descripción:** Desarrollar una función que permita a un usuario actualizar la información de su cuenta. La función debe solicitar:

- **ID de la cuenta:** El identificador de la cuenta que se desea actualizar.
- **Nuevo nombre de usuario (opcional):** Un nuevo nombre de usuario.
- **Nuevo correo electrónico (opcional):** Una nueva dirección de correo electrónico.
- **Nuevo plan de suscripción (opcional):** Un nuevo tipo de plan de suscripción.

**Resultado:** La función debe actualizar la información de la cuenta y confirmar los cambios al usuario.

---

#### Enunciado 2: Actualización de una Película o Serie

**Descripción:** Desarrollar una función que permita a un administrador actualizar los detalles de una película o serie existente. La función debe solicitar:

- **ID de la película o serie:** El identificador de la película o serie que se desea actualizar.
- **Nuevo título (opcional):** Un nuevo título para la película o serie.
- **Nueva descripción (opcional):** Una nueva descripción para el contenido.
- **Nuevo género (opcional):** Un nuevo género para la película o serie.
- **Nuevo año de lanzamiento (opcional):** Un nuevo año de lanzamiento.
- **Nueva clasificación (opcional):** Una nueva clasificación por edades.
- **Nueva URL de la portada (opcional):** Una nueva URL para la imagen de portada.

**Resultado:** La función debe actualizar los detalles de la película o serie y confirmar los cambios al administrador.

---

#### Enunciado 3: Actualización de una Reseña

**Descripción:** Desarrollar una función que permita a un usuario actualizar una reseña existente en una película o serie. La función debe solicitar:

- **ID de la reseña:** El identificador de la reseña que se desea actualizar.
- **Nuevo texto de la reseña (opcional):** El nuevo contenido de la reseña.
- **Nueva calificación (opcional):** La nueva calificación dada por el usuario.

**Resultado:** La función debe actualizar la reseña y confirmar los cambios al usuario.

---

## Delete

#### Enunciado 1: Eliminación de una Cuenta

**Descripción:** Desarrollar una función que permita a un usuario eliminar su cuenta de la aplicación. La función debe solicitar:

- **ID de la cuenta:** El identificador de la cuenta que se desea eliminar.

**Resultado:** La función debe eliminar la cuenta y confirmar la eliminación al usuario, manejando el caso en que la cuenta no exista.

---

#### Enunciado 2: Eliminación de una Película o Serie

**Descripción:** Desarrollar una función que permita a un administrador eliminar una película o serie de la biblioteca. La función debe solicitar:

- **ID de la película o serie:** El identificador de la película o serie que se desea eliminar.

**Resultado:** La función debe eliminar la película o serie y confirmar la eliminación al administrador, manejando el caso en que la película o serie no exista.

---

#### Enunciado 3: Eliminación de una Reseña

**Descripción:** Desarrollar una función que permita a un usuario eliminar una reseña que ha realizado en una película o serie. La función debe solicitar:

- **ID de la reseña:** El identificador de la reseña que se desea eliminar.

**Resultado:** La función debe eliminar la reseña y confirmar la eliminación al usuario, manejando el caso en que la reseña no exista.

---

--- Ante cualquier duda consultar con el Docente/Auxiliar. ---