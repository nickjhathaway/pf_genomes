# pf\_genomes
Version 1.0.0 - 2025-02

Repository of 13 Plasmodium falciparum reference genomes and annotation files. Genomes include Pf3D7 reference genome version 2020-09-01. Also included are the genomes from Otto et al 2018  


*Otto , T. D., Böhme, U., Sanders, M., Reid, A., Bruske, E. I., Duffy, C. W., Bull, P. C., Pearson, R. D., Abdi, A., Dimonte, S., Stewart, L. B., Campino, S., Kekre, M., Hamilton, W. L., Claessens, A., Volkman, S. K., Ndiaye, D., Amambua-Ngwa, A., Diakite, M., … Berriman, M. (2018). Long read assemblies of geographically dispersed Plasmodium falciparum isolates reveal highly structured subtelomeres. Wellcome Open Research, 3, 52.*


## Directory structure

*  genomes/  
	*	 Contains the fasta files of the genomes 
*	info/gff/
	*	 Contains the annotation files of the genomes in gff3 format 
*	info/drug_resistant_aaPositions.tsv
	*  A file with a list of currently (2025-02) known associated drug resistant loci 
*  info/drug_resistant_aaPositions.bed  
	*  The Pf3D7 genomic locations of the drug resistant loci 


Files are in gz format for size considerations but most programs will want the files in uncompressed format, once git is downloaded you can run the utility script in bin/unzip_data.sh to unzip all the gz files 

```
git clone https://github.com/nickjhathaway/pf_genomes.git
cd pf_genomes
bin/unzip_data.sh
```

   