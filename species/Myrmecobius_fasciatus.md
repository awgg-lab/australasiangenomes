# **Numbat** *(Myrmecobius fasciatus)* 

[Genome & Transcriptomes ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp s3://threatenedspecies/Myrecobius_fasciatus/Myrfas_md5sum.txt .
aws s3 cp s3://threatenedspecies/Myrecobius_fasciatus/mMyrfas.global.20211206.fasta .
aws s3 cp s3://threatenedspecies/Myrecobius_fasciatus/mMyrfas1.pri.20211206.fasta.gz .
aws s3 cp s3://threatenedspecies/Myrecobius_fasciatus/mMyrfas1.pri.20211206.gff3.gz .
aws s3 cp s3://threatenedspecies/Myrecobius_fasciatus/NumbatReadMe.txt .
aws s3 sync s3://threatenedspecies/Myrecobius_fasciatus/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi & 10X Genomics |
| Assembler program |  IPA version 1.1.2 & 10X Genomics Long Ranger v2.2.2 |
| Genome size | 3.42 GB |
| #contigs | 219,447 |
| Contig N50 | 0.037 Mb |
| # scaffolds | 112,299 |
| Scaffold N50 | 0.223 Mb |
| Largest Scaffold | 35.6 Mb |
| Largest Contig | 12.02 Mb |
| % Genome in Scaffolds | 99.59% |
| % Gaps | 3.52% |

<br>

| **BUSCO** | **v3.1.0** | **v4.0.6** |
|:--- | --- | --- |
| Genes    | 4915 | 8338 |
| Complete    | 92.1% | 86.5% |
| Single Copy |  90.5% |  85.1% |
| Duplicated | 1.6% |  1.4% |
| Fragmented | 2.0% |  3.3% |
| Missing | 11.5%  |  4.6% |
