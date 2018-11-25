# Nombre: Cargar Fichero

ID: 06

**Breve Descripción**: El sistema deberá cargar los datos de un fichero binario que el profesor quiera.

**Actores Principales**: Profesor

**Actores Secundarios**: 

**Precondiciones**:

   * El profesor no deberá tener los datos del fichero binario en el sistema.

**Flujo Principal**:

   1. El caso de uso empieza cuando el profesor selecciona la opción de "Cargar fichero".

   2. El sistema le preguntará al usuario el fichero binario donde están los datos que desea cargar.

   3. El usuario le indicará cual es el fichero con esos datos.

   4. El sistema carga en memoria todos los datos del fichero.

**Postcondiciones**:

   * La memoria tiene que tener todos los datos del fichero.

**Flujos alternativos**:

   * El sistema dará un mensaje de error si no encuentra el fichero deseado.
