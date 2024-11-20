# COMPLETAR  
Con docker compose aprendí a estructurar archivos YAML para definir servicios, redes y volúmenes además, comprendí cómo orquestar múltiples contenedores de manera eficiente.
Para esto, hay que llenar correctamente los archivos YAML para evitar errores, porque al momento que se manda incluso un ":" mal, el compose de este archivo no se ejecuta bien y hay que estar muy pendiente de los datos que hemos ingresado al momento de modificar este archivo. 
Y se implementó verificaciones de estado para garantizar que los servicios estén en funcionamiento antes de iniciar dependencias, mejorando la confiabilidad de los despliegues también se utilizó, redes de tipo bridgepara conectar servicios de manera aislada.

También, configuré PostgreSQL como base de datos para SonarQube, incluyendo variables de entorno esenciales y mapeo de volúmenes para la persistencia de datos.
