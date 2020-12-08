prob_Budyko_tx (probabilistic Budyko)
=====================================

Este repositorio representa la realización (**plantilla** o *template*) del **documento de tesis** (de maestría) titulada: "Vulnerabilidad de la disponibilidad de los recursos hídricos en el Perú frente al cambio climático: Análisis probabilístico de Budyko". La vista en formato *.pdf* se encuentra en https://www.overleaf.com/read/rvxdjrbcqkwf, y el código (scripts) de esta investigación en https://github.com/adrHuerta/prob_Budyko.

Formato de documento
---------------------
La tesis se realizo mediante `Overleaf <https://overleaf.com>`__ (editor colaborativo de *LaTeX* basado en la nube) siguiendo el reglamento de `tesis <http://pmrh-unalm.com/wp-content/uploads/2018/09/Reglamento-de-Tesis.pdf>`__ de la `Universidad Nacional Agrararia La Molina (UNALM) <http://www.lamolina.edu.pe/>`__. El documento ha sido aceptado por la `Escuela de Posgrado <http://www.lamolina.edu.pe/postgrado/>`__, por lo que sigue todos los detalles del formato en forma automática.

Sin embargo, a la fecha existen tres puntos que no pude automatizar:

- Espacio en cada inicio de capítulo.
- No numeración en cada inicio de capítulo y página que contenga una Tabla o Figura.
- Índice de Anexos

Lo anterior se resolvió manualmente, por lo que no tiene gran impacto en la rapidez de elaboración del documento. Si tienes forma de acoplar lo anterior, ¡por favor házmelo saber! 

Utilización
------------
Para hacer uso de este documento (plantilla o *template*) para tu propia **tesis** (**proyecto, pregrado, maestría y doctorado**) en la `UNALM <http://www.lamolina.edu.pe/>`__, y solo enfocarte en el contenido del mismo... sigue lo siguiente:

1. Crea tu cuenta en Overleaf mediante https://www.overleaf.com?r=e00506ba&rm=d&rs=b
2. Copia este proyecto (es decir, https://www.overleaf.com/read/rvxdjrbcqkwf) a tu propia cuenta mediante: **Menu** / **Actions** / **Copy Project**
3. Dale un nombre al proyecto copiado y ¡avanza tu tesis!

Si eres familiar a *LaTeX*, entonces será muy fácil usar Overleaf. Si no es así, te sugiero que revises la `wiki de Overleaf <https://es.overleaf.com/learn/latex/Tutorials>`__. Si eres del tipo que aprende con los errores, entonces no dudes modificar (y ver los resultados), igual puedes copiar tantas veces el proyecto original.

El orden que se propuso para la redacción de la tesis fue la siguiente:

1. Un archivo principal donde se tiene la redacción del documento en sí y en donde se invoca el resto de archivos (**main.tex**).
2. Una vez la tesis sea aceptada, se puede tener el resumen de la tesis y la ficha de firmas de los asesores las cuales se encuentran en **abstract.tex** y **head.tex** respectivamente.
3. Las referencias (**ref.bib**) y el formato del mismo (**apalikeADR.bst**) se encuentran dentro de la carpeta *References*.
4. Las imágenes o figuras en formato .png (puede ser otro formato) están almacenadas en la carpeta *Images*. Debido a que las figuras y tablas pueden ocasionar mucho espacio en **main.tex**, estás se generaron previamente en *FigsANDTables* en formato .tex para luego ser invocado en **main.tex**.

Agradecimientos
----------------
La idea de esta plantilla o *template* es para facilitar la vida de los *tesistas*. Inicialmente fue diseñado mediante TeX Live, pero fue actualizado (y mejorado) utilizando Overleaf. Si realizas tu tesis con esta plantilla, no olvides agradecer a Overleaf y vincular este repositorio (https://github.com/adrHuerta/prob_Budyko_tx).

Referencias
------------
1. Huerta , A. (2020). Vulnerabilidad de la disponibilidad de los recursos hídricos en el Perú frente al cambio climático: análisis probabilístico de" Budyko". Universidad Nacional Agraria La Molina. http://repositorio.lamolina.edu.pe/handle/UNALM/4503

2. Huerta, A. (2020). Actual evapotranspiration at Peru scale (2003-2013) (Version 1). figshare. https://doi.org/10.6084/m9.figshare.13270391.v1 (http://repositorio.lamolina.edu.pe/handle/UNALM/4503)