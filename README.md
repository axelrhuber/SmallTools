Genetics
========

Small tools for genetics research
See the [Small tools Manifesto](https://github.com/pjotrp/bioinformatics)

count_temolmeres.py:
  Extracts reads containing telomeric sequences from BAM files using [SAMBAMBA](http://lomereiter.github.io/sambamba/).
  Stores these in a sam file for further processing.
  Now performs a simple line count and provides the total read count of the BAM to generate a normlised telomer count.
  
Annotate_CADD_Scores_In_VCF.py:
  Annoates variants in a VCF file with [CADD scores](http://cadd.gs.washington.edu/score) using the [precomputed](http://cadd.gs.washington.edu/download) files provided by  the University of Washington .
  It uses multiprocessing to distribute tabix lookup commands over different processes.
  
  
Hope they help.
If you have suggestions or improvements let me know.  
