# Viral Protein Families, Phylogenetics and Biodiversity
This is a code blocks of my thesis, BUT the code has not yet be automated for a complete graph analysis(to be).., because there is a mix of bash and python script included. So I would recommend dont look at the code until I will make it neat. 

So some theoretical staff:
We have taken the planet's viral proteome (version Sep 2020) of NCBI and examined the similarity in sequences using sequence alignment and networks.
We created families of viruses based on their sequence similarity using LAST.
Each protein has a taxonomic lineage. 
For each family of proteins only few taxonomic lineages were kept using a threshold. 
For each taxnomic level of the lineage we created graphs that showed the similarities between the families. 

Then we enriched our protein families with metagenomes(from IMG/M) that had a similar sequence similarity and we wanted to see if the taxonomic lineage of the enriched families was altered significantly(well.. it did on low level taxonomy ranks). Therefore we made new graphs of the enriched families , after we had identified our metagenomes using classification algorithm mmseqs2(with small sensitivity).

Function analysis(gene ontology) and habitat identification was also done by peeking into Pfam and GOLD database. 

