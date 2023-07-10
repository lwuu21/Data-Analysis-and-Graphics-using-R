# Data-Analysis-and-Graphics-using-R
Practiced plotting graphs for various datasets. 

Then interacted with a subset of the golub data, a set of data from a paper from Golub et al. Science 1999, 286(5439):531-537. This paper describes the first use of microarray (a lab tool) gene expression data to classify cancer cell subtypes that are difficult to distinguish morphologically, using acute leukemia (and its 2 common subtypes, ALL and AML) as a proof of principle.

I interacted with a subset of the original Golub et al. training data set, which contains normalized gene expression values for 3051 genes from 27 ALL and 11 AML patients derived from microarray analysis. I focused on the gene cyclin D3, whose expression difference correlates strongly with ALL versus AML status. Using functions like grep() and factor() to isolate data for this particular gene, I plotted a stripchart and a histogram to compare cyclin D3's expression in ALL and AML patients.
