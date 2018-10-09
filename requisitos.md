# EXTRACCIÓN DE REQUISITOS

### Actores:

Aquí vamos a describir los actores que van a participar en nuestro sistema:
* Profesor, será el usuario que entre a la aplicacion y modifique los datos de los alumnos.
* Alumno, serán los usuarios que estaran registrados en el sistema.

### Datos del alumno:

Aquí vamos a detallar los datos que se van a guardar de cada alumno:
* DNI, será el DNI del alumno que tenemos guardado.
* Nombre, será el nombre del alumno que tenemos guardado.
* Apellido, será el apellido del alumno que tenemos guardado.
* Teléfono, será el telefono del alumno que tenemos guardado
* email_UCO, será el correo de la uco del alumno que tenemos guardado.
* Dirección, será la calle del alumno que tenemos guardado.
* Curso mas alto, será el curso más alto al que este matriculado el alumno.
* Fecha de nacimiento, será la fecha de nacimiento del alumno que tenemos guardado.
* Equipo, será el número del equipo al que pertenece el alumno que tenemos guardado.
* Líder o no, será una variable la cual nos dirá si el alumno es líder o no.

## Requisitos

### Requisitos funcionales:

-RF1. El sistema deberá poder buscar un alumno dentro de su base de datos. (Prioridad: 1)

-RF2. El sistema deberá tener la opción de poder introducir a un nuevo alumno en el sistema. (Prioridad: 2)
-RF3. El sistema deberá tener la opción de poder modificar a un alumno ya existente en el sistema. (Prioridad: 3)
-RF4. El sistema deberá tener la opción de poder eliminar a un alumno del sistema. (Prioridad: 3)
-RF5. El sistema deberá poder cargar datos procedentes de un fichero binario. (Prioridad: 4)
-RF6. El sistema deberá poder descargar datos procedentes de un fichero binario. (Prioridad: 4)
-RF7. El sistema deberá tener la opción de realizar una copia de seguridad de todos los datos del sistema. (Prioridad: 5)
-RF8. El sistema deberá tener la opción de imprimir por pantalla todos los alumnos del sistema, ordenados por la variable que el usuario desee, como el DNI, nombre, apellido o curso mas alto, de forma ascendente o descendente, a la vez tiene que generar un fichero MarkDown, donde vendra impresos los datos de los alumnos. (Prioridad: 6)
-RF9. El sistema deberá pedir obligatoriamente todos los datos del alumno, al introducir un nuevo usuario, excepto el equipo y si es líder o no. (Prioridad: 7)
-RF10. El sistema deberá pedir el DNI si al realizar una busqueda, se encuentra a más de un usuario. (Prioridad: 7)
-RF11. El sistema no deberá tener más de un lider por grupo. (Prioridad: 8)
-RF12. El sistema no deberá de autorrellenar los datos de un nuevo alumno. (Prioridad: 8)

### Requisitos no funcionales:

-RNF1. El sistema deberá de estar disponible para Linux. (Prioridad: 1)
-RNF2. El sistema deberá tener capacidad para un máximo de 150 alumnos. (Prioridad: 2)
-RNF3. El sistema deberá guardar toda la información en un fichero binario. (Prioridad: 3)
-RNF4. El sistema deberá tener una interfaz por línea de comandos. (Prioridad: 3)
-RNF5. El sistema solo podrá ser usado por el profesor. (Prioridad: 4)
-RNF6. El sistema no deberá de tener un límite de alumnos por equipo. (Prioridad: 4)
-RNF7. El sistema deberá estar codificado en c++. (Prioridad: 4)


