This practical guides you through:

Reading three input files and converting them to useful Python structures.
Building a PPI network with NetworkX.
Measuring connectivity of disease gene sets (Largest Connected Component, LCC).
Assessing significance with a Z-score (vs. random expectation) and two-tailed p-value.
Characterizing disease genes via centrality metrics and finding the most central genes/diseases.
Files

rare_disease_genes.tsv — columns: disease, gene (semicolon-; separated gene symbols per row)
ppi.tsv — columns: Gene Name Interactor A, Gene Name Interactor B (edge list)
drugs_drugbank_symbol.tsv — first col = drug name; remaining cols = targets
