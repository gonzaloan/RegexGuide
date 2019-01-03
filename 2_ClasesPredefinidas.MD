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
https://github.com/gonzaloan/RegexGuide/blob/master/1_Caracter_(.)%2CMD

#Clases Predefinidas
- Para encontrar sólo los dígitos: **\d**. Aquí selecciona todos los números, dejando las letras sin seleccionar. También se puede poner [0-9]. Es equivalente, pero esta opción es más potente, ya que permite cambiar el rango, por ejemplo [6-9].

- Otra notación importante es el **\w**. Esto nos devuelve todos las letras y dígitos, pero sólo eso, es decir, sólo dígitos, y letras minúsculas y Mayúsculas. Sin tildes. También podemos usar **[a-z]** Buscando todos los caracteres de la a a la z minúsculas. y podemos **[a-zA-Z]** para buscar minúsculas y mayúsculas. Finalmente si ponemos **[a-zA-Z0-9]** se asemeja la funcionalidad de **\w**. Y también más poderoso, agregando búsquedas de guiones o puntos **[a-fA-F0-9_\.]** Esto encuentra letras de la a a la z, min y mayúsculas, incluye guiones bajos y puntos.


- **\s** busca los espacios.

- 