# Exercise: Exploring the HLA class I histocompatibility antigen, alpha chain E (HLA-E) Gene with the UCSC Genome Browser
Today, we will be using the [UCSC Genome Browser][2] to explore the HLA class I histocompatibility antigen, alpha chain E (HLA-E) gene.
## Sections
1. Accessing the UCSC Genome Browser
2. Searching for the HLA-E Gene
3. Genome Browser Overview
4. Exploring HLA-E Annotations
5. Phenotype and Disease Association Tracks
6. Gene Expression Tracks


This tutorial follows the format of [Fishing for Genes in the UCSC Genome Browser][1].
For a more thorough tutorial of the UCSC Genome Browser, please visit this tutorial.

## Accessing the UCSC Genome Browser
To access the UCSC Genome Browser, go to [UCSC Genome Browser][2].
On the resulting page, you will see many tools in the blue ribbon menu, as well as a list of tools labeled 'Our tools' with a yellow background. The tools we will be using today are highlighted in the Figure ![UCSC Home Page][ucscHomepage]: These tools include:
- Genome Browser link on the top blue
menu bar links to the Gateway page
for the Genome Browser. The Gateway page is explored in greater
depth in the next section.
- Gene Sorter is a tool that displays a sorted
table of genes that are related by some metric
selected by the user. Such metrics include similar gene expression
and gene distance. The Gene Sorter is explored in the second part of this lab.
To read more about the Gene Sorter, see [Gene Sorter Abstract][3].
- Downloads allows users to bulk download data from multiple species from the UCSC
Genome Browser.

## 1. Searching for the HLA-E Gene
For this exercise, we will be exploring the UCSC Genome Browser with a focus on
the HLA class I histocompatibility antigen, alpha chain E (HLA-E) gene. The HLA-E gene encodes for the MHC Class I antigen E. HLA-E displays a subset of peptides on a cell surface to be read by natural killer cells. HLA-E has limited polymorphism, as we will explore in these exercises. To read more about HLA-E, see [HLA-E Gene][4].

### Exercises
1A. Given the link above for HLA-E, give a summary of the gene's function.

### Instructions

1. To get started exploring HLA-E, click on the **Genome Browser** tab on the home page. Clicking on this link takes you to the **Gateway page** that displays
the genome and multiple assemblies. Make sure the human assembly is The Gateway page is shown in the Figure: ![UCSC Gateway][ucscGateway] On this Gateway page, you can zoom in and out of
the genome and search for gene symbols and other search terms in the **search term box**, highlighted in red.

2.  Enter the gene symbol **HLA-E** into the **search term box**.
Clicking on the submit button directs you to a page of search results.
Results are presented as links to genome positions where there is data for the HLA-E Genes or HLA-E related terms. ![Search HLA-E][ucscHLAESearch]
3. Next, click on the link for HLA-E under **RefSeq Genes** where the chromosome is 'chr6', outlined in the Figure above. This will take you to the locus of HLA-E on the genome in the UCSC genome browser.

## 2. Genome Browser Overview
The Genome Browser displays certain annotation
tracks by default on the browser. The default image for the browser is shown below.
![Browser Home][ucscBrowserHBBHome] Highlighted components include:
- Search bar. Here, you can search positions, gene symbols and other search terms.
- Navigation. These tools allow you to zoom in and out and scroll to new parts of the
genome.
- Annotation Options. UCSC Genome Browser provides the ability to toggle annotation options to learn more about a specific region.


Now, let's look at the track for HLA-E.

Gene structure is shown on the HLA-E gene track with filled blue blocks representing
exons. Thick blocks are in the coding sequences (CDS) and thin
blocks represent untranslated regions (UTRs).
The lines connecting the blocks are introns.
The direction of arrowheads show the strand on which the element resides.
Right-facing arrows show that it is on the
forward strand while left-facing arrows show that
it is on the reverse strand. To toggle the direction of the strand, click
on the **reverse** button under all of the tracks.

### Exercises
2A.  What is the start and end location of HLA-E?

2B.  Hover over the HLA-E exons and introns. How many exons does the HLA-E gene have? Introns?


## 3. Exploring HLA-E Annotations
Each track has an associated description page
which can be reached by clicking on the name of the track. To access detailed gene annotations, click on the label **HLA-E** next to the RefSeq Gene track in the browser. This will
take you to a new page displaying more in depth information about HLA-E.


### Exercises
3A.  Which strand does this gene reside on?

3B. Navigate to the **Sequence and Links to Tools and Databases** section. What are the lengths of the predicted protein? The mRNA sequence? The genomic sequence? What is the correlation between these difference sequences?

3C. Nativate to the **RNA-Seq Expression Data from GTEx** section. In what tissue is HLA-E most highly expressed?


## 4. Phenotype and Disease Association Tracks
Navigate back to the genome browser to view HLA-E.

If the user scrolls down to the annotation sections, there is a **Phenotype and Literature** section under the browser view. Here, we can select options to view diseases associated with
a particular gene. Today, we will use **OMIM Pheno Loci View
track** to visualize diseases associated with HLA-E.
![Phenotype Annotation][pheno_clickOMIM]

### Instructions
1. Make sure you navigate back to the genome browser.
2. Scroll down to  **Phenotype and Literature** and toggle **OMIM Pheno Loci** to **full**. Make sure to click refresh.
3. Scroll back to the the browser view at the top of the page. Here, you will see multiple
colored bars that demonstrates the presence of diseases associated potentially associated with HLA-E.
![OMIM Visualization][pheno_redDisease]

### Exercises
4A. Scroll below the browser and click on the **OMIM Pheno Loci** title in **Phenotype and Literature**. Where does the
information from GAD View come from?

4B. In the browser, hover over some of the colored bars that signal associated diseases with the HLA-E gene. List
one of these associated diseases and describe them.


## 5. Gene Expression Tracks
Users can also search Gene Expression Tracks across multiple databases. These tracks
display gene expression across cell tissues from multiple samples. We will visualize gene expression from the GTEx Track.

### Instructions
1. Scroll down beneath the genome browser and select **full** view for GTEx Gene in the Expression section. Click Refresh.

2. In the refreshed browser, you will see a new bar chart showing the expression of HLA-E in different cell types. Click on that bar chart.
![Gene Expression GTEx][genex_gtex]

### Exercises
5A. In the GTEx bar chart, the y axis measures expression in RPKM. What does this stand for?

5B. What tissue has the highest median expression of HLA-E? The lowest?

<References>

[1]: https://genome.ucsc.edu/training/ucscGeneFishing.pdf "Fishing for Genes in the UCSC Genome Browser"
[2]: http://genome.ucsc.edu/ "UCSC Genome Browser"
[3]: http://genome.cshlp.org/content/15/5/737.abstract "Gene Sorter"
[4]: https://www.ncbi.nlm.nih.gov/gene/3133 "HLA-E Gene"

<Images>

[ucscHomepage]: ../../images/lab2/ucscHomepage.png "UCSC Homepage"

[ucscGateway]: ../../images/lab2/ucscGateway.png "UCSC Gateway"

[ucscHLAESearch]: ../../images/lab2/ucscHLAESearch.png "HLAE Search"

[ucscBrowserHBBHome]: ../../images/lab2/ucscBrowserHBBHome.png "HBB Browser Home"


<Phenotype section images>

[pheno_clickOMIM]: ../../images/lab2/pheno_clickOMIM.png "GAD Annotation"

[pheno_redDisease]: ../../images/lab2/pheno_redDisease.png "GAD Visualization"


<Gene Expression section images>

[genex_barChart]: ../../images/lab2/genex_barChart.png "Gene Expression Track"

[genex_gtex]: ../../images/lab2/genex_gtex.png "Gene Expression GTEx"
