# **Regent honeyeater** *(Anthochaera phrygia)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Anthochaera_phrygia/bAntphy.fgenesh.20231011.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Anthochaera_phrygia/bAntphy.global.20230913.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Anthochaera_phrygia/bAntphy1.pri.20221031.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Anthochaera_phrygia/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_magna/README-AWS.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Anthochaera_phrygia/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi |
| Assembler program |  hifiasm v0.16.1 |
| Genome size | 1.13 GB |
| #contigs | 1,453 |
| Contig N50 | 2.096 Mb |
| Largest Contig | 15.57 Mb |

<br>

| **BUSCO** | **v5.4.6 aves odb10** |  **v5.4.6 vertebrata odb10** |
|:--- | --- | --- |
| Genes    | 8,059 | 3,354|
| Complete    | 96.7% | 95.3% |
| Single Copy |  95.7% | 93.7% |
| Duplicated | 1.0% | 1.6% |
| Fragmented | 0.7% | 1.6% |
| Missing | 2.6% | 3.1% |


