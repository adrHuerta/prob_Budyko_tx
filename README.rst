prob_Budyko_tx (probabilistic Budyko)
==================================

La finalidad de esta tesis fue evaluar la vulnerabilidad de la disponibilidad de los recursos hídricos debido al cambio climático a través del enfoque bottom-up. La tesis sigue las ideas de dos principales trabajos: validación de la evapotranspiración actual (`Weerasinghe et al. 2020 <https://www.hydrol-earth-syst-sci.net/24/1565/2020/hess-24-1565-2020.html>`__) y aplicación del Budyko probabilístico (`Singh and Kumar 2015 <https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015GL066363>`__).

La vista en formato PDF se encuentra en <https://www.overleaf.com/read/rvxdjrbcqkwf>. y el código para la realización de esta investigación (`aqui <https://github.com/adrHuerta/prob_Budyko>`__).

Formato de documento
---------------------
La tesis se realizo mediante el editor online **LaTeX** `Overleaf <https://overleaf.com>`__ siguiendo el reglamento de `tesis <http://pmrh-unalm.com/wp-content/uploads/2018/09/Reglamento-de-Tesis.pdf>`__ de la `Universidad Nacional Agrararia La Molina - UNALM <http://www.lamolina.edu.pe/>`__. A la fecha existe tres puntos que no pude automatizar antes del preámbulo (no busque demasiado!):

1. Espació en cada inicio de capitulo.
2. No numeración en cada inicio de capitulo y pagina que contenga una Tabla o Figura.
3. Índice de Anexos

Lo anterior se puede solucionar manualmente, por lo que no tiene gran impacto en la rapidez de elaboración del documento. Si tienes forma de acoplar lo anterior, por favor házmelo saber! 

Uso
------------
Para hacer uso de este documento para tu propia tesis (proyecto, pregrado, maestría y doctorado) en la `UNALM <http://www.lamolina.edu.pe/>`__. Sigue lo siguiente:

1. Crea tu cuenta en Overleaf usando <https://www.overleaf.com?r=e00506ba&rm=d&rs=b>
2. Copia este proyecto <https://www.overleaf.com/read/rvxdjrbcqkwf> a tu propia cuenta mediante: **Menu** - **Actions** - **Copy Project**
3. Dale un nombre al proyecto copiado y avanza tu tesis!

Si eres familiar a **LaTeX**, entonces sera muy fácil usar Overleaf. Si no es así, te sugiero que leas la `wiki de Overleaf <https://es.overleaf.com/learn/latex/Tutorials>`__.

El orden que yo propuse para la redacción de mi tesis es la siguiente: Un archivo principal donde se tiene la redacción del documento en si y en donde se invoca el resto de archivos (**main.tex**), una vez la tesis sea aceptada, se puede tener el resumen de la tesis y la ficha de firmas de los asesores las cuales se encuentran en **abstract.tex** y **head.tex** respectivamente. Las referencias (**ref.bib**) y el formato del mismo (**apalikeADR.bst**) se encuentran dentro de la carpeta *References*. Las imágenes o figuras en formato .png (puede ser otro formato) están almacenadas en la carpeta *Images*. Debido a que las figuras y tablas pueden ocasionar mucho espacio en **main.tex**, estás se generaron previamente en *FigsANDTables* en formato .tex para luego ser invocado en **main.tex**.

Agradecimientos
---------------
Esto no pudo ser posible sin **Overleaf**.

Referencias
------------
1. Singh, R., and Kumar, R. (2015). Vulnerability of water availability in India due to climate change: A bottom‐up probabilistic Budyko analysis. Geophysical Research Letters, 42(22), 9799-9807.

2. Weerasinghe, I., van Griensven, A., Bastiaanssen, W., Mul, M., and Jia, L. (2020). Can we trust remote sensing ET products over Africa?, Hydrol. Earth Syst. Sci. Discuss., https://doi.org/10.5194/hess-24-1565-2020, 24(3), 1565-1586.