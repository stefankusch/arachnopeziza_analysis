## Genome assembly and analysis of *Arachnopeziza aurata* and *Arachnopeziza aurelia*

Saprohytic fungi of the family *Arachnopezizaceae* are the closest known extant relatives of the powdery mildew fungi and may hold great potential for studying genetic components of their obligate biotrophic lifestyle. Here, we established telomere-to-telomere genome assemblies for two representatives of this family, *Arachnopeziza aurata* and *Arachnopeziza aurelia*. Both species harbor 16 chromosomes at a genome size of 43.1 and 46.3 million base-pairs, respectively, which, in contrast to the transposon-enriched powdery mildew genomes, show a repeat content below 5% and signs of repeat-induced point mutation (RIP). 

In this repository, I summarize the scripts and tools I used to perform the assembly of the genome of *Arachnopeziza aurata* and *Arachnopeziza aurelia* and analyse genomic features in the assemblies. 
The publication can be found **here**.

#### Index

01. Genome assembly with `Canu`, `Flye` and `NextDenovo`, merging assemblies using `quickmerge` and telomere extension with `teloclip`.
02. Assembly quality assessments with `BUSCO`, `Quast`, and `CRAQ`.
03. Genome analysis.
04. Gene annotation *ab initio* via `BRAKER`.
05. Functional gene annotations.

#### References

##### Genome assembly
- Canu v2.2 [Koren et al. 2017]()
- Flye v2.9.2 [Kolmogorov et al. 2019]()
- NextDenovo v2.5.2 [Hu et al. 2024]()
- quickmerkge v0.3 [Manual](https://github.com/mahulchak/quickmerge?tab=readme-ov-file)
- BWA v0.7.17.r1188 [Li & Durbin 2009]()
- pilon v1.24 [Walker et al. 2014]()
- teloclip v0.0.4 [Manual](https://github.com/Adamtaranto/teloclip)

##### Genome assembly quality assessment
- Quast v5.2.0 [Gurevich et al. 2013]()
- BUSCO [Simão et al. 2015]()
- compleasm [Huang & Li 2023]()
- CRAQ v1.0.9 [Li et al. 2023]()

##### Genome analysis
- NCBI Blast+ [Website](https://www.ncbi.nlm.nih.gov/books/NBK279690/)
- MUMmer v4.4.0 [Kurtz et al. 2004]()
- RepeatMasker v4.0.9 [Website](http://www.repeatmasker.org)
- TETrimmer [Qian et al. 2024]()
- RIPCAL v2.0 [Hane & Oliver 2008](www.r-project.org/)

##### Gene annotation
- BRAKER3 v3.0.8 [Bruna et al. 2023](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btv661)
- HISAT2 [Kim et al 2015](http://www.nature.com/articles/nmeth.3317)
- Trimmomatic v0.39 [(Bolger et al. 2014]()
- HMMer v3.4 [Potter et al. 2018]()
- InterProScan v5.73-104.0 [Jones et al. 2014]()
- TMHMM v2.0c [Krogh et al. 2001]()
- SignalP5.0 [Almagro Armenteros et al. 2019]()
- OrthoFinder v2.5.5 [Emms & Kelly 2019]()

##### Other command-line tools
- Samtools [Publication](https://academic.oup.com/bioinformatics/article/25/16/2078/204688) | [Manual](http://www.htslib.org/doc/)
- BEDtools v2.31.0 [Publication](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btq033) | [Manual](https://bedtools.readthedocs.io/en/latest/)
- gffread [Manual](http://ccb.jhu.edu/software/stringtie/gff.shtml)

##### Plotting and statistical analysis
- R v4.3.1 [R Core Team 2018]()
