# **Orange bellied parrot** *(Neophema chrysogaster)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | [NCBI Accession: 	PRJNA1140271](https://www.ncbi.nlm.nih.gov/bioproject/1140271)

[Publication:]

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp s3://threatenedspecies/Neophema_chrysogaster/bNeochry1.pri.20230906.fa.gz .
aws s3 cp s3://threatenedspecies/Neophema_chrysogaster/bNeochry_global_20230920.fa.gz .
aws s3 cp s3://threatenedspecies/Neophema_chrysogaster/bNeochry1_fgenesh_20231024.gff3.gz .
aws s3 cp s3://threatenedspecies/Neophema_chrysogaster/md5sum.txt .
aws s3 cp s3://threatenedspecies/Neophema_chrysogaster/README.txt .
aws s3 sync s3://threatenedspecies/Neophema_chrysogaster .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | bNeochry1.pri.20230906 | 
| Description |  HiFi reads assembled with hifiasm (0.16.2-r375) and HiC scaffolded with YaHs |
| Genome size | 1.32Gb | 
| #contigs | 2387 |
| contig N50 | 7.61Mb |
| # scaffolds | 2002 | 
| Scaffold N50 | 104.05Mb | 
| Largest Scaffold | 165.58Mb |

<br>

| **BUSCO** | **v5.4.6 aves_obd10** |  **v5.4.6 vertebrata_obd10** |
|:--- | --- | --- |
| Genes    |8,338 | 3,354 |
| Complete    | 96.8% | 96.0% |
| Single Copy | 96.3% | 95.1% |
| Duplicated | 0.5% | 0.9% |
| Fragmented |0.5% | 1.0% |
| Missing |  2.7% | 3.0% |

The authors acknowledge the traditional custodians of the land upon which the orange-bellied parrot resides, as well as the custodians of the historic range of the species and pay our respects to their elders past and present. We acknowledge the many years of effort and work of the orange-bellied parrot recovery team in the conservation of this species. We thank Priam Psittaculture Centre for sampling of the reference genome individual and transcriptomes. The authors wish to acknowledge the use of the services and facilities of the Australian Genome Research Facility; Ramaciotti Centre for Genomics at the University of New South Wales; and the Biomolecular Resource Facility at the John Curtin School of Medical Research, Australian National University. This work was supported by resources provided by the Pawsey Supercomputing Centre with funding from the Australian Government and the Government of Western Australia; the Sydney Informatics Hub, a Core Research Facility of the University of Sydney; Amazon Web Services; RONIN; and Australian Biocommons which is enabled by NCRIS via Bioplatforms Australia Threatened Species Initiative funding.

