# EPIC_SNP_Manifest
*Annotating snps on EPIC arrays for GWAS identifier matching/sample fingerprinting.*

Uploaded a compiled EPIC SNP manifest for fingerprinting using all 59 SNPs if imputed genotypes are available.
Affy system is used to code corresponding methylation scores (ie if Methyl(beta) = 1, then Affy score is 0 (corresponding to ref allele) or 2 (corresponding to alternate allele) for a given snp, or vice-versa, depending on the M and U beads at each probe). 

Data is compiled from an in-house project where DNA methylation (EPIC) and Genotyping (affymatrix) data are available for a cohort of 1,500 individuals. 

This table was built upon a previous effort from [ttriche/infiniumSnps] (https://github.com/ttriche/infiniumSnps) and credit must be given to **Tim Triche**.

#To do list (not immediate future):
- Build a function to import genotype from platforms (ie Illumina & Affy)
- Build a function to extract and import imputed genotype data (bgen, plink, vcf)
- Build a function that streamlines fingerprinting process and report back accuracy and mismatches, perhaps with a user-settalbe threshold.
