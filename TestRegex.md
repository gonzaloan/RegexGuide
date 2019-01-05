1
12
123
1234
12345
123456
1234567
12345678910
12345678910a
13432135
hola tambien
palabra

Este test será reemplazando el texto superior.

# . 
Si reemplazamos el regex **.** por un guión, el resultado es que todo caracter es un guión.
-
--
---
----
-----
------
-------
-----------
------------
--------
------------
-------

# Delimitador * 

Si reemplazamos el regex **[.*]** por un guión, el resultado será  
-
-
-
-
-
-
-
-
-
-
-
-
-
#Delimitador ?
Buscará donde haya cero o más. Por ejemplo haciendo el reemplazo de **\d?** buscará donde haya cero o más caracteres numéricos. Por eso al principio de cada linea igual hace un reemplazo
-
--
---
----
-----
------
-------
-----------
------------a
--------
-hola tambien
-palabra

#Delimitador +
Buscará donde haya uno o más dígitos. 

-
-
-
-
-
-
-
-
-a
-
hola tambien
palabra