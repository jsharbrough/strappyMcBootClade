# strappyMcBootClade

To run strappyMcBootClade type the following into a unix interpreter:
    
python strappyMcBootClade_vxxx.py <popFile.txt>

Where "xxx" refers to the version number. Current version is 1.3.
    

ASSUMPTIONS:

strappyMcBootClade only considers codons with 2 or fewer changes between them and 2 or 
fewer alleles at the codon of interest. For codons with 2 changes, pathway 
with fewest number of nonsynonymous changes is assumed. Sites with missing 
data are partially ignored by removing that sample from the codon-by-codon 
analysis. Codons with missing data are assumed to have 0.71875 synonymous 
sites and 2.28125 nonsynonymous sites. Missing nucleotides should be 
specified by 'N', missing amino acids will be specified by 'X'.
    
Citation Information:
    
Sharbrough et al. Inefficient purifying selection and variation in 
functional constraint drives accelerated but heterogeneous accumulation 
of harmful mutations in asexual lineages of a freshwater snail. In review.
