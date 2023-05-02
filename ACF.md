<cfoutput>
    <cfloop query="con_mis_datos">
        <cfset nombre = con_mis_datos.nombre_dev>
        <cfset direccion = con_mis_datos.direccion_dev>
        <cfset datos = con_mis_datos.datos_dev>
    </cfloop>
</cfoutput>