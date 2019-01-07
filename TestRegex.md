1
12
123
1234
12345
123456
1234567
12345678910
12345678910ac
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

Si reemplazamos el regex **[.*]** por un guión, el resultado será todo, porque de cada línea TODO está dentro de lo delimitado.
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
hola tambien*
palabra

#Contador
**\d{2,2}** buscará todo los lugares donde hayan dos dígitos seguidos y los reemplazará
1
X
X3
XX
XX5
XXX
XXX7
XXXXX0
XXXXX0ac
XXXX
hola tambien
palabra