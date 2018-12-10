# Xochitonal
LABORATORIO DE BIOROBÓTICA, Facultad de Ingeniería UNAM.

Responsable: Daniel Garcés Marín

El proposito de este repositorio es almacenar el trabajo que se ha desarrollado en el proyecto Xochitonal, el cual tiene que objetivo desarrollar un robot móvil autónomo el cual cuente con características similares a los desarrolados en el proyecto justina, en términos de navegación autónoma y planeación de acciones, además de que cuente con una compatibilidad para trabajar con dispositivos Smart Things. 

Actualmente el proyecto cuenta con un robot móvil de seis ruedas cuyas características se encuentran explicadas en la documentación incluida en este repositorio. Pero en pocas palabras consta de un robot de tipo diferencial con 6 ruedas, una torre de fotoresistores, el módulo Smart Things, arduinos y una raspberry sobre la cual corre la arquitectura del proyecto.

=> DESCRIPCIÓN DE LAS RAMAS DE DESARROLLO:

-[SAFE_MODE]:: En esta rama solo se mantendrá el el workspace con la arquitectura y los nodos mas sencillos para la prueba del hardware con el que cuenta el robot; el principal objetivo es el revisar cada uno de los componentes disponibles en caso de probar con un nuevo roboto o el que se encuentre en uso presente algunos problemas de desempeño o funcioabilidad.

-[MASTER]:: En esta rama se guardarán la arquitectura y nodos que se han desarrollado y que han demostrado tener la eficiencia adecuada para cumplir con el comportamiento que se desea implementar el robot. En otras palabras, es el código que consideramos el más adecuado para implementar en el robot y que consiga los objetivos deseado.

-[DEVELOP]:: En esta rama se guardarán los archivos que se están desarrollando y probando, los cuales pueden contener algunos errores ya sea de programación y lógica, los cuales serán revisados e implmentados para poder ser aprobados y guardados en la rama MASTER.

- (Extras) :: (Este es una rama que está tentativamente a proponer, la cual tiene como objetivo el alamcenar algunos comportamientos que si bien no se encuentran entre los comportamientos y funcionabildades deseadas, se crearon bajo ciertas circunstancias y cumplen con los requisitos de calidad )

=> CONTENIDO DEL REPOSITORIO

-Workspace [catkin_ws] :: En esta carpeta se encuentra almacenada todo el software desarrollado hasta la fecha, el cual debe ser implementado en la tarjeta Raspberry Pi que se encuentra integrada al robot.

-Smart things [SmartThings_files] :: En esta carpeta se encuentra todo el software necesario para el uso del módulo Smart Things para la tarjeta arduino UNO. Así como el código original del nodo para ROS con el que se comenzó a implementar este módulo.

- Documentacion [Manual_Usuario_Xochitonal] :: Esta documentación describe el desarrolloo del robot, así como una rápida introducción a cada uno de los componentes disponibles y una serie de instrucciones para la instalación del software necesario. 

>>Actualización 8 de Diciembre del 2018

  >> -Se agregó el Documento/Manual donde se describe el proyecto y sus componentes, tanto en hardware como en Hardware.
  >> -Se agregó el Fichero comprimido del workspace que se encuentra en la Raspberry Pi. 
  >> -Se agregán el fichero comprimido que contiene todos los archivos originales para el uso del shield de Smarthings para el Arduino UNO.

