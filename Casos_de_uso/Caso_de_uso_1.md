# Nombre: Buscar Alumno

ID: 01

**Breve Descripción**: El sistema deberá buscar a un usuario en el fichero

**Actores Principales**: Profesor

**Actores Secundarios**: -

**Precondiciones**:

   * 

**Flujo Principal**:

   1. El sistema le pide al profesor el DNI o el apellido de la persona que esta buscando.

   2. El profesor introduce el DNI o el apellido.

   3. Si se ha introducido el apellido y hay mas de un alumno con el mismo apellido.

   	3.1. El sistema pide un DNI.

   	3.2. El profesor introduce un DNI .

   	3.3. El sistema comprueba que el DNI esta entre los alumnos con el mismo apellido.

   	3.4. Mientras el DNI no este entre esos alumnos.

   		3.4.1. El sistema pide un nuevo DNI.

   		3.4.2. El profesor introduce un nuevo DNI.

   		3.4.3. El sistema comprueba si el DNI esta entre esos alumnos.

  4. El sistema devuelve los datos del alumno que ha encontrado.

**Postcondiciones**:

   * El sistema devuelve los datos del alumno.

**Flujos alternativos**:

   * Si no se ha encontrado un alumno devulve un mensaje de error.


