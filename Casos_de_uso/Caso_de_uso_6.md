# Nombre: Descargar Fichero

ID: 06

**Breve Descripción**: El sistema deberá descargar los datos de un fichero binario que el usuario quiera.

**Actores Principales**: Usuario
**Actores Secundarios**: Fichero Binario

**Precondiciones**:

   * El usuario no deberá tener los datos del fichero binario en el sistema.

**Flujo Principal**:

   1. El caso de uso empieza cuando el usuario le pida al sistema de descargar unos datos de un fichero binario.

   2. El sistema le preguntará al usuario el fichero binario donde están los datos que desea descargar.

   3. El usuario le indicará cual es el fichero con esos datos.

**Postcondiciones**:

   * El sistema una vez identificado el fichero, descargará y mostrará los datos al usuario.

**Flujos alternativos**:

   * El usuario podrá cancelar el proceso cuando lo desee.
   * El sistema dará un mensaje de error si no encuentra el fichero deseado.
