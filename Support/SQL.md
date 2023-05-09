
# Microsoft SQL Server

[Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2022) manejador de base de datos.

```SQL
--> Ejemplo:
CREATE TABLE miTabla (
    columna1 INT,
    columna2 VARCHAR(50),
    columna3 DATE
);

BULK INSERT miTabla
FROM 'C:\datos.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

SELECT *
FROM miTabla;
```
