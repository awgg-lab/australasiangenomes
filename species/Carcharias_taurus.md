# **Grey Nurse Shark** *(Carcharias taurus)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

Note: assembly fCartau1_20232908 is a draft version of the grey nurse shark genome, fCartau2_20231112 is a final version of the grey nurse shark genome which was assembled using an additional PacBio HiFi Revio cell to obtain more data

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Carcharias_taurus/fCartau2_20231112.fasta.gz

```
<br>

| Assembly Statistics | fCartau1_20232908 | fCartau2_20231112 |
|:--- | --- | --- |
| Assembly    | PacBio HiFi | PacBio HiFi |
| Assembler program |  hifiasm v0.16.1-r375 | hifiasm v.0.19.8 |
| Genome size |4.69 GB | 4.42 GB |
| #contigs | 33,515 | 7,323 |
| Contig N50 | 0.27 Mb | 1.96 Mb |
| Largest Contig | 3.78 Mb | 18.46 Mb |

<br>

| BUSCO | v5.4.6 vertebrata odb10 | v5.4.6 vertebrata odb10 |
|:--- | --- | --- |
| Genome Assmebly | fCartau1_20232908 | fCartau2_20231112 |
| Genes    | 3354 |  3354 |
| Complete    | 85.2% | 91.6% |
| Single Copy |  73.9% | 88.3% |
| Duplicated | 11.3% | 3.3% |
| Fragmented | 7.8% | 4.0% |
| Missing | 7.0%  | 4.4% |

This genome data was supported by funding from the NCRIS supported Bioplatforms Australia Threatened Species Initiative and the University of Sydney. Computational resources were provided by Galaxy Australia, a service provided by the Australian Biocommons and its partners. We wish to acknowledge the use of the services and facilities of the Australian Genome Research Facility.
We thank the New South Wales Department of Fisheries for access to samples.


