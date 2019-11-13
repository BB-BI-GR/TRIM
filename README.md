# TRIM
TRIM(Tandem Repeat Information Mining)

TRIM can mine tandem repeat intrevals of any motif length.

TRIM can be run as 

$TRIM input.fasta -k 7 > Output.txt


input.fasta file contains genome sequence from which TRIM extract tandem repeats with motif length k=7, as well as extract entropies of intervals of trails of TRs to form TRIM vector. 


Output.txt contains the TRIM vector corresponding to the genome sequence
