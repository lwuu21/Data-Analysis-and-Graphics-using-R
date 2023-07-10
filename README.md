# Data-Analysis-and-Graphics-using-R
Practiced plotting graphs for various datasets. 

Then interacted with a subset of the golub data, a set of data from a paper from Golub et al. Science 1999, 286(5439):531-537. This paper describes the first use of microarray (a lab tool) gene expression data to classify cancer cell subtypes that are difficult to distinguish morphologically, using acute leukemia (and its 2 common subtypes, ALL and AML) as a proof of principle.

I interacted with a subset of the original Golub et al. training data set, which contains normalized gene expression values for 3051 genes from 27 ALL and 11 AML patients derived from microarray analysis. 3 new objects will be loaded into my environment: golub, golub.gnames, and golub.cl. golub is a matrix containing normalized microarray gene expression data for 3051 genes from the 38 leukemia patients. golub.gnames is a matrix containing the same 3051 rows in an equivalent order to golub, providing gene names for each row. golub.col is a numeric vector containing 38 numbers in the same column order as golub, providing leukemia subtype identifiers for each patient: 0 codes for ALL and 1 codes for AML.
