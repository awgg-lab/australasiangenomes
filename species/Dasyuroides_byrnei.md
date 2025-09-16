# **Kowari** *(Dasyuroides byrnei)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) |  [NCBI Accession: 	PRJNA1301011](https://www.ncbi.nlm.nih.gov/bioproject/1301011)

Citation: Cleopatra Petrohilos, Emma Peel, Luke W. Silver, Patrick G. S. Grady, Rachel J. O’Neill, Carolyn J. Hogg, Katherine Belov: When Cells Rebel: a comparative genomics investigation into marsupial cancer susceptibility
bioRxiv 2025.08.12.669816; doi: https://doi.org/10.1101/2025.08.12.669816.

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/mDasByr.global.20251403.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/mDasByr1.2.fgenesh.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/mDasByr1.2.fgenesh_mrna.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/mDasByr1.2.fgenesh_protein.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/mDasByr.1.2_20251403.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/README.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Dasyuroides byrnei/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi + YaHS |
| Genome size | 3.21 GB |
| #contigs | 2402 |
| # Scaffolds | 851|
| Contig N50 | 4.0 Mb |
| Scaffold N50 | 620.0 Mb |

<br>

| **BUSCO** | **v5.8.0 mammalia odb10** |
|:--- | --- |
| Complete    | 95.6% |
| Single Copy |  94.5% |
| Duplicated | 1.2% |
| Fragmented | 1.0% |
| Missing | 3.4%  |

This genome data was supported by funding from the Australian Research Council Centre of Excellence for Innovations in Peptide and Protein Science (CE200100012); the NCRIS supported Bioplatforms Australia Threatened Species Initiative. The kowari samples were provided by the South Australian museum.
Computational resources were provided by the Australian FGENESH++ Service provided by the Australian BioCommons and the Pawsey Supercomputing Research Centre with funding from the Australian Government and the Government of Western Australia; Galaxy Australia, a service provided by the Australian Biocommons and its partners; and the University of Sydney’s High Performance Computing facility Artemis provided by the Sydney Informatics Hub.
We wish to acknowledge the use of the services and facilities of the Ramaciotti Centre for Genomics, UNSW, of the Biomolecular Resource Facility, ANU, and of the Australian Genome Research Facility.
