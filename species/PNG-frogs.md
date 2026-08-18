# **PNG frog transcriptomes** 

[Transcriptome Data ](https://threatenedspecies.s3.ap-southeast-2.amazonaws.com/index.html#Ornithorhynchus_anatinus/) | 
Download data through hyperlinks above or using the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html) | [NCBI Accession: 	PRJNA1510881](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1510881)
  
```
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/AUSTRO_GLOBAL.trinity.Trinity.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/AUSTRO_GLOBAL.trinity.Trinity.fasta.TD2.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/AUSTRO_GLOBAL.trinity.Trinity.fasta.TD2.pep .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/COPIULA_GLOBAL.trinity.Trinity.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/COPIULA_GLOBAL.trinity.Trinity.fasta.TD2.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/COPIULA_GLOBAL.trinity.Trinity.fasta.TD2.pep .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/OREOPHYRNE_GLOBAL.trinity.Trinity.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/OREOPHYRNE_GLOBAL.trinity.Trinity.fasta.TD2.gff3 .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/OREOPHYRNE_GLOBAL.trinity.Trinity.fasta.TD2.pep .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/pred_amps_austro_08.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/pred_amps_cop_08.fasta .
aws s3 cp --no-sign-request s3://threatenedspecies/png_frogs/pred_amps_oreo_08.fasta .
```


De novo generated transcriptomes and amp identification from three PNG frog species, raw RAN seq data available at PRJNA1510881

Discrepancies between file and species names are due to changes in species names during the study:
AUSTRO = Copiula guttata
COPIULA = Copiula mosbyae
OREOPHYRNE = Oreophyrne pseudunicolor
