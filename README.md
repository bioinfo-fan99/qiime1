# qiime1
QIIME 
This pipelines has some of the default parameters changed in the otu picking method and clustering methods in order to make QIIME a bit lenient.
The BLAST parameters are also modified a bit and the e value is set to 1e-5 intead of 1e-10
Other changes are:
BLAST OTU pickeraligned_percent= 0.75
Sequence similarity threshold= 0.80
rev_strand_match= True
Percent identity threshold for cluster error detection= 0.80
Percent ID for mapping OTUs created by usearch= 0.80
Minimum length of sequence= 61
cdhit similarity= 0.70
