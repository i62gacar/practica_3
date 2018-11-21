# Nombre: Introducir nuevo alumno

ID: 02

**Breve Descripción**: El sistema deberá cargar añadir un nuevo alumno al fichero

**Actores Principales**: Profesor

**Actores Secundarios**: Alumno

**Precondiciones**:

   * No hay dentro del sistema mas de 150 alumnos.
	* El alumno no debe de estar en el sistema.

**Flujo Principal**:

   1. El caso de uso empieza cuando el usuario le pida al sistema la opción de "introducir nuevo alumno".

   2. El sistema pide al profesor que introduzca el DNI, nombre, apellido, teléfono, email de la uco, dirección, curso mas alto, fecha de nacimiento, equipo y líder del alumno.

   3. El profesor introduce todos los datos obligatoriamente, excepto el grupo y si es líder o no.

   4. El sistema guarda todos los datos del nuevo alumno.

**Postcondiciones**:

   * El sistema tendrá los datos del nuevo alumno.

**Flujos alternativos**:

   * El sistema detecta que el DNI ya está en el sistema y lo notifica con un mensaje de error.

