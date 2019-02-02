Tabla de datos tomada de modelo:

https://excelsignum.com/2015/10/26/conectar-base-de-datos-de-excel-utilizando-herramienta-olebd-y-sql/comment-page-1/




Comentarios:

- Hemos cambiado la columna "2º idioma" por "segundo_idioma" ya que las etiquetas no pueden comenzar por un dígito.

- Subidos los siguientes documentos para validar conjuntamente:

   empleados_dtd.xml / empleados.dtd
   empleados_xsd.xml / empleados.xsd


- Ambas validaciones han sido correctas utilizando la web https://www.xmlvalidation.com/


- Las fechas las he cambiado de formato "31/02/2013" a "2013-02-31" porque el validador "date" no reconoce el formato "/". (date - Fechas en forma (AAAA-MM-DD))
  Una solución hubiera sido validar por partrones, pero pensé que eso no conservaba la esencia de lo que es una fecha. Referencia: https://stackoverflow.com/questions/13409567/xml-schema-change-date-format



