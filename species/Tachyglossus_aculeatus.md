# **Short-beaked echidna** *(Tachyglossus aculeatus)* 

[Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html#Ornithorhynchus_anatinus/) | 
Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Tachyglossus_aculeatus/echidnacruralglandtranscriptome_65percalign2026.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Tachyglossus_aculeatus/echidnaglobaltranscriptome_65percalign2026.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Tachyglossus_aculeatus/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Tachyglossus_aculeatus/README .
aws s3 sync --no-sign-request s3://threatenedspecies/Tachyglossus_aculeatus/ .
```

Reference guided short-beaked echidna global transcriptome and crural gland transcriptome generated from publicly availably short-beaked echidna RNA sequence data (SRR931704, SRR10530483, SRR10530484, SRR10530485, SRR10530487, SRR10530488, SRR10530489, SRR10530490, SRR10530491, SRR10530493, SRR34326942, SRR34326943, SRR34326944, SRR34326945, and SRR34326946). 

The data was aligned (>65% alignment) against the echidna reference genome mTacAcu1.pri (NCBI RefSeq assembly GCF_015852505.1).
