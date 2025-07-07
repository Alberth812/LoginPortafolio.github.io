# LoginPortafolio.github.io
Portafolio web con login 

![image](https://github.com/user-attachments/assets/8ca8cf22-a3d1-4563-8849-7911dfdc554a)

Para el siguiente trabajo de programacion web elaboramos un portafolio web a partir de una plantilla, sin embargo debiamos complementar elementos y crear nuevos con los conocimientos previamente adquiridos en trabajos anteriores y lo aprendido en clase.

Descripcion de proyecto.

El proyecto es un portafolio web personal con un sistema de inicio de sesión. Incluye una página principal de login (Login.html) donde los usuarios pueden iniciar sesión o registrarse, asl iniciar sesion nos redirecciona a la pagina (index.html) que muestra información sobre mi, habilidades, proyectos y un formulario de contacto. El diseño utiliza Bootstrap para la apariencia responsiva y moderna, e integra imágenes y logos almacenados en la carpeta assets/img/.

Menús que la componen
index.html: El menú de navegación principal incluye:

Inicio
Sobre mí
Proyectos
Contacto
Login.html: solo es un formulario de login/registro.

Plantilla utilizada
El proyecto utiliza la plantilla "Start Bootstrap Grayscale" para la página principal (index.html), que es un tema moderno y responsivo basado en Bootstrap.
Para el login, se usa Bootstrap 5 y estilos personalizados, pero no una plantilla específica de login, sino un diseño propio con Bootstrap.

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
No hay validaciones adicionales en el frontend para la fortaleza de la contraseña ni para comparar que ambas contraseñas coincidan (esto se podría agregar si lo deseas).

En el formulario de contacto (index.html)
Correo electrónico:
El input tiene type="email" y required, lo que valida que el usuario escriba un correo válido y que el campo no esté vacío.
Además, hay mensajes personalizados de error usando Bootstrap (data-sb-validations="required,email" y mensajes en <div class="invalid-feedback">).
En el script personalizado, también se valida que el correo contenga un @ antes de mostrar el mensaje de éxito.

Capturas de previsualizacion:

Login.html  
![image](https://github.com/user-attachments/assets/7fa17122-3ecf-4a55-8601-db6ad7651814)
![image](https://github.com/user-attachments/assets/caef22b7-266a-491c-8309-cdd64d883f59)
![image](https://github.com/user-attachments/assets/196ed4b9-e3b4-4771-8df2-b958aa637198)

index.html (Portafolio)
![image](https://github.com/user-attachments/assets/16db69ee-645f-4d60-8955-5299aa5be8ba)
![image](https://github.com/user-attachments/assets/ef7d7e05-f577-4b20-bd91-2714c119a392)
![image](https://github.com/user-attachments/assets/57828a5c-25b1-4bca-9889-e136ad4b67fd)
![image](https://github.com/user-attachments/assets/224c3bfd-1944-43b8-ae8e-bb411d652115)
