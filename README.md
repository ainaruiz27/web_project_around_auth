# Tripleten web_project_around_auth

En este proyecto, implementarás el registro y la autorización en el frontend de tu proyecto de React "Alrededor de los EE.UU.". Trabajarás en un nuevo repositorio de git y copiarás el contenido del repositorio del proyecto 11 en el nuevo.

## Requisitos

1. **Crear Rutas y Redireccionar**
   - Toda la funcionalidad de la aplicación estará disponible únicamente para usuarios autorizados a través de la ruta raíz `/`.
   - Implementa dos nuevas rutas para usuarios no autorizados en un archivo `auth.js`:
     - `/signup`: para el registro de usuarios.
     - `/signin`: para la autorización de usuarios.
   - Si un usuario no autorizado visita la aplicación, debería ser redirigido a la página de inicio de sesión, independientemente de la ruta desde la que accedió.

2. **Crear Nuevos Componentes de React**
   - **Login**: Componente para la autorización de usuarios con las variables de estado necesarias.
   - **Register**: Componente para el registro de los usuarios con las variables de estado necesarias.
   - **ProtectedRoute**: Componente para proteger la ruta `/` de tal modo que los usuarios no autorizados no puedan acceder a ella.
   - **InfoTooltip**: Componente de ventana modal que informa al usuario si ha sido registrado exitosamente.
   - El encabezado debe ser diferente para los usuarios autorizados y los no autorizados, según el diseño de Figma.

3. **Conectar la Funcionalidad Principal del Sitio en el Backend de TripleTen**
   - URL base: `https://register.nomoreparties.co`
   - Endpoints:
     - `/signup`: registro de usuarios.
     - `/signin`: autorización de usuarios.
   - Las funciones, la habilitación de solicitudes API relacionadas con el registro y la autorización deben estar ubicadas en el archivo `auth.js` en la carpeta `/utils`.
   - Las nuevas llamadas a la API deben suceder en `App.js`, no en los componentes `Register` y `Login`.

4. **Implementar la Autenticación del Usuario**
  

5. **Implementar el Almacenamiento Local y la Manipulación de Tokens**
   - Implementa `localStorage` para almacenar y acceder al token cuando trabajes en un sitio.
   - Comprueba la validez del token al enviar una solicitud al endpoint `/users/me`.

6. **Analizar tu Sitio con Base en lo que ya Sabes sobre Seguridad**
  

## Diseño Figma
