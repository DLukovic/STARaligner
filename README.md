# STARaligner
## Installation
Download the latetst release [from](https://github.com/alexdobin/STAR/releases) and install it.

    # Get latest STAR source from releases
    wget https://github.com/alexdobin/STAR/archive/2.7.8a.tar.gz
    tar -xzf 2.7.8a.tar.gz
    cd STAR-2.7.8a

    # Alternatively, get STAR source using git
    git clone https://github.com/alexdobin/STAR.git
    
## Step 1: Prepare the genome index

Download the "Genome sequence" and corresponding (same source) "annotation"
    
    mkdir genome
    cd Path/to/genome
    # Genome sequence
    wget ftp://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_29/GRCh38.primary_assembly.genome.fa.gz
    # Annotation
    wget ftp://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_29/gencode.v29.annotation.gtf.gz


Genome sequence from NCBI [here](https://www.ncbi.nlm.nih.gov/assembly/GCF_000003025.6/):

GCF_000003025.6_Sscrofa11.1_genomic.fna
Name of the chromosomes in genome sequence and annotation: **"chromosome 1"**

Genome sequence from Ensemble/iGenomes [here](https://www.ensembl.org/Sus_scrofa/Info/Index) or [here](https://support.illumina.com/sequencing/sequencing_software/igenome.html):
Name of the chromosomes in genome sequence and annotation: **"1,2,3.."**


## Step 2: 
