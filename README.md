# Sr35_gene_editing
This is a project of CRISPR-Cas9 gene editing of the stem rust resistance gene Sr35
The Sr35_gDNA file contains the full length Sr35 gene sequence including the introns
The first step is to identify intron-exon boundaries(and/or reading frames) in order to have a more certain exon target. 
Step 4 can be done on the program called ApE available at http://biologylabs.utah.edu/jorgensen/wayned/ape/
The next step is identifying sequnces to target within the coding region. We selected a sequence upstream of the first exon of the Nucleotide-Binding dormain sequence (5'U), one within the upstream region of the second exon (5'CDS) and one downstream of the whole coding region (3'CDS). 
We designed guide RNA using those three sequences using the free CRISPR-Cas guide RNA design tool http://www.rgenome.net/cas-designer/ and determined the chances of off-target mutations using the same tool
The gRNA sequences' primers were designed and cloned into two plasmids (B module for both 5'U and 5'CDS gRNAs and C module for the 3'CDS)
