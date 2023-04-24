Microsoft SQL Server para la gestion de datos.

```SQL
SELECT
    sqlServerDB AS HABILIDAD,
    dedicacion AS TRABAJO,
    bicicleta AS PASATIEMPO
FROM
    rutinaDeTodosLosDias
WHERE
    actitud LIKE '%positiva%'
    AND coffe = 1
```