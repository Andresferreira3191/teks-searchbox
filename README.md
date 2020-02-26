# teks-searchbox
Repositorio destinado a alojar los desarrollos relacionados al searchbox y al buscador SQL de Magento 2.3.1, basado en el theme Electro.

Hacer Fork del proycto y enviar Merge Request, a la rama develop. O bien, crear ramas específicas para cada featured o avance a subir.

Todas las clases CSS e identificadores deben tener el prefijo "gsb-"
ejemplo, id="gsb-mi-input" class="gsb-clase-del-input"

Sobre archivos SQL:

el archivo core_config_data.sql contiene la configuración general de la tienda. Necesitas sustituir las las filas 2 y 3 de este archivo e incluir la ruta del front end de tu servidor local, ej: localhost:8080/

La linea 167 de este archivo incluye los estilos customizados respaldados en la DB.

Carpeta design:

Descomprimir la carpeta design.zip dentro de la carpeta app del proyecto Magento,
eje: xamp/htdocs/mi-proyecto-magento/app/

En esta carpeta se encuentran los estilos personalizados de la web.

A continuación los enlaces requeridos.

Carpeta Drive con todos los archivos requeridos:
https://drive.google.com/drive/folders/15QmAfo6w9ofMfYQgWDqCgG5-KgHhznE5?usp=sharing

Esta carpeta contiene:
1)el tema original con sus módulos requeridos (tema.zip),
2)arhivo con la configuración requerida para el php.ini del servidor local (ini.txt),
3)carpeta con los módulos de terceros instalados en la web de producción (modulos.zip), esta carpeta es opcional, para verificar compatibilidad.
4)archivo core_config_data.sql, el cual debe ser importado en la db local (necesitarás modificar la url base, ubicada en las filas 2 y 3 de esta tabla SQL)
5)Carpeta design.zip, la cual debe ser descomprimida dentro de la carpeta app del proyecto. Esta carpeta incluye los estilos personalizados del web.

Documentación del Tema Electro:
https://docs.alothemes.com/m2/theme/electro/
