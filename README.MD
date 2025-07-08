# LoginPortafolio.github.io
Portafolio web con login 

![image](https://github.com/user-attachments/assets/8ca8cf22-a3d1-4563-8849-7911dfdc554a)

Para el siguiente trabajo de programacion web elaboramos un login en html, añadiendo metodos de verificacion y registro de datos.
index.html: El menú de navegación principal incluye:

Inicio
Sobre mí
Proyectos
Contacto

Login.html: solo es un formulario de login/registro.

Plantilla utilizada
Pare el Logine no se uso una plantilla específica de login, sino un diseño propio con Bootstrap.

Descripción de cada sección

index.html
Menú de navegación: Barra superior fija con enlaces a las secciones principales.
Masthead: Encabezado con título y subtítulo de bienvenida.
Sobre mí: Tarjeta con foto de perfil, nombre, escolaridad, pasatiempos y una breve descripción personal.
Habilidades: Sección con íconos y nombres de lenguajes de programación, bases de datos y herramientas de diseño.
Proyectos: Galería de proyectos con imágenes y descripciones breves.
Contacto: Formulario para enviar un correo electrónico y tarjetas con dirección, correo y teléfono.
Redes sociales: Íconos con enlaces a Twitter, Facebook y GitHub.
Footer: Pie de página con derechos reservados.

Login.html
Logo: Imagen circular en la parte superior.
Formulario de inicio de sesión: Campos para correo y contraseña, botón para ingresar y enlace para registrarse.
Formulario de registro: (oculto por defecto) Campos para nombre, correo, contraseña y repetir contraseña, botón para registrar y enlace para volver al login.
Mensajes: Área para mostrar mensajes de error o información.
Redirección: Al iniciar sesión, redirige a index.html.

Metodos de validacion de correo:

En el registro (Login.html)
Correo electrónico:
Se usa el atributo HTML type="email" en el input, lo que valida automáticamente que el formato sea de correo electrónico (por ejemplo, que contenga un @ y un dominio).
El atributo required obliga a que el campo no esté vacío antes de enviar el formulario.
Contraseña:
El campo de contraseña también tiene el atributo required, por lo que no puede estar vacío.


En el formulario de contacto (index.html)
Correo electrónico:
El input tiene type="email" y required, lo que valida que el usuario escriba un correo válido y que el campo no esté vacío.
Además, hay mensajes personalizados de error usando Bootstrap (data-sb-validations="required,email" y mensajes en <div class="invalid-feedback">).
En el script personalizado, también se valida que el correo contenga un @ antes de mostrar el mensaje de éxito.

capturas de previsualizacion:

Login.html  
![image](https://github.com/user-attachments/assets/7fa17122-3ecf-4a55-8601-db6ad7651814)
![image](https://github.com/user-attachments/assets/caef22b7-266a-491c-8309-cdd64d883f59)
![image](https://github.com/user-attachments/assets/196ed4b9-e3b4-4771-8df2-b958aa637198)
