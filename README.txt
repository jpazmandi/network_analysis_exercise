This practical guides you through:

1) Reading three input files and converting them to useful Python structures.
2) Building a PPI network with NetworkX.
3) Measuring connectivity of disease gene sets (Largest Connected Component, LCC).
4) Assessing significance with a Z-score (vs. random expectation) and two-tailed p-value.
5) Characterizing disease genes via centrality metrics and finding the most central genes/diseases.
6) Some (very) basic network visualisation with NetworkX


Files in data/

rare_disease_genes.tsv — columns: disease, gene (semicolon-; separated gene symbols per row)
ppi.tsv — columns: Gene Name Interactor A, Gene Name Interactor B (edge list)
drugs_drugbank_symbol.tsv — first col = drug name; remaining cols = targets
