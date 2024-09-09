# **Regent honeyeater** *(Anthochaera phrygia)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | [NCBI Accession: PRJNA1145263](https://www.ncbi.nlm.nih.gov/bioproject/1145263)

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

This work was funded by the NCRIS supported Bioplatforms Australia Threatened Species Initiative and the University of Sydney. Computational resources were provided by; the Australian FGENESH++ Service provided by the Australian BioCommons and the Pawsey Supercomputing Research Centre with funding from the Australian Government and the Government of Western Australia; Galaxy Australia, a service provided by the Australian Biocommons and its partners; and the University of SydneyÃ¢â‚¬â„¢s High Performance Computing facility Artemis provided by the Sydney Informatics Hub. We wish to acknowledge the use of the services and facilities of the Ramaciotti Centre for Genomics, UNSW and of the Australian Genome Research Facility.
Thanks to Jo Day and Taronga Zoo for provisions of the samples used to generate the genome and transcriptomes
