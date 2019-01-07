#Contadores

Se utiliza para ser específicos al buscar la información, es decir, cuántas ocurrencias queremos buscar.

Por ejemplo si estamos buscando 3 dígitos podríamos usar:
**\d\d\d** 
Lo cual está bien, pero qué pasa si necesitamos por ejemplo 10 dígitos, o más.

Para ello podríamos decir
**\d{2,2}**
Esto significa que buscamos dígitos, mínimo 2 y máximo 2.

También podemos poner un mínimo hasta el infinito
**\w{2,}** Esto muestra todos los caracteres minimo 2 y hasta el infinito.

Con esto se puede hacer cosas interesantes. Supongamos que tenemos varios formatos de teléfonos y queremos encontrar todos:
5556581111
56-85-45-65-65
45.54.11.22.36
Todos estos son válidos, podríamos encontrar todos utilizando:
**\d{2,2}[\-\.]?** Esto, hace que tome de rangos de dos números, y luego busque si hay guiones o puntos. El ? indica que puede o no haber dichos caracteres. Eso si, esto está buscando de dos en dos, y queremos todo el formato, por lo que podemos hacer es hacer esto la cantidad de veces que necesitamos el teléfoo, en este caso 5 veces.
**\d{2,2}[\-\.]?\d{2,2}[\-\.]?\d{2,2}[\-\.]?\d{2,2}[\-\.]?\d{2,2}[\-\.]?**
Y también podriamos usar los mismos contadores para hacer esta expresión
más legible **(\d{2,2}[\-\.]?){5,5}**

