#Recapitulación

\w - caracteres de palabras
\d - digitos
\s - espacios en blanco
[0-9] es similar a \d
[0-9a-zA-Z_] es similar a \w

#Delimitador * 
Si busco .* significa que buscará todos los caracteres. Como un sólo match. Si hucieramos sólo el ., esto encontrará cada caracter por separado.

* es todo.

#Delimitador +
Es uno o más. 


#Delimitador ?
es 0 o uno. 

##Podemos mezlar identificadores
Por ejemplo, siq ueremos buscar todas las coincidencias donde haya uno o más dígitos, y que termine en alguna letra, podríamos usar
**\d+[a-zA-Z]**


