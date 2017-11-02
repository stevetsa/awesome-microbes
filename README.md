# awesome-microbes
List of software packages (and the people developing these methods) for microbiome (16S), metagenomics (WGS, Shot-gun sequencing), and pathogen identification/detection/characterization.  [Contributions welcome...](https://github.com/stevetsa/awesome-microbes/blob/master/CONTRIBUTE.md)
<br /> 
Inspired by [awesome-single-cell](https://github.com/seandavi/awesome-single-cell/blob/master/README.md)
<br />


## Microbiome (16S)

[Explicet]( http://www.explicet.org) - [?] - a free to use, open source software package (GPLv3) available for Windows, Mac, and Linux that facilitates the exploration and visualization of taxonomy-based microbiome datasets (a.k.a. OTU tables).

[LotuS]( http://psbweb05.psb.ugent.be/lotus) - [?] - aims at scientists and bioinformatician that want a simple pipeline that is streamlined to a core functionality of creating OTU and taxa abundance tables, at very fast speeds (e.g. processing an 8GB 16S miSeq run takes ~ 30 min on a laptop). LotuS does not include numerical analysis of samples, instead we designed LotuS output to be easily integrateable into existing workflows in e.g. statistical programming languages like R, QIIME/mothur or Matlab.

[METAREP](https://github.com/jcvi/METAREP) - [?] - high-performance comparative metagenomics. It provides a suite of web based tools to help scientists to view, query, browse and compare metagenomic annotation data derived from ORFs called on metagenomics reads or assemblies.

[Microbiome Util]( http://microbiomeutil.sourceforge.net) - [perl] - NASTiEr - Sequence Alignment; WigeoN - Chimera detection; TreeChopper - OTU binning; AMOSScmp - Sequence assembly.

[mothur](https://www.mothur.org/) - [C++] - OTU-based analysis of 16S data.

[Otupipe](http://www.drive5.com/usearch/manual/otupipe.html) - [?] - a bash script for OTU clustering based on USEARCH. This page is retained for historical interest because a script based on otupipe was used to create the published QIIME results for the Human Microbiome Project (HMP).

[Qiime](http://qiime.org/) - [Python] - QIIME is designed to take users from raw sequencing data generated on the Illumina or other platforms through publication quality graphics and statistics. This includes demultiplexing and quality filtering, OTU picking, taxonomic assignment, and phylogenetic reconstruction, and diversity analyses and visualizations.

[Qiita (cheetah)]( http://qiita.microbio.me/) - [?] - microbiome storage and analysis resource that can run on everything from your laptop to a supercomputer. It is built on top of the widely used QIIME package, and enables the exploration of -omics data.

[UPARSE]( http://drive5.com/uparse/) - [?] - generates OTUs that are far superior to state-of-the-art methods including QIIME, mothur and AmpliconNoise on mock community tests. OTU representative sequences are more accurate predictions of biological sequences, and the number of OTUs is much close to the number of species.

[USEARCH](https://www.drive5.com/usearch/) - [?] - a high-throughput sequencing tool that offers read processing, clustering (ESTs, OTUs, +more), and diversity and taxonomy analysis algorithms in a single package. USEARCH's database search feature is 10-100 times faster than BLAST, and the documentation is thorough and user-friendly. The 32-bit version is free, including for commercial use. A paid 64-bit version is also available.


## Metagenomics (WGS, Shot-gun sequencing)

[bioBakery-MetaPhlAn](https://bitbucket.org/biobakery/biobakery/wiki/Home) - [python] - a virtual environment platform that provides meta'omic analysis tools.

[Mauve](http://darlinglab.org/mauve/mauve.html) - [?] - a system for constructing multiple genome alignments in the presence of large-scale evolutionary events such as rearrangement and inversion. Multiple genome alignments provide a basis for research into comparative genomics and the study of genome-wide evolutionary dynamics.

[curatedMetagenomicData](bioconductor.org/packages/curatedMetagenomicData) - [R] - a curated database of processed human microbiome data from metagenomics, from the Human Microbiome Project and numerous other published datasets.  Provides both taxonomic profiles and inferred metabolic function.  Distributed via Bioconductor's [ExperimentHub](https://bioconductor.org/packages/ExperimentHub/), command-line interface also available.

[MetaMeta](https://github.com/pirovc/metameta) - [python] - Integrates metagenome analysis tools to improve taxonomic profiling. [doi](https://doi.org/10.1101/138578)



## Microbe (pathogen, bacterial, viral) Identification/Detection/Characterization

[Pathoscope](https://sourceforge.net/p/pathoscope/wiki/Home/) - [python] - Species identification and strain attribution with unassembled sequencing data.

[MetaHIT](http://www.metahit.eu/index.php?id=232) - [?] - DNA microarrays and high-throughput DNA re-sequencing technology for structural and functional analysis of microbial populations.

## Visualization

[Krona](https://github.com/marbl/Krona/wiki) - [python] - Interactive metagenomic visualization in a Web browser. 

[MEGAN](http://ab.inf.uni-tuebingen.de/software/megan6/) - [?] - The most powerful interactive microbiome analysis tool
Analyse metagenome, metatranscriptome and amplicon sequences from multiple sources.

## Other Tools 

[AmpliconNois]( https://code.google.com/p/ampliconnoise) - [?] - a collection of programs for the removal of noise from 454 sequenced PCR amplicons. It involves two steps the removal of noise from the sequencing itself and the removal of PCR point errors. This project also includes the Perseus algorithm for chimera removal.

[BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) - [C?] - Basic Local Alignment Search Tool.

[gist, genepuddle, and gargle]( http://www.compsysbio.org/front/?id=73) - [?] - filter contaminants from RNA-seq sequences to make them suitable for alignment and analysis.

[MLSTEZ](https://sourceforge.net/projects/mlstez/) - [python] - MLSTEZ is designed for next generation sequencing technology (PacBio CCS or Roche 454 platform) based MSLT methods. 

## Web Portals
[CosmosID](http://www.cosmosid.com/) - Exploring the Universe of Microbes.

[One Codex](https://www.onecodex.com) - One Codex is a data platform for applied microbial genomics.

[Cancer Genomics Cloud](http://www.cancergenomicscloud.org/) - A cloud platform to analyze microbe data.  Currently available pipelines - BLAST-based microbe identification and characterization, mothur, Qimme, and MetaPhlAn with built-in visualization.  Contact @stevetsa for [more information](http://bit.ly/nciposter).  

[MG-RAST](http://metagenomics.anl.gov/) - Metagenomics Analysis Server.

[Nephele](https://nephele.niaid.nih.gov/#home) - Microbiome Analysis without Boundaries.

[PATRIC](https://www.patricbrc.org/) - Bacterial database and analysis platform.

[ViPR](https://www.viprbrc.org/brc/home.spg?decorator=vipr) - Viral pathogen database and analysis platform.

## Journal Articles, etc.
[BIOM Format](http://biom-format.org/) - is designed to be a general-use format for representing biological sample by observation contingency tables. BIOM is a recognized standard for the Earth Microbiome Project and is a Genomics Standards Consortium supported project.

[Experimental and analytical tools for studying the human microbiome](http://www.nature.com/nrg/journal/v13/n1/full/nrg3129.html) - Nature Reviews Genetics 13, 47-58 (January 2012) | doi:10.1038/nrg3129.






