# LoginPortafolio.github.io
Portafolio web con login 

![image](https://github.com/user-attachments/assets/8ca8cf22-a3d1-4563-8849-7911dfdc554a)

Para el siguiente trabajo de programacion web elaboramos un portafolio web a partir de una plantilla, sin embargo debiamos complementar elementos y crear nuevos con los conocimientos previamente adquiridos en trabajos anteriores y lo aprendido en clase.


link de descarga de la plantilla utilizada: https://startbootstrap.com/theme/grayscale


Descripcion de proyecto:
El proyecto es un portafolio web personal con un sistema de inicio de sesión. Incluye una página principal de login (Login.html) donde los usuarios pueden iniciar sesión o registrarse, asl iniciar sesion nos redirecciona a la pagina (index.html) que muestra información sobre mi, habilidades, proyectos y un formulario de contacto. El diseño utiliza Bootstrap para la apariencia responsiva y moderna, e integra imágenes y logos almacenados en la carpeta assets/img/.

Menús que la componen

Inicio:
Es el encabezado principal de la página.
Contiene el título "Mi Portafolio", un subtítulo y un botón "Get Started" que lleva a la sección "Sobre mí".
Sobre mí

Sección con información personal:
Incluye una tarjeta con foto de perfil, nombre, escolaridad, pasatiempos y una breve descripción personal.

Proyectos:
Muestra los proyectos realizados.
Cada proyecto tiene:
Una imagen representativa.
Un título ( Login, 3D, Render).
Una breve descripción del proyecto.
Los proyectos destacados son:
Login: Sistema de inicio de sesión con Bootstrap.
3D: Figuras tridimensionales con OpenGL.
Render: Modelado y renderizado en Blender.
Contacto

Formulario para enviar un correo electrónico.
Incluye validación de email y mensajes de éxito/error.
Muestra información de contacto adicional:
Dirección.
Correo electrónico.
Teléfono.
Enlaces a redes sociales (Twitter, Facebook, GitHub).

Metodo de validacion:
Correo electrónico de contacto:
El input tiene type="email" y required, lo que valida que el usuario escriba un correo válido y que el campo no esté vacío.
Además, hay mensajes personalizados de error usando Bootstrap (data-sb-validations="required,email" y mensajes en <div class="invalid-feedback">).
En el script personalizado, también se valida que el correo contenga un @ antes de mostrar el mensaje de éxito.

Capturas de previsualizacion:

Portafolio.html (Portafolio)
![image](https://github.com/user-attachments/assets/16db69ee-645f-4d60-8955-5299aa5be8ba)
![image](https://github.com/user-attachments/assets/ef7d7e05-f577-4b20-bd91-2714c119a392)
![image](https://github.com/user-attachments/assets/57828a5c-25b1-4bca-9889-e136ad4b67fd)
![image](https://github.com/user-attachments/assets/224c3bfd-1944-43b8-ae8e-bb411d652115)
