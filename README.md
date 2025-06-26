# missouri-trout-genetics
Genetic analyses of Missouri Rainbow Trout

This repository has multi-snp haplotype (micro-haplotype) data and code for figure generation associated with: Origins and Population Genetics of Self-sustaining Rainbow Trout (_Oncorhynchus mykiss_) in Missouri. [placeholder for DOI]

## Directories and files

data/Supplemental Table S1 Haplotype Data.csv
  - Numerically coded multi-snp haplotype/microhaplotype data.   

Figure-2.Rmd - R Markdown file that generates Figure 2.   
   - uses a genind object data/obj.rda
   - uses a list of populations data/calinoaa.rda (and writes that as a .csv meta/cali-noaa-samples.csv). 
   - uses tree-labels.csv in /meta/ to annotate the tree.    
   

/Figure-2/ - contains the base figure used for Figure 2 in the associated paper, created by Figure-2.Rmd.    

/outputs/Figure-2/ - alternative tree constructions generated in preparation of the manuscript.    

