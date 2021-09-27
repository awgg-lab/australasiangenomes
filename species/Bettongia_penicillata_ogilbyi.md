# **Woylie** *(Bettongia penicillata ogilbyi)* 

[Genome & Transcriptomes ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp s3://threatenedspecies/Bettongia_penicillata_ogilbyi/Betpen_md5sum.txt .
aws s3 cp s3://threatenedspecies/Bettongia_penicillata_ogilbyi/mBetpen.global.20210916.fasta.gz .
aws s3 cp s3://threatenedspecies/Bettongia_penicillata_ogilbyi/mBetpen1.pri.20210916.fasta.gz .
aws s3 cp s3://threatenedspecies/Bettongia_penicillata_ogilbyi/mBetpen1.pri.20210916.gff3.gz .
aws s3 cp s3://threatenedspecies/Bettongia_penicillata_ogilbyi/WoylieReadMe.txt .
aws s3 sync s3://threatenedspecies/Bettongia_penicillata_ogilbyi/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi & 10X Genomics |
| Assembler program |  IPA version 1.1.2 & 10X Genomics Long Ranger v2.2.2 |
| Genome size | 3.39 GB |
| #contigs | 3,016 |
| Contig N50 | 1.99 Mb |
| # scaffolds | 1,116 |
| Scaffold N50 | 6.94 Mb |
| Largest Scaffold | 35.6 Mb |
| Largest Contig | 12.02 Mb |
| % Genome in Scaffolds | 99.59% |
| % Gaps | 0.4% |

<br>

| **BUSCO** | **v3.1.0** | **v4.0.6** |
|:--- | --- | --- |
| Genes    | 4915 | 8338 |
| Complete    | 92.1% | 86.5% |
| Single Copy |  90.5% |  85.1% |
| Duplicated | 1.6% |  1.4% |
| Fragmented | 2.0% |  3.3% |
| Missing | 11.5%  |  4.6% |
