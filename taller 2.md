# Laboratorio 02 - Alineamiento de secuencias
1. **¿Qué función cumple el gen SRY? [2]**
  - Factor determinante de los testículos, iniciando la diferenciación masculina. [LINK](https://www.ncbi.nlm.nih.gov/gene/6736)

2. **¿Cuántos genes ortólogos están anotados en esa base de datos? [1]**
  - 29 genes ortólogos [LINK](https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_6736[group])
3. **¿Qué es el EMBL-EBI? [2]**
  - Una plataforma online que desarrolla bases de datos, herramientas y software que hacen posible la alineación, además de verificar y visualizar los diversos datos producidos. creando una gran data a la vez disponible para el publico. 
 [link](https://www.ebi.ac.uk/about/our-impact)
4. **¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas? [2]**
  - MUSCLE (MUSCLE... "especially good with proteins")
  [LINK](https://www.ebi.ac.uk/Tools/msa/)

5. **¿Qué otros tipo de herramientas ofrece EMBL-EBI? [2]**
  - Multiple sequence alignment, Protein feature detection, Sequence motif recognition,Sequence similarity search, Protein function analysis, entre otras.
  [LINK](https://www.ebi.ac.uk/services)
6. **¿Cuál es el costo de abrir un gap? [1]**
  - 1.53
7. **¿Cuál es el costo de extender un gap? [1]**
  - 0.123

   [LINK 6 y 7](https://www.ebi.ac.uk/Tools/msa/mafft/)

8. **¿Cuál es la longitud total del alineamiento? [1]**
  - 1934 bases
9. **¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? [2]**
  - SRY_Piliocolobus_tephrosceles 0.00135
10. **¿Cuál es el más lejano? [2]**
  - SRY_Desmodus_rotundus 0.0973

11. **¿Cuál es la especie cuyo gen SRY es más cercana a la del burro? [2]**
  - SRY_Equus_przewalskii 0.00047 (Caballo salvaje)
  -[LINK 9, 10 Y 11](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-171043-0177-8926314-p2m&analysis=phylotree)

12. **¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye? [3]**

  - Si se disminuye el costo de un gap, seria más largo el alineamiento. Por el contrario si es que aumenta el costo. Esto debido a que al ser una penalización más alta, la homología entre las secuencias no bastarían para llegar a un consenso en casos de gap's.

13. **¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? [3]**

  - Al aumentar el costo de la extensión de un gap se hace más corta la secuencia consenso. y si disminuye, lo contrario. debido a que las secuencias con gap's muy extensos no se toman en cuenta.

14. **¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? [2]**

  -  La longitud disminuyó a 1895 nucleótidos, lo que quiere decir que, las secuencias son menos homologables bajo esos parámetros.

15. **Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento. [2]**

  - Aumentó a 2017 nucleótidos. es menos restrictiva y deja secuencias con gap's muy extensos. 

16. **Agrega a tu informe una lista de los "LEFT PRIMER" y "RIGHT PRIMER" que obtuviste usando Primer3. [3]**

| LEFT PRIMER   | RIGHT PRIMER    |
| ------------- | ------------- |
| __AGAGTGAAGCGACCCATGAA__ | TCTCTGTGCATGGCCTGTAA|
| TTACAGGCCATGCACAGAGA  | CTTGAGTGTGTGGCTTTCGT |
| GGATAGAGTGAAGCGACCCA | TTTCTCTCTGTGCATGGCCT |
| AGATGCTGCCGAAGAATTGC| **GCTTTGTCCAGTGGCTGTAG** |
| CGAAGATGCTGCCGAAGAAT | CTACAGCTTTGTCCAGTGGC |.

17 . **Indica los partidores forward y reverse que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. [5]**

  - Están en negrita en la tabla anterior. los escogí por que es la combinación de primers que cubre la mayor parte del gen, haciendo un amplicon más grande, a la vez sus T°m son la misma y además cumple con todos los parámetros que nos da AmplifX

18 . **¿Cuál es el largo del amplicón? ¿Y la temperatura de annealing sugerida? [3]**

- Una longitud de 436 nucleótidos.   y la temperatura de annealing sugerida es de 55°C (temperaturas de fusion iguales).




