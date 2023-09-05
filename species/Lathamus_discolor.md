# **Swift Parrot** *(Lathamus discolor)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Lathamus_discolor/Latdis_md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Lathamus_discolor/bLatdis.global.20233108.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Lathamus_discolor/bLatdis.pri.20231708.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Lathamus_discolor/bLatdis.fgenesh.20230209.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Lathamus_discolor/README-AWS.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Lathamus_discolor/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi |
| Assembler program |  hifiasm v0.16.1-r375 |
| Genome size | 1.24 GB |
| #contigs | 847 |
| Contig N50 | 18.97 Mb |
| Largest Contig | 78.39 Mb |

<br>

| **BUSCO** | **v5.4.6 vertebrata odb10** |
|:--- | --- |
| Genes    | 3354 |
| Complete    | 96.5% |
| Single Copy |  94.9% |
| Duplicated | 1.6% |
| Fragmented | 0.9% |
| Missing | 2.6%  |

This genome data was supported by funding from the NCRIS supported Bioplatforms Australia Threatened Species Initiative. Computational resources were provided by the Australian FGENESH++ Service provided by the Australian BioCommons and the Pawsey Supercomputing Research Centre with funding from the Australian Government and the Government of Western Australia; Galaxy Australia, a service provided by the Australian Biocommons and its partners; and the University of Sydney’s High Performance Computing facility Artemis provided by the Sydney Informatics Hub. We wish to acknowledge the use of the services and facilities of the Ramaciotti Centre for Genomics, UNSW and of the Australian Genome Research Facility. 
Thanks to Bonorong Wildlife Sanctuary and the Department of Natural Resources and Environment Tasmania, particularly Margie Morrice, Sarah Michael and Rachael Alderman for facilitating access to genetic samples
