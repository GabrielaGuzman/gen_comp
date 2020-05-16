# Comandos de la Práctica 03
## Gabriela Guzmán Favila

01. mkdir gguzman_p03
02. touch comandos_p03.md

## Parte I.

 1.1 ¿A qué organismo pertenece? *Mycoplasma genitalium*
 
 1.2 ¿Es un gen o una región genómica de importancia? Es una parte del gen que codifica el ARNr 16s
 
 1.3 ¿Qué es un marcador molecular? Son regiones de ADN utilizadas para estudios taxonómicos y filogenéticos,debido a que presentan 
 características como una variabilidad significativa a nivel de especie y ubicarse entre sitios conservados (Valenzuela-González et al., 2015).
 
 1.4 ¿Cuál es la importancia de este tipo de marcador en particular? el ADN ribosomal 16s se encuentra en todos los organismos, con 
 la misma función. El gen contiene tanto regiones de alta variabilidad, que permiten clasificar a nivel de especie y cepa; así como 
 regiones conservadas, con las que se pueden implementar primers universales (Valenzuela-González et al., 2015).

02. | BLAST | Definición | Aplicación |
    | -- | -- | -- |
    | BLASTN | Comparar secuencias de nucleótidos con secuencias de nucleótidos | Análisis filogenético |
    | BLASTP| Comparar secuencias de aminoácidos, con secuencias proteicas de la base de datos |  |
    | BLASTX | Comparar secuencias de nucleótidos con secuencias proteícas | Busca las proteínas que codifican una secuencia  |
    | TBLASTX| Comparar todos los marcos de lectura de una secuencia respecto a los marcos de lectura de una base de datos | Verificar el efecto de mutaciones en el marco de lectura. |
    | TBLASTN | Comparar secuencias proteicas con secuencias de nucelótido de la base de datos | Buscar secuencias de nucleótidos que codifiquen para esa proteína |

03. La metodología del artículo consistió en tomar muestras de semen, sangre y tejido de adiposo de hombres delgados y hombres con obesidad, 
así como de hombres obesos sometidos a cirugía Rouwx-en-Y ( en distintas etapas). Se realizó una secuenciación de bisulfito, un análisis de 
posicionamiento de histonas y un SncRNA-Seq. Las lecturas de retención de histonas y se sncRNA de al menos 15nt se alinearon con Bowtie2 (Donkin et al., 2017).

## Parte II.

01. El problema de la ciudad de Königsberg consiste en encontrar una forma de recorrer 4 islas conectadas por 7 puentes, pasando por cada uno
de ellos sólo una vez. Según el método pensado por Euler, la condición necesaria para que tenga solución es que las islas con número de puentes 
impar sean de cero a dos. En el problema de la ciudad de Königsberg, las cuatro cuidades tienen un número de puentes impar, lo que hace necesario 
algunos puentes más de una vez, para poder ir a todas las islas.

02. Las tecnologías de nueva secuenciación generan miles de lecturas, en las gráficas de Bruijin estas lecturas se fragmentan en pedazos que van 
a representar los nodos, dando como resultado billones de estos. Los círculos Hamiltonianos no tienen el suficiente poder para un análisis con tantos
nodos. Por otra parte, el algoritmo de los círculos de Euler sí es capaz de realizar un análisis con muchos nodos, pero el tiempo del análisis depende 
de esto, por lo que ser requiere un gran poder de computo e implica mucho tiempo. 

03. Son estadísticas utilizadas para evaluar la calidad del ensamblaje. La estádistica N50 da la longitud del conting menor de los mayores, es decir, 
la longitud de los cotings ( acomodados de menor a mayor), que cubren la mitad de un genoma (Aguilar-Bultet y Falquet, 2015). Mientras que L50 es el 
número de cotings cuya suma de su longitud es N50. 


## Referencias 

Aguilar-Bultet, L. y Falquet, L. (2015) Secuenciación y ensamblaje de *novo* de genomas bacterianos: una alternativa para el estudio de nuevos patógenos.*Revista de Salud Animal*, 37(2). 

Donkin, I., Versteyhe, S., Ingerslev, L., Qian, K. Mechta, M., Nordkap, L., Mortensen, B., Appel., E., Jorgensen, N., Dristiansen, V., Hansen, T., Workman, C., Zierath, J. and Barres, R.(2017) Obesity and Baratric Surgery Drive Epigenetic Variation of Spermatozoa in Humans. *Cell Metabolism*, 23(2), 369-378.
