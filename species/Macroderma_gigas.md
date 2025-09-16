# **Ghost bat** *(Macroderma gigas)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) |  [NCBI Accession: 	PRJNA1311142](https://www.ncbi.nlm.nih.gov/bioproject/1311142)

Luke Silver, Nicola Hanrahan, Kym Ottewell, Kyle Armstrong and Carolyn Hogg: The complete genome sequences of the ghost bat, *(Macroderma gigas)*

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2.fgenesh_cds.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2.fgenesh_mrna.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2.fgenesh_protein.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2.fgenesh.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2.global.20250303.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/mMacGig1.2_20250303_update.fasta.gz .
aws s3 cp --no-sign-request s3://threatenedspecies/Macroderma_gigas/README.txt .
aws s3 sync --no-sign-request s3://threatenedspecies/Macroderma_gigas/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | PacBio HiFi + YaHS |
|Assembler| hifiasm v0.19. + YaHS v1.2a.2 |
| Genome size | 2.00 GB |
| # Contigs | 460 |
| Longest Contig | 95.87Mb |
| # Scaffolds | 313 |
| Longest Scaffold| 192.28 Mb |
| Contig N50 | 37.66 Mb |
| Scaffold N50 | 100.01Mb |

<br>

| **BUSCO** | **v5.5.0 mammalia odb10** |
|:--- | --- |
| Complete    | 96.4% |
| Single Copy |  95.1% |
| Duplicated | 1.3% |
| Fragmented | 0.6% |
| Missing | 3.0%  |

This genome data was supported by funding from the Australian Research Council Centre of Excellence for Innovations in Peptide and Protein Science (CE200100012); the NCRIS supported Bioplatforms Australia Threatened Species Initiative.
Computational resources were provided by the Australian FGENESH++ Service provided by the Australian BioCommons and the Pawsey Supercomputing Research Centre with funding from the Australian Government and the Government of Western Australia; Galaxy Australia, a service provided by the Australian Biocommons and its partners; and the University of Sydney’s High Performance Computing facility Artemis provided by the Sydney Informatics Hub.
We wish to acknowledge the use of the services and facilities of the Ramaciotti Centre for Genomics, UNSW, of the Biomolecular Resource Facility, ANU, and of the Australian Genome Research Facility.
