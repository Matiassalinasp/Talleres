### Laboratorio 03 - Ensamblaje de genomas y predicción de genes

**1. ¿Cuántos Sequencing Projects y Analysis Projects hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? [2]**

  - *Sequencing projects*
  
    - Complete Projects 14.956

    - Permanent Drafts 125.997

    - Incomplete Projects 71.945

    - Targeted Projects 1.107


  - *Analysis Projects*

    - Genome Analysis 110.157 

    - Metagenome Analysis 33.928 

    - Metagenome - Cell Enrichment 1.044 

    - Metagenome - Single Particle Sort 3.742 

    - Metagenome - Assembled Genome (MAG) 8.844

    - Metatranscriptome Analysis 3.967

    - Combined Assembly 175

    - Single Cell - Screened (SAG) 2.250

    - Single Cell - Unscreened (SAG) 1.951

    - Transcriptome Analysis 519


[LINK](https://gold.jgi.doe.gov/statistics)

**2 ¿Cuál es el dominio más representado en la base de datos, archea, bacteria, eukaryote, o virus? [1]**

  - Es de bacterias.
![DOMINIO BACTERIA](https://github.com/Matiassalinasp/imagenes/blob/master/Captura.JPG?raw=true)-

**3. ¿Cuáles son los phyla más representados entre los proyectos de genomas bacterianos en la base de datos? [1]**

 - Proteobacteria
 - Firmicutes
 - Actinobacteria
 - Bacteroidetes
 - Cyanobacteria
 - Spirochaetes 
 - Tenericutes
 - Chlamydiae
 - Fusobacteria.
 
 [LINK](https://gold.jgi.doe.gov/statistics)
 
 **4. ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) [1]**

 - Medical
 - Environmental
 - Agricultural
 - Evolution
 - Pathogen
 - Human Pathogen
 - Human
 - Microbiome
 - Project (HMP)... etc.
 
[LINK](https://gold.jgi.doe.gov/statistics)

**5. ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) [2]**

  - The bonobo genome compared with the chimpanzee and human genomes
 [Artículo](https://www.nature.com/articles/nature11128)
 

**6. Explica, qué es el N50, L50, y NG50. [3]**

  - N50: es la mitad del largo de la longiutud de la secuenciacion, es decir, una mediana o media.
  - L50: es el menor numero de cotings, donde su longitud se iguala a N50.
  - NG50: es la mitad del largo de la longitud del genoma conocido, es decir una mediana o media.

**7. ¿Cuál es el propósito de calcular estas estadísticas? [3]**

  - Estas ayudan a comparar diferentes secuencias de diferentes especies. logrando informaciones valiosas de las longitudes y cotings.

**8. ¿Cuántos contigs conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los contigs) [3]**

  - Number of contigs	: 121,356

  - Contig N50:	 66,676

  - Contig L50:	 11,048



[LINK](https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2)

**9. ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?**

  - largo total: 3,286,643,896
  - % GC : 42.3185
  
[LINK](https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2) y [2°LINK](https://www.ncbi.nlm.nih.gov/genome/?term=txid9597[Organism:noexp])

**10. ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?**

  - The genome was assembled using the open-source Celera Assembler software29
  
  
[LINK](https://www.nature.com/articles/nature11128)

**11. Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [start] y término [stop])? [3]**

| ORFs     | Hebra     | Largo (nt/aa)| sobreposición|
| ------------- | ------------- | ------------- |------------- |
| 1 |   + | 909/302|no|
|2 | + | 78/35| a 4|
|3| +| 99/32| a 5|
|4|-|441/146|no|
|5|-|405/134|no|
|6|-|84/27| a 4|
|7|-|144/47| a 1|.

[LINK](https://www.ncbi.nlm.nih.gov/orffinder/)

**12. ¿Qué tipo de programa es ORFfinder, Ab initio o por homología? [2]**

  -  Es Ab initio, por que no necesita de una base de datos.
  
**13. ¿A qué organismo pertenece la secuencia en cuestión? [2]**

  - Haemophilus influenzae
  
[LINK](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

**14. ¿Qué gen(s) está(n) codificados en la secuencia? [2]**

  - formate dehydrogenase accessory protein FdhE [Haemophilus influenzae] 
  - DNA polymerase III subunit PSI
  - peptide N-acetyltransferase 

[LINK](https://blast.ncbi.nlm.nih.gov/Blast.cgi#alnHdr_491962129)


**15. Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? [3]**

  - el ORF 1, 4 y 5 son correctos.







