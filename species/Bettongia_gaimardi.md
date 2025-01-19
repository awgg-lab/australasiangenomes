# **Eastern Bettong** *(Bettongia gaimardi)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | [NCBI Accession: PRJNA1095660](https://www.ncbi.nlm.nih.gov/bioproject/1095660)

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.2.hap1.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.2.hap2.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.0.dipnr.gemoma.cds.fna .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.0.dipnr.gemoma.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.0.dipnr.gemoma.proteins.faa .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/bettong.v1.0.dipnr.rrna.gff .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/README .
aws s3 sync --no-sign-request s3://threatenedspecies/Bettongia_gaimardi/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | Short read + 10x Genomics |
| Assembler program |  Supernova |
| Genome size |3.46 GB |
| #contigs | 91,460 |
| Contig N50 | 87.36 Kb |
| Largest Contig | 956.31 Kb |
| #scaffold | 26,623 |
| Scaffold N50 | 2.93 Mb |
| Largest Scaffold |15.08 Mb |

<br>

| **BUSCO** | **v5.4.3 mammalia odb10** |  **v5.4.3 vertebrata odb10** |
|:--- | --- | --- |
| Genes    | 9,226 | 3,354|
| Complete    | 96.7% | 96.9% |
| Single Copy |  92.2% | 92.9% |
| Duplicated | 2.8% | 4.0% |
| Fragmented | 1.8% | 2.0% |
| Missing | 6.0% | 1.1% |

The authors would like to acknowledge computational resource support from: Galaxy Australia, a service provided by the Australian Biocommons and its partners; the University of Sydney’s High Performance Computing facility Artemis provided by the Sydney Informatics Hub; the University of New South Wales Katana High Performance Computing (doi:10.26190/669X-A286). Support for DNA sequencing was provided through the Oz Mammals Genomics (OMG) Initiative consortium (https://ozmammalsgenomics.com/consortium/), which was funded by Bioplatforms Australia through the Australian Government National Collaborative Research Infrastructure Strategy.

The eastern bettong reintroduction was conducted as part of and with support of the “Mulligans Flat – Goorooyarroo Woodland Experiment” (https://www.coexistenceconservationlab.org/mulligans-flat-goorooyarroo-woodland-experiment). Thanks to the ACT Government and Woodlands and Wetlands Trust and their staff for their support for the eastern bettong reintroduction project at Mulligans Flat Woodland Sanctuary. Thanks to Brittany Brocket for the initial DNA extraction.

