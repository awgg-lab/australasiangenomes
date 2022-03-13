# **Woylie** *(Bettongia penicillata ogilbyi)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | [NCBI Accession: 	PRJNA763700](https://www.ncbi.nlm.nih.gov/bioproject/763700)

[Publication:](https://doi.org/10.46471/gigabyte.35)  Emma Peel, Luke Silver, Parice Brandies, Carolyn J. Hogg, Katherine Belov, A reference genome for the critically endangered woylie, Bettongia penicillata ogilbyi, Gigabyte, 1, 2021

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

This genome data was supported by funding from the Australian Research Council Centre of Excellence for Innovations in Peptide and Protein Science (CE200100012) and Discovery Project (DP180102465), and the Presbyterian Ladies' College Sydney. Image was supplied by Sabrina Trocini.
