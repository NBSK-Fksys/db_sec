# **TableSpace**

TABLEESPACE 
```sql
CREATE TABLESPACE [NOMBREDELATALBE] 
DATAFILE '[RUTA_AL_DATAFILE]' 
SIZE [TAMAÑO][K-M-G] 
AUTOEXTEND ON 
NEXT 10M 
MAXSIZE 2024M; 
```

TEMPORAL TABLEESPACE 
```sql
Create tablespace temp_tbs
tempfile 'ruta_al_archivo'
size 50M 
AUTOEXTEND on 
next 1M
maxsize 500M;
```



USER
````sql
CREATE USER usuario_ejemplo
IDENTIFIED by asd1234
Default tablespace tbs_ejemplo
temporary tablespace temp_tbs
quota 10M on tbs_ejemplo 


-- si no se coloca el tablespace default y el temporal ... la info se guardara en el sys y lo ideal es que nunca se mezcle usuarios admin con los comunes en las carpeta system --

-- si no se establecen quotas se usara todo el espacio del tablespace --
````

COMMIT---> guarda los cambios 

INSERT


ROLES Y PRIVILEGIOS 
````
GRANT CREATE SESSION TO USUARIO_EJEMPLO; 
GRANT CREATE TABLE TO [USUARIO];
GRANT CREATE ANY TABLE TO [USUARIO];

GRANT UNLIMITED TABLESPACE TO USUARIO_EJEMPLO;


QUOTA UNLIMITE ON [TABLESPACE] (QUOTA ILIMITADA)




