# Bioinformatic pipelines for mumps genome sequencing

#### Louise Moncla<sup>1</sup>, Allison Black<sup>1,2</sup>, Trevor Bedford<sup>1

<sup>1</sup>Department of Epidemiology, University of Washington, Seattle, WA, USA, <sup>2</sup>Vaccine and Infectious Disease Division, Fred Hutchinson Cancer Research Center, Seattle, WA, USA


## Overview of bioinformatic processing of mumps sequencing reads 
1. Adapter and quality trimming with [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic )
2. Mapping with [bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml)
3. Manual inspection of mapping and consensus genome calling with [Geneious](https://www.geneious.com/) 
4. Re-mapping fastq files called consensus with [bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml)


### Trimming
Trimming was performed with [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic ) to remove Illumina adapter sequencing and ends of reads with low quality scores. Reads were trimmed in 5 bp windows to a quality score of Q30, and trimmed reads with length < 100 bp were discarded. 

### Mapping 
We used a [genome](https://www.ncbi.nlm.nih.gov/nuccore/MF965301) from the mumps outbreak in Massachusetts as a reference sequence. We mapped our trimmed reads to that reference using [bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml). The mapping (bam) file was manually inspected in [Geneious](https://www.geneious.com/). 

### Consensus sequence calling
Consensus sequences were called in Geneious, with nucleotide sites with <100x coverage called as Ns. Consensus genomes were exported in fasta format. 

### Remapping
To avoid issues with mapping to improper reference sequences, we then remapped each sample's fastq files to its own consensus sequence. These bam files were again manually inspected in Geneious, and a final consensus sequence was called. Those consensus genomes for which we acquired at least 80% full-genome coverage are available [here](https://github.com/blab/mumps-seq/tree/master/data/consensus-genomes) as fasta files. 



