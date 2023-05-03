# Adobe ColdFusion 

[Coldfusion](https://www.adobe.com/products/coldfusion-family.html) de Adobe para el Backend.

```XML

<!--- DECLARO LA PARTE DE LOS DATOS --->
<cfset consulta_mis_datos = QueryNew("nombre_dev", "Varchar")>
<cfset QueryAddColumn(consulta_mis_datos, "direccion_dev", "Varchar")>
<cfset QueryAddColumn(consulta_mis_datos, "datos_dev", "Varchar")>
<cfset QueryAddRow(consulta_mis_datos, "Carlos,Toluca,Montaña")>

<!--- MUESTRO LOS DATOS EN PANTALLA --->
<cfoutput>
    <cfloop query="consulta_mis_datos">
        Nombre: #con_mis_datos.nombre_dev#<br>
        Direccion: #con_mis_datos.direccion_dev#<br>
        Datos: #con_mis_datos.datos_dev#
    </cfloop>
</cfoutput>
```
