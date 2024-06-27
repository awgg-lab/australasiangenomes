# **Ninu (Greater Bilby)** *(Macrotis lagotis)* 

[Genome & Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html) | [NCBI Accession: 	PRJNA1049866](https://www.ncbi.nlm.nih.gov/bioproject/1049866)

[Publication:](https://www.nature.com/articles/s41559-024-02436-2)  Carolyn J. Hogg, Richard J. Edwards, Katherine A. Farquharson, Luke W. Silver, Parice Brandies, Emma Peel, Merly Escalona, Frederick R. Jaya, Rujiporn Thavornkanlapachai, Kimberley Batley, Tessa M. Bradford, J King Chang, Zhiliang Chen, Nandan Deshpande, Martin Dziminski, Kyle M. Ewart, Oliver W. Griffith, Laia Marin-Gual, Katherine L. Moon, Kenny J. Travouillon, Paul Waters Camilla M. Whittington, Marc R. Wilkins, Kristofer M. Helgen, Nathan Lo, Simon Y. W. Ho, Aurora Ruiz Herrera, Rachel Paltridge, Jennifer A. Marshall Graves, Marilyn Renfree, Beth Shapiro, Kym Ottewell, Kiwirrkurra Rangers, Katherine Belov. (2024) Extant and extinct bilby genomes combined with Indigenous knowledge improve conservation of a unique Australian marsupial. Nature Ecology & Evolution DOI: 10.1038/s41559-024-02436-2

Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/bilby.v1.9.fasta.gz .
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/bilby_fgenesh.gff3 .
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/bilby_fgenesh_proteins.fa .
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/Mala_11tissues_refGuided_annot.fasta .
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/bilby.v1.5.hypo.hirise.curation.fasta.gz .
aws s3 cp s3://threatenedspecies/Macrotis_lagotis/bilby.v1.5.hirise.ensrep200kb.gff .
aws s3 sync s3://threatenedspecies/Macrotis_lagotis/ .
```

<br>

| Assembly Statistics |  |
|:--- | --- |
| Assembly    | bilby.v1.5.hypo.hirise.curation | bilby.v1.9.fasta |
| Description |  HiRise HiC-scaffolded core assembly | Final Bilby v1.9 genome assembly |
| Genome size | 3.57 Gb | 3.66 Gb |
| #contigs | 5955 | 5028 |
| contig N50 | 1.23 Mb | 1.23 Mb|
| # scaffolds | 296 | 609 |
| Scaffold N50 | 343.85 Mb | 343.85 Mb |
| Largest Scaffold | 934 Mb | 934 Mb|

95.6% of the genome is assigned to 9 nuclear chromosomes and one mitogenome
<br>

| **BUSCO** | **v5.4.6 mammalia_obd10** |
|:--- | --- |
| Genes    | 9226 |
| Complete    | 93.5% |
| Single Copy |  88.6% |
| Duplicated | 4.9% |
| Fragmented | 1.1% 
| Missing | 5.4%  | 

We acknowledge the traditional custodians of the land upon which bilbies have been, and are still, found and pay respects to their elders past and present. 

We thank Perth Zoo and Taronga Zoo for the provision of the individuals (female and male respectively) for the reference genome and transcriptomes. Thanks also to A. Sayer for assistance in acquiring the genome sample from Perth Zoo.

The 10x Genomics sequencing was provided as part of the Oz Mammals Genomics (OMG), and bioinformatic support was provided as part of the Threatened Species Initiative (TSI), both supported by funding from the Australian Government National Collaborative Research Infrastructure Strategy (NCRIS) Bioplatforms Australia. The PacBio HiFi sequencing and HiC was supported by the University of Sydney through research grants to KB (DP180102465) and CJH (Toledo Zoo and Aquarium).

Image supplied by Emma Peel, AWGG.
