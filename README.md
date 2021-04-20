# Ejercicio práctico aplicación completa con RoR


Se desea desarrollar una aplicación para administrar los turnos de una clínica médica.
Para lo mismo se necesita administrar los datos del doctor, especialidad, paciente y consulta. 

Considera las siguientes relaciones:
 1. Un doctor (nombre y apellido)  tiene una especialidad (tiene nombre) y una especialidad tiene muchos doctores
 2. Una consulta pertenece a un doctor y a un paciente. Guardar fecha de la consulta.
 3. Un paciente (nombre y apellido)  tiene muchas consultas.
 4. Un doctor tiene muchas consultas.

Consideraciones generales:
 1. Modificar el formulario de consulta médica para que permita seleccionar un doctor y un paciente desde un combo.
 2. Utilizar estilo bootstrap para las vistas de la aplicación
 3. Crear un menu horizontal (navbar) con acceso al index de todos los recursos en el layout de la aplicación
 
 Modificar la lista de especialidades agregando lo siguiente:
 1. Columna con la cantidad de doctores que posee la especialidad
 2. Columna con la cantidad consultas de la especialidad
 3. Modificar el dato de las columnas agregadas en el punto a y b para que sean enlaces a la lista correspondiente filtrando por especialidad.

Modificar la lista de doctores agregando los siguientes datos:
 1. Columna con el nombre de la especialidad.
 2. Columna con la cantidad de consultas.
 3. Modificar el dato de la columna agregada en el punto b para que sea un enlace a las consultas filtradas por doctor.

Modificar el listado de consultas agregando los siguientes puntos.
1. Columna con el nombre completo del paciente.
2. Columna con el nombre completo del doctor.
3. Agregar un formulario de búsqueda que permita filtrar la búsqueda por el nombre del doctor o paciente. La búsqueda se puede hacer por cualquiera de los dos campos.

Extra:
1. Paginar los resultados del listado de doctores utilizando ActiveRecord. (NO HECHO)

