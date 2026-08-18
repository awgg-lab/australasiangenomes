# **Southern corroboree frog** *(Pseudophryne corroboree)* 

[Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html#Ornithorhynchus_anatinus/) | 
Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)|[NCBI Accession: 	PRJNA1510867](https://www.ncbi.nlm.nih.gov/bioproject/114027)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/stringtie_merge_nrtrans.filtered.newheader.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/stringtie_merge_nrtrans.filtered.newheader.fasta.TD2.pep .
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/stringtie_merge_nrtrans.filtered.newheader.fasta.TD2.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/pred_amps_corrob_global_08.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Pseudophryne_corroboree/README .
aws s3 sync --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/ .
```
Reference guided corroboree frog global transcriptome generated from both publicly available (PRJNA921726) and recently generated southern corroboree frog skin RNA sequence data (PRJNA1510867). Data was aligned to the corroboree frog reference genome (GCA_028390025.1) and used to identify antimicrobial peptides
