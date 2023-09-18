# **King Island scrubtit** *(Acanthornis magna greeniana)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

[Pre-print:](https://doi.org/10.22541/au.169471129.99174363/v1) Ross Crates, Brenton von Takach, Catherine M Young, Dejan Stojanovic, Linda Neaves, Liam Murphy, Daniel Gautschi, Carolyn J Hogg, Robert Heinsohn, Phil Bell, Katherine A Farquharson, Genomic insights into a critically endangered island endemic songbird provide a roadmap for preventing extinction, Authorea. September 14 2023.

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/Acamag_md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/bAcamag.global.20230524.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/bAcamag1.pri.20230524.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/bAcamag1.fgenesh.20230524.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/README-AWS.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Acanthornis_magna_greeniana/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi |
| Assembler program |  hifiasm v0.16.1 |
| Genome size | 1.48 GB |
| #contigs | 1,516 |
| Contig N50 | 7.715 Mb |
| Largest Contig | 60.595 Mb |

<br>

| **BUSCO** | **v5.2.2 aves odb10** |
|:--- | --- |
| Genes    | 8,338 |
| Complete    | 97.1% |
| Single Copy |  96.4% |
| Duplicated | 0.7% |
| Fragmented | 0.5% |
| Missing | 2.4% |

We acknowledge the traditional custodians of the land on which this research was conducted. This study was funded by the Commonwealth Department of Environment and Climate Change, BirdLife Australia and generous donors to the Difficult Bird Research Group. Sequencing received in-kind support from the NCRIS funded BioPlatforms Threatened Species Initiative. Research was conducted under Tasmanian Scientific licence #TFA23010, ANU animal ethics permit #A2021/33 and ABBBS banding authorities #3192 & #2833. Computational resources were provided by Amazon Web Services and RONIN; the Australian Biocommons supported FGENESH++ service; the Pawsey Supercomputing Research Centre with funding from the Australian Government and the Government of Western Australia; Galaxy Australia, a service provided by the Australian Biocommons and its partners; and the University of Sydney’s High Performance Computing facility Artemis. We thank Mark Carey, the King Island Conservation Action Plan working group, Sustainable Timber Tasmania, the Tasmanian National Parks and Wildlife Service & H. Camm & family for logistical support. KAF is supported by the Australian Research Council Centre of Excellence for Innovations in Peptide and Protein Science (CE200100012).
