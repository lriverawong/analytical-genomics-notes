# Analytical Genomic Notes

## Table of Contents
|       Section        |
| -----------------    |
|   [W10](#w10) |
|   [W11](#w11) |


## W10
### DNA Methylation and CpG Island
- CG island is a short stretch of DNA in which the frequency of the CG sequence is higher than other regions
    - also called the CpG island, where "p" simply indicates that "C" and "G" are connected by a phosphodiester bond
- CG sequences in inactive genes are usually methylated to supress their expression
- methylation plays crutial role in gene regulation
    - when located in a gene promoter, typically acts to repress gene transcription

        1. Methylation of CpG islands may prevent or enhance binding of regulatory transcription factors to promoter region

        ![alt text](assets/methyl-inhibition-01.png "Methylation Method 01")
        2. Inhibition using methyl-CpG-binding proteins, which bind methylated sequences

        ![alt text](assets/methyl-inhibition-02.png "Methylation Method 02")
- methylated cytosine may be converted to thymine by accidental deamination
    - unlike C->U mutation which is efficiently repaired, C->T can only be fixed by inefficient mismatch repair
- methylation and acetylation can either activate or repress specific histones

### microRNA
![alt text](assets/miRNA.svg "miRNA")
- what is microRNA
    - small non-coding RNA molecule (containing about 22 nucleotides) found in plants, animals and some viruses
    - encode regulatory RNA molecules that are not translated (not including rRNA, tRNA, snRNA, etc)
    - 1000s identifed in various genomes
    - 1000 or more in human genom`e
    - regulate mRNA stability, translation, and participate in cell communication
- miRNA function (summary)
    - function in RNA silencing and post-transcriptional regulation of gene expression
- first 7 or 8 nucleotide pairs determine which target it binds to

#### miRNA Mechanism/Function
![alt text](assets/miRNA-mechanisms.png "miRNA Mechanisms")

- function pathways
    - miRNA binds 3’-UTR - mRNA destabilization
    - miRNA binds coding region – translational repression
    - miRNA binds 5’-UTR – translational repression/activation
- translational regulation
    - not always degraded, sometimes stores the target and released later for a delayed translation
- dysregulation of miRNA genes contributes to cancer in some cases - possibly all
    - due to loss of tumour-supressor miRNAs
    ![alt text](assets/miRNA-dysregulation.png "miRNA Dysregulation")

#### miRNA Execretion
- secreted in exosome - cell-cell communication
- secreted as free molecule +/- proteins - cell-cell communication
- miRNA released by cell death
- liquid biopsies
    - trying to detect miRNA from exosomes trying to use blood tests to determine state of tumours in blood
    - RNA-Seq (or PCR) for circulating miRNAs
    ![alt text](assets/circulating-miRNA.png "Circulating miRNA")

#### Finding miRNA Targets
- gene knockout (KO) + transcriptional profile & phenotype
- gene overexpression + transcriptional profile & phenotype
- validation
    - validate results for mRNA by measuring protein levels/turnover
- TargetScan
    - summarizes data and predicts targets
    - predicts biological targets of microRNAs (miRNAs) by searching for the presence of sites that match the seed region of each miRNA

## W11