# Desafio1-Backend

¡Bienvenido al primer desafío del modulo Backend con Node y Express!

Este programa te permite registrar citas de pacientes para una clínica veterinaria. Utiliza Node.js y archivos JSON para almacenar los datos.

¿Cómo utilizar?

Para empezar, asegúrate de tener Node.js instalado en tu computadora.

   Puedes utilizar las siguientes operaciones:
   
      * Registrar
      * Leer
      * Vaciar
      
   Registrar: Para registrar una nueva cita, utiliza el siguiente comando:
   
    node index.js registrar [nombre] [edad] [animal] [color] [enfermedad]

    [nombre]: Nombre del paciente.
    [edad]: Edad del paciente.
    [animal]: Tipo de animal.
    [color]: Color del animal.
    [enfermedad]: Enfermedad del paciente.

  Leer: Para leer todas las citas registradas, utiliza el siguiente comando:

    node index.js leer

  Vaciar: Para vaciar todas las citas registradas, utiliza el siguiente comando:

    node index.js vaciar

¿Cómo funciona?

El programa utiliza el módulo fs de Node.js para manejar los archivos JSON que contienen los datos de las citas.

El archivo operaciones.js contiene las funciones necesarias para realizar las operaciones de registro, lectura y vaciado. 

La función registrar valida que todos los campos necesarios estén presentes antes de agregar una nueva cita al archivo JSON. 

La función leer lee todo el contenido del archivo JSON y lo muestra en la terminal. 

La función vaciar borra todo el contenido del archivo JSON.

¡Gracias por leer!
