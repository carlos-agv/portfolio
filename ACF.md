# Adobe ColdFusion 

[CF](https://www.adobe.com/products/coldfusion-family.html) de Adobe para el Backend.

```XML
<cfset consulta_mis_datos = QueryNew()>
<cfoutput>
    <cfloop query="consulta_mis_datos">
        Nombre: #con_mis_datos.nombre_dev#<br>
        Direccion: #con_mis_datos.direccion_dev#<br>
        Datos: #con_mis_datos.datos_dev#
    </cfloop>
</cfoutput>
```
