# Bumble-Wasp-bGC
Biased GC gene conversion, Bombus impatiens and Polistes dominula

York University, Zayed Lab
Taeyoon You - honours thesis project
biased GC gene conversion testing in B.impatiens and P.dominula
Duration: Sept 2018 - March 2019

Chopped LD - Polistes.ipynb 
is a example file of analysis done on Polistes.
Same codes were used for B.impatiens, was copy&pasted and non-essential lines were removed for P.dominula.



polisteschopper.script.txt  
chops all contigs to 10k sized windows
uses list of contigs as reference.
this is same file used on Bombus, modifed.

pol_mass_ld.script.txt  
takes the 10k window files made from above to perform ld test using vcftools
conditions include --geno-r2, window of 60 bp as determined earlier.
for bombus, conditions were --hap-r2, window of 80 bp, with minor allele frequency cut off of 0.2 (--maf 0.2).

