Repeated model based differentially expressed genes (gene signature) discovery

This is a grid search method to find the optimal balances between fold change (signal strength) and p value (mostly signal consistency). The grid search is guided by cross-validated model performance. After an optimal model is discovered, the genes are removed from the data and the process starts again.

The numbers after "@@@@@@@" are training AUC performance and validation AUC performance. The validation AUC performance is a mesaure of model performance.

"Internal ID	GeneID	Mean1	Mean0	 P_R	 MDadj"

Mean1 is the mean value of cancer samples; Mean0 is the mean value of normal samples.

P_R is a consistency measure between 0-1, the smaller the better.

MDadj is a fold change measure.

Genes in each model does not have to be used together. Top genes can be picked from each model.
