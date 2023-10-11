# Beta-cell-dysfunction in Type II Diabetes

The gene expression data of Beta-cell is obtained from NCBI database. The flod change (FC) in the expression level of diffrent genes are calculated using DESeq2 library. The FC data is mapped with KEGG pathway database to analysis the affected biochemical pathways (Using R script).

Gene expession data (read raw count) is normalize using TPM normalization (Python script). The normalized data is integrated into the HumanGEM model using INIT module in CobratoolBox (.Mat script). The gene expression data integrated model is undergoes diffrent alalysis like Flux balance analysis, Flux sampling, Diffrential flux analysis (.Py script).
