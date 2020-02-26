# teks-searchbox
Repositorio destinado a alojar los desarrollos relacionados al searchbox y al buscador SQL de Magento 2.3.1, basado en el theme Electro.

Hacer Fork del proycto y enviar Merge Request, a la rama develop. O bien, crear ramas específicas para cada featured o avance a subir.

Todas las clases CSS e identificadores deben tener el prefijo "gsb-"
ejemplo, id="gsb-mi-input" class="gsb-clase-del-input"

Sobre archivos SQL:

el archivo core_config_data.sql contiene la configuración general de la tienda. Necesitas sustituir las las filas 2 y 3 de este archivo e incluir la ruta del front end de tu servidor local, ej: localhost:8080/

La linea 167 de este archivo incluye los estilos customizados respaldados en la DB.
