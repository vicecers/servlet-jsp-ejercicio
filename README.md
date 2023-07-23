# servlet-jsp-ejercicios
Este proyecto está creado para guiar y capacitar al estudiante, en programación web en java utilizando Servlet y JSP.

### Ejercicios usando servlet
1. Escriba un Servlet para mostrar el mensaje de bienvenida en el navegador usando anotaciones/web.xml para mapear el Servlet.
2. Diseñe un formulario HTML para invocar un Servlet que debe capturar del lado del cliente el número de registro, el nombre y el apellido y mostrar lo mismo en el lado del cliente en formato HTML.
3. Escriba un programa Servlet para demostrar el uso de los métodos de HttpServletRequest y HttpServletResponse para mostrar información de encabezado.
4. Cree un formulario para ingresar los detalles de los estudiantes como registro, nombre, apellido, teléfono, educación y correo electrónico y muestre todos los valores de entrada de Servlet utilizando la clase de enumeración.
### Ejercicios usando servlet y base de datos
5. Escriba un programa Servlet para insertar un registro en la base de datos y mostrar "Registro insertado". si el registro se inserta correctamente o el mensaje "No se puede insertar un registro" si no tiene éxito. La base de datos es "EmpDb", el nombre de la tabla es "empleado" y los campos son empno, nombre, designación, teléfono.
6. Cree un programa Servlet para almacenar los detalles del producto y facilitar la consulta del producto específico. La base de datos es "ProdDb", el nombre de la tabla es "product" y los campos son p_id, p_name, p_price. La aplicacion debe mostrar un formulario de captura con un boton que envíe los datos al servlet usando el metodo post.
Se deben respetar los siguientes requisitos:
- La conexión a la base de datos se debe realizar en el método init() del servlet.
- Se debe permitir consultar datos por p_id, esta opción debe ser procesada por el método doGet() del servlet, el cual debe responder generando codigo html dinámico.
7. Cree un formulario en HTML para aceptar las calificaciones de los estudiantes en diferentes materias y guárdelo en la tabla denominada "notas" de la base de datos denominada "estudiante" en MySQL. La tabla "notas" debe tener los campos student_id, computing, math, english.
8. En la base de datos Estudiante cree la tabla "registro" con la siguiente estructura:
  - id int,
  - name varchar(30),
  - address varchar(30)
  - Inserte varios registros a la tabla.
9. Escriba un programa Servlet para conectarse a la base de datos y mostrar los registros de la tabla de "registro" de la base de datos de "estudiante".
### Ejercicios usando servlet y jsp
10. Escriba un programa Servlet para redirigir la URL mediante el método sendRedirect y la interfaz RequestDispatcher.
  - Cree un formulario de login con los campos usuario y contraseña (user = "admin" password = "123")
  - El servlet debe procesar los datos enviados desde el formulario.
  - En caso de ser incorrectos redirigir a la pagina error.jsp usando sendRedirect.
  - En caso de ser correctos redirigir a la pagina success.jsp usando RequestDispatcher. Debe mostrar el usuario y un mensaje de bienvenida.
11. Escriba un programa Servlet para demostrar el uso de los métodos setAttribute y getAttribute. 
12. 
