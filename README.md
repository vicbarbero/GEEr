# GEEr
GEEr es un Generador de Estadísticas de Evaluación para raíces. Es una aplicación que se ejecuta en tu navegador y procesa la exportación de datos de evaluación en formato .CSV, generando un informe de estadísticas que te permite obtener:
- el alumnado con calificación positiva o negativa en cada materia
- la distribución del alumnado por número de materias suspensas
- media de calificaciones por materia
- media de suspensos por alumno o alumna
- desviación de porcentaje de suspensos de materia, módulo o ámbito respecto a la media de aprobados
- distribución de alumnado por media de calificaciones y
- alumnado con mejor calificación media.

Para utilizar la aplicación, haz click sobre el botón verde *Code* y escoge la opción *Download ZIP*. Descomprime el fichero .zip que se descarga y haz doble click sobre el fichero *index.html*. Se abrirá una pestaña en tu navegador donde se ejecutará la aplicación.

GEEr no almacena ni envía por internet ningún dato que facilites. Utiliza únicamente el motor JavaScript de tu navegador. Se distribuye con licencia GPL.

# *Changelog*
- Versión actual disponible: v1.02 - publicada el 18/06/2024 - se corrige un error por el que el alumnado con media de 10 no aparecía ordenado correctamente en la relación de alumnado con mejores calificaciones.
- Versión disponible: v1.01 - publicada el 09/06/2024 - se calcula la media del porcentaje de alumnado que supera cada materia, módulo o ámbito y se muestra una tabla ordenando las materias, módulos o ámbitos respecto a la media. De esta forma, se facilita la elaboración de la memoria final de curso según modelo de la Subdirección General de Inspección Educativa de la Comunidad de Madrid.
- Versión disponible: v1 - publicada el 14/01/2023 - primera versión, modificando el catálogo de materias y ámbitos de ESO, Bachillerato presencial y Diversificación, además de una incidencia al procesar cadenas de apellidos, nombre de alumnado muy largas, truncadas por la exportación de raíces.
