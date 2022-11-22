# **Lister's gecko** *(Lepidodactylus listeri)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | 

[Publication:]()  Tristram O. Dodge, Katherine A. Farquharson, Claire Ford, Lisa Cavanagh, Kristen Schubert, Molly Schumer, Katherine Belov, Carolyn J. Hogg, Genomes of two Extinct-in-the-Wild reptiles from Christmas Island reveal distinct evolutionary histories and conservation insights, BioRxiv (preprint)

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/Leplis_md5sum.txt .
aws s3 cp --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/rLeplis1.global.20221122.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/rLeplis1.pri.20221122.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/rLeplis1.fgenesh.20221122.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/README-AWS.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Lepidodactylus_listeri/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly | PacBio HiFi + HiC |
| Assembler program | hifiasm v0.16 |
| Genome size | 2.35 GB |
| #contigs | 381 |
| Contig N50 | 72.29 Mb |
| #scaffolds | 401 |
| Scaffold N50 | 119.9 Mb |
| Largest Scaffold | 159.32 Mb |
| Largest Contig | 159.32 Mb |
| % genome in scaffolds | 96.2% in scaffolds > 10 Mb |

<br>

| **BUSCO** | **v5.4.3 vertebrata odb10** |
|:--- | --- |
| Genes    | 3354 |
| Complete    | 97.6% |
| Single Copy |  96.3% |
| Duplicated | 1.3% |
| Fragmented | 0.9% |
| Missing | 1.5% |

This genome data was supported by funding from the Threatened Species Initiative (TSI), NCRIS funded Bioplatforms Australia, and the Australian Research Council Centre of Excellence for Innovations in Peptide and Protein Science (CE200100012). Image was supplied by Lisa Cavanagh, Taronga Conservation Society Australia.
