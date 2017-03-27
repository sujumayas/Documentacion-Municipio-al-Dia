## Buscador de Normas Legales

Sección que contiene una base de normas legales referidas a la gestión municipal, desde el marco general hasta temas específicos. Esta sección es actualizada mensualmente.

Esta sección se ha construido con herramientas integradas en el desarrollo de Wordpress mismo. Se creó un custom posttype con custom fields \(usando [ACF](https://www.advancedcustomfields.com/)\). Y aparte del query simple de normas legales \(que retorna TODAS las normas legales ordenadas por fecha de publicación de la norma\), se construyó una solución de buscador con AJAX.

![](/assets/normas legales.png)

**Los siguientes templates y archivos han sido utilizados:**

* **/includes/functions/posttypes.php**
  * Definición del Posttype de las Normas Legales
* **/includes/functions/acf\_tweaks.php**
  * En este template están todos los hooks que se han utilizado para modificar la librería de ACF \(Advanced Custom Fields\). 
* **/includes/functions/taxonomies.php**
  * Definición de taxonomías para las normas legales. 
* **/includes/functions/ajax-normas.php**
  * File que recibe la llamada de Ajax de normas legales \(buscador\) y retorna la data necesaria. 
* **/archive-legalrule.php \(no utilizado en front, reemplazado por page-legalrule.php\)**
  * No se utiliza. 
* **/page-legalrule.php **
  * Buscador de Normas legales. 
* **/single-legalrule.php**
  * Template singular para cuando se ingresa a una norma legal. 



