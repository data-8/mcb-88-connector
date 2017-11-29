# Lab 2: Genome Analysis

In this lab, we will use a myriad of public interfaces that allow us to learn and explore specific genes.

### Terms to know before Starting
Some important keywords that will help you understand this lab more clearly are listed below.

1. Define each of these terms:


* Single Nucleotide Polymorphism (SNP)
* Coding Sequence
* Transcript
* RNA-sequencing (RNA-seq)

## Part 1: Using the UCSC Genome Browser to explore the HLA class I histocompatibility antigen, alpha chain E (HLA-E) Gene
Follow instructions from [UCSC Genome Browser Exercise: HLA class I histocompatibility antigen, alpha chain E (HLA-E) Gene][3].
Answer the questions throughout the tutorial.

## Part 2: Exploring HLA-E
For this part of lab, we will be using [UCSC Gene Sorter][2] to compare genes based on certain traits, specifically by distance and expression.
Genes of interest for this portion of the lab include HLA-A, HLA-C and HLA-E.

### Search for HLA-E by distance:
1. Navigate to [UCSC Gene Sorter][2].
2. Search for HLA-E in the search box, sorting by **GTEx Expression** in the **Sort By** dropdown menu. Here you will see a list of gene names and their position, description and BLASTP E-Value. ![Gene Sorter][gene_sorter]

#### Exercises
6A. What is the BLASTP E-value represent?

6B. What are the 2 most similarly expressed genes to HLA-E?

6C.  Using the gene descriptions, are there any similarities between HLA-E and these closest genes? What are they?

6D.  In this view, is there any way to gain information of how this gene is expressed? What
  can you learn about HLA-E expression from this view?

Now, search for HLA-E in the search box, sorting by **Protein Homology** in the **Sort By** dropdown menu.

6E. What does homology mean?

6F. What genes have similar homology to HLA-E? Is this list of genes surprising? Why or why not?

### Search for HLA-E by expression:
1. Search for HLA-E, sorting by gene expression (GTEx). List the 2 most similar expressed genes.
2. Search for HLA-E, sorting by gene expression (GNF Atlas 2). Are there any differences in
expression from searching in GTEx? If so, why would these be different?






[1]: https://genome.ucsc.edu/training/ucscGeneFishing.pdf "Fishing for Genes in the UCSC Genome Browser"
[2]: https://genome.ucsc.edu/cgi-bin/hgNear "UCSC Gene Sorter"
[3]: https://github.com/data-8/mcb-88-connector/blob/master/exercises/lab2/UCSCBrowserTutorial.md "UCSC Browser Exercise: HLA class I histocompatibility antigen, alpha chain E (HLA-E) Gene"

<Images>

[gene_sorter]: ../../images/lab2/geneSorterHBB.png "Gene Sorter"
