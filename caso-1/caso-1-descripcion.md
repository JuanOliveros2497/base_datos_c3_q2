# Obtener de manera ordenada la lista de vistas y modulos a los que tiene acceso un rol en estado activo.

 - role[name=> rol, route => ruta]
 - module[name=> modulo, route => paquete]

´´´sql

 SELECT 
        * 
    FROM 
        persona p
    ORDER BY p.nombre
---