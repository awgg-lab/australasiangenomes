## A targeted approach to investigating immune genes of an iconic Australian marsupial 
(link will become active upon publication)
### Molecular Ecology Resources; accepted April 2022
Luke W. Silver, Yuanyuan Cheng, Bonnie L. Quigley, Amy Robbins, Peter Timms, Carolyn J. Hogg, Katherine Belov

Disease is a contributing factor to the decline of wildlife populations across the globe. Koalas, iconic yet declining Australian marsupials, are predominantly impacted by two pathogens, Chlamydia and koala retrovirus. Chlamydia is an obligate intracellular bacterium and one of the most widespread sexually transmitted infections in humans worldwide. In koalas, Chlamydia infections can present as asymptomatic or can cause a range of ocular and urogenital disease signs, such as conjunctivitis, cystitis and infertility. In this study, we looked at differences in response to Chlamydia in two northern populations of koalas using a targeted gene sequencing of 1,209 immune genes in addition to genome-wide reduced representation data. We identified two MHC Class I genes associated with Chlamydia disease progression as well as 25 single nucleotide polymorphisms across 17 genes that were associated with resolution of Chlamydia infection. These genes are involved in the innate immune response (TLR5) and defence (TLR5, IFNγ, SERPINE1, STAT2 and STX4). This study deepens our understanding of the role that genetics plays in disease progression in koalas and leads into future work that will use whole genome resequencing of a larger sample set to investigate in greater detail regions identified in this study. Elucidation of the role of host genetics in disease progression and resolution in koalas will directly contribute to better design of Chlamydia vaccines and management of koala populations which have recently been listed as “endangered”.

[Open Dataset - raw and aligned sequence data](https://koalagenomes.s3.ap-southeast-2.amazonaws.com/index.html#Investigating_immune_genes_of_the_iconic_koala/)

Download data through hyperlink above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  
```
aws s3 sync s3://koalagenomes/Investigating_immune_genes_of_the_iconic_koala/.
aws s3 sync s3://koalagenomes/Investigating_immune_genes_of_the_iconic_koala/DArTSeq/ .
aws s3 sync s3://koalagenomes/Investigating_immune_genes_of_the_iconic_koala/Target_Enrichment/ .


```

<br>

This data was produced as part of the Koala Genome Survey with funding from the NSW Government and the Australian Government’s Bushfire Recovery for Wildlife and their Habitats program (GA-2000526), further support was provided by the University of Sydney, Amazon Web Services Open Data Sets, Ramaciotti Centre for Genomics and Illumina.
