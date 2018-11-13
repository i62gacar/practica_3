# Nombre: Introducir nuevo alumno

ID: 02

**Breve Descripción**: El sistema deberá cargar añadir un nuevo alumno al fichero

**Actores Principales**: Profesor

**Actores Secundarios**: Alumno

**Precondiciones**:

   * fgkfmgf
   * sdsd

**Flujo Principal**:

   1. El caso de uso empieza cuando el usuario le pida al sistema la opción de "introducir nuevo alumno".

   2. El sistema pide al profesor que introduzca el DNI, nombre, apellido, teléfono, email de la uco, dirección, curso mas alto, fecha de nacimiento, equipo y lider del alumno.

   3. El profesor introduce todos los datos obligatoriamente, excepto el grupo y si es lider o no.

   4. El sistema busca si el DNI introducido no esta en el sistema.

   5. El sistema guarda todos los datos del nuevo alumno.

**Postcondiciones**:

   * El sistema tendra los datos del nuevo alumno.

**Flujos alternativos**:

   * El sistema detecta que el DNI ya esta en el sistema y lo notifica con un mensaje de error.


