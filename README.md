# Kai_Li_w_TS_Kalbfleisch_AG2PI_SeedGrant
Software to support "A genetic data portal to enable discovery of deleterious genetic variants in farmed animals"
 
Download and install applications and server software from 

Install software that will enable creation of bcalm index, and ultimately a kmer index

https://github.com/kamimrcht/REINDEER?tab=readme-ov-file

Install sofwware for server socket that can be queried remotely.

https://github.com/Bio2M/rdeer-service
[RunReindeer.docx](https://github.com/kalbfleiUKY/Kalbfleisch_AG2PI_SeedGrant/files/14606963/RunReindeer.docx)


As a proof of principle, RNA-Seq data for 7 tissues from 4 animals was indexed.  K-mers with three selected randomly from each transcript fasta record were queried against the 28 indexed datasets, and a principal component analysis can be run directly on the kmer counts generated using the kmers derived from the transcriptome.  These counts were then used to generate a PCA plot demonstrating that the tissues clustered by kmer count derived expression values.


 



This work was supported by Agricultural Genome to Phenome Initiative (AG2PI):USDA-NIFA 2022-70412-38454 via a subaward from the University of Arizona (Dr. Fiona McCarthy PI)
