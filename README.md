# grupo bioinfo-genomIkiam

> En este repositorio pondremos todo el material colaborativo a medida que trabajamos en nuestros proyectos bioinformáticos grupales a distancia. 

para empezar
---

Los programas que necesitan tener instalados y funcionando en sus computadores locales son: 

- [Github Desktop](https://desktop.github.com/) o [Git for Windows](https://gitforwindows.org/)
- [cmder](https://cmder.net/) (traductor de lenguage Windows a unix/shell/bash)
- [FASTQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) (generador de reportes de calidad de corridas de Illumina)
- [atom](https://atom.io/)
- [Typora](https://typora.io/)

Esto, para empezar. 

-------------

primera tarea bioinformatica
---

>**ACERCA DE LOS DATOS:** Estaremos reanalizando unos datos que [ya han sido analizados](https://github.com/pesalerno/Pseudacris-island-genomics) ya que salio una nueva version de un programa, [`stacks`](https://catchenlab.life.illinois.edu/stacks/), que se utiliza comunmente para alinear y genotipificar datos generados con representación reducida de genomas generados por medio de tags de enzimas de digestión (RADtags). Estaremos realizando permutaciones similares a las reportadas para [este proyecto](https://github.com/pesalerno/Hypsiboas-genomics), y evaluando el output (es decir, numero de loci obtenidos, de secuencias retenidas, etc) en comparación con la version anterior. Lo principal que queremos es evaluar algun cambio significativo en los resultados de genotipificacion que amerite reanalizar todo lo demas que se hizo con los datos. 

1. **Recordar/practicar línea de comando.** Estaremos trabajando en un **cluster/computador remoto** que está en Fort Collins, Colorado (donde vivi por cuatro años como postdoc donde jugue mucho en [la montaña](https://www.google.com/search?q=rocky+mountain+national+park&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjp1oXat7vqAhWtTd8KHdG8CpQQ_AUoAXoECBgQAw&biw=1413&bih=582)). Este supercomputador, llamado `correns`, es administrado por [Dan Sloan](https://scholar.google.com/citations?user=T3egfLkAAAAJ&hl=en) de Colorado State University, y corre bajo un "job scheduling system" llamado [`slurm`](https://slurm.schedmd.com/overview.html). Como todos los computadores remotos, corre bajo sistema operativo linux, por lo que deben [refrescar su conocimiento y manejo de linea de comando en bash](https://swcarpentry.github.io/shell-novice/) - para esto es que necesitaran el programa `cmder`. 

