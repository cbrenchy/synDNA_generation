# synDNA_generation
Generates synthetic DNA sequences:
- of a specified length and GC content, 
- defines 8 insert fragments (hard-coded strings that look like 16S segments) with intended insertion positions relative to the original base,
- ensures no internal restriction sites (EcoRI GAATTC, NheI GCTAGC, AvrII CCTAGG) exist inside the body of the sequence, 
- flanks EcoRI sites,
- writes everything to a FASTA file

-------------------------------------------------------------------------------------------------------------------------------------------------------

## Libraries loaded:
Biostrings (used to build/write sequences)

-------------------------------------------------------------------------------------------------------------------------------------------------------
*Output is append-mode: rerunning with the same parameters will keep adding sequences to the same FASTA unless you delete/rename it first.*
