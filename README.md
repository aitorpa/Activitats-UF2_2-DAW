# Activitats-UF2_2-DAW

## OPTIMIZACIÓN

### HEDIONDEZ DEL CÓDIGO

Según el diccionario hediondez está definido como “MAL OLOR”, “HEDOR” por lo que podemos decir que cuando algo no tiene buen olor es un claro indicio que de algo no está bien, es un indicador de problemas, alerta y precaución, algo que muchas veces resulta molesto y desagradable. Y más técnicamente hablando, en programación, la **hediondez del código** (code smell en inglés, o también conocido por código que huele o apesta) es cualquier síntoma en el código fuente de un programa que posiblemente indica un problema más profundo, se basa en indicar deficiencias en el diseño que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro.

#### ANÁLISIS DE CÓDIGO
Antes de mostrar sus diferentes formas de analizar código, aclaro que es, el análisis de código es un proceso de revisión del código mediante el que se pretende evaluar dicho código. Dicha evaluación supone la búsqueda de problemas de funcionamiento del mismo código y pretende mejorar su funcionamiento.
Existen dos tipos de análisi de códigos, **los dinámicos y los estáticos**, mientras que los _dinámicos_ (ejemplo unit tests) se realiza mientras el código se está ejecutando. Es más lento y necesita un proceso completo de testeo. Sin embargo, permite ver muchos errores que quedan ocultos en un análisis estático. En cambio los _estáticos_ (ejemplo linters como C) presenta frente al dinámico la ventaja de que se hace sin ejecutar el código. Como no necesita de esa ejecución, el análisis estático permite detectar errores en una fase muy temprana de la escritura. Así se ahorra mucho tiempo en fases posteriores del desarrollo. El problema más grave que ofrece en cambio, es que puede arrojar positivos que no lo son y cuya falsedad solo se verá durante la ejecución del código.

#### CONTINUOUS INSPECTION O CONTINUOUS ANALYSIS
Existen dos sitios web que ofrecen inspección de código, **Scrutinizer & SonarQube**, _Scrutinizer_ soporta tanto PHP, Python como Ruby con 14 das iniciales gratuitos y _SonarQube_ que puede llegar a soportar más de 20 lenguajes que puede usarse gratiutamente o pagar 5 dólares más por funciones extras.

![image](https://user-images.githubusercontent.com/74070906/110681939-a7066580-81da-11eb-8258-aa71031228b4.png)

#### REFACTORIZACIÓN

La refactorización podría compararse con la corrección de un libro: el producto final de la corrección no es un nuevo libro, sino el mismo texto, pero más comprensible. Así, al igual que en la corrección de un libro se usan procedimientos como la reformulación y la reestructuración o eliminación de frases, en la refactorización de código se aplican métodos como la encapsulación, el reformateo o la extracción para optimizar el código sin cambiar su contenido.

## DOCUMENTACIÓN

Diferenciando los tipos de documentación, nos encontramos 3, documentación de código, técnica y de usuario. Para ello, necesitaremos establecer un formato de documentación como bien ya puede ser:
- HTML (p. ej. Javadoc)
- Markdown (p. ej. Gitbook)
- reStructuredText (p. ej. Readthedocs)
- asciiDoc

![image](https://user-images.githubusercontent.com/74070906/110683583-79bab700-81dc-11eb-86cb-74658e93d430.png)

## CONTROL DE VERSIONES

Los sistemas más conocidos dentro de lo que es "control de versiones" (es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante):

- CVS
- Subversion
- Mercurial
- Git

![image](https://user-images.githubusercontent.com/74070906/110684346-56443c00-81dd-11eb-923f-485ef4aefd8b.png)
