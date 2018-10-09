# test-BIOL633
script -a

grep probeset_id sed_temp.txt > id.txt

\s+
\n OR \r

C2Cplate\d_\D\d+_


\.CEL_call_code


head -2 sample.gff3

grep 'exon\|CDS' sample.gff3 > sample.gtf

cat header.txt sample.gtf > sample2.gtf

ID=
gene_id 

gene_id cds\.
gene_id 

\.exon1;
;

gene_id (Gene\S+)::g\.\S+;
gene_id \1;

;Parent=(\S+)
; transcript_id \1
# https://www.biostars.org/p/79202/
# accessed 25 Sept. 2018
# Vivek Krishnakumar
# USE: perl removeSmallCmtd.pl 200
# contigs.fasta > testL200.fasta
#!/usr/bin/perl
perl -v

perl -e ‘print “Hello World\n"'

perl      -e       ‘print    “Hello World\n"' #spaces everywhere

perl -e ‘print Hello World\n' #interpretive quotes are important

perl removeSmallCmtd.pl 200 sequences.fasta > testL200.fasta

grep –c ‘>’ testL200.fasta

grep –c ‘>’ sequences.fasta

perl SeparateSNPfiles.pl SNPlist.txt sed_temp.txt

wc -l SNPlist.txt

wc –l sed_temp.txt.toss.txt

wc –l sed_temp.txt.keep.txt

rm sed_temp.txt.*

perl SeparateSNPfiles.pl SNPlist.txt sed_temp.txt

wc –l sed_temp.txt.keep.txt

perl SeparateSNPfiles.pl SNPlist.txt sed_temp.txt

wc –l sed_temp.txt.keep.txt

python3

print("Hello, World!")

exit()

which python3

./addAntn2.py

ls

cat mod.gff3
