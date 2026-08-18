# **Platypus** *(Ornithorhynchus anatinus)* 

[Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html#Ornithorhynchus_anatinus/) | 
Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/platypuscruralglandtranscriptome_65percalign2026.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/platypusglobaltranscriptome_65percalign2026.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/README_2026 .
aws s3 sync --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/ .
```
Reference guided platypus global transcriptome and crural gland transcriptome generated from publicly availably platypus RNA sequence data (SRR065183, SRR065184, SRR065185, SRR065186, SRR065187, SRR065188, SRR065189, SRR065190, SRR306724, SRR306725, SRR306726, SRR306727, SRR306728, SRR306729, SRR306730, SRR306731, SRR306733, SRR306734, SRR306736, SRR306738, SRR306740, SRR306741, SRR414996, SRR414997, SRR414998, SRR5412222, SRR5412223, SRR5412224, SRR5412225, SRR5412226, SRR5412227, SRR5412228, SRR5412229, SRR5412230, SRR5412231, SRR5412232, SRR5412233, SRR5412234, SRR5412235, SRR5412236, SRR5412237, SRR5412238, SRR5412239, SRR5412240, SRR5412241, SRR649381, SRR649382, SRR649383, SRR649384, SRR943349, SRR943350, SRR38740941, SRR38740942, SRR38740943, SRR38740944, SRR38740945, SRR38740946, and SRR38740947). The data was aligned (>65% alignment) against the platypus reference genome mOrnAna1.pri.v4 (NCBI RefSeq assembly GCF_004115215.2).

*OLD*

```
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/platypuscruralglandtranscriptome_75percalign2025.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/platypusglobaltranscriptome_75percalign2025.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/README_2025 .
aws s3 sync --no-sign-request s3://threatenedspecies/Ornithorhynchus_anatinus/ .
```

These are a reference guided platypus global transcriptome and crural gland transcriptome generated from publically availably platypus RNA sequence data (SRR065183, SRR065184, SRR065185, SRR065186, SRR065187, SRR065188, SRR065189, SRR065190, SRR306725, SRR306726, SRR306727, SRR306728, SRR306730, SRR306731, SRR306734, SRR306736, SRR414996, SRR414997, SRR414998, SRR5412222, SRR5412223, SRR5412224, SRR5412225, SRR5412226, SRR5412227, SRR5412228, SRR5412229, SRR5412230, SRR5412231, SRR5412232, SRR5412233, SRR5412234, SRR5412235, SRR5412236, SRR5412237, SRR5412238, SRR5412239, SRR5412240, SRR5412241, SRR649381, SRR649382, SRR649383, SRR649384, SRR943349, and SRR943350)
The data were aligned against platypus reference genome mOrnAna1.pri.v4 (NCBI RefSeq assembly GCF_004115215.2) with a 75% inclusion rate and used in https://doi.org/10.1186/s12864-025-12299-x

