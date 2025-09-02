# synDNA_generation
Generates synthetic DNA sequences of:
- a specified length and GC content, 
- splices in a set of predefined 16S rRNA fragments at fixed positions, 
- ensures no internal restriction sites (EcoRI GAATTC, NheI GCTAGC, AvrII CCTAGG) exist inside the body of the sequence, 
- flanks EcoRI sites, and writes everything to a FASTA file

# Libraries loaded: 
Biostrings (used to build/write sequences)

**Output is append-mode: rerunning with the same parameters will keep adding sequences to the same FASTA unless you delete/rename it first.**
