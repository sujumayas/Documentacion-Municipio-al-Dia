## Calendario de Obligaciones {#calendario-de-obligaciones}

El calendario de Obligaciones está hecho para que Municipio al Día publique obligaciones municipales que vencen en los 2 meses siguientes a la fecha actual. De esta forma los gobiernos regionales planifican correctamente el cumplimiento de las mismas. Este calendario es un archivo simple con un Date-picker que ejecuta una búsqueda en el cliente mismo.

**Ojo**: El formato de retorno de la fecha de las obligaciones no puede ser cambiado sin revisar el apartado sobre [Integración con Mailchimp](/extras/integracion-con-mailchimp.md).

![](/assets/Calendario Municipal.png)

**Los siguientes templates y archivos han sido utilizados:**

* **/includes/functions/posttypes.php**
  * Definición del Posttype de los eventos. 
* **/page-evento.php**
  * Este es el Archive de las obligaciones. Cuando el proyecto inició, esta página era para nombrar todo tipo de eventos futuros, pero luego se cambió a  “solo obligaciones“.
* **/single-evento.php **\(antiguo\)
  * Este es el template singular, que dejó de usarse en el 2017. 



