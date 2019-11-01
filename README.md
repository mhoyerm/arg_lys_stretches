Arg-lys stretches

Searches for stretches containing a certain number of arginines and/or lysines, in a stretch of 10 amino acids in a protein.

Usage:

python arg_lys_stretches.py -F proteome.fasta -O output.csv -L 10 -N 8 -P 999999 -I 0

-F [required]: Fasta archive containing proteins list

-O [required]: Output file in csv format

-L [optional]: Lenght of the stretch, default is 10

-N [required]: Insert wanted number of arginines or lysines

-P [optional]: Position of the last amino acid of each protein to be searched for

-I [optional]: Position of the last amino acid of each protein to be searched for
