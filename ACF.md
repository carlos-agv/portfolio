<cfoutput>
    <cfloop query="con_mis_datos">
        <cfset nombre = con_mis_datos.nombre_dev>
        <cfset nombre = con_mis_datos.direccion_dev>
    </cfloop>
</cfoutput>