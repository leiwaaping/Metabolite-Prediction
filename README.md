# Metabolite-Prediction
[Gene expression is a poor predictor of the metabolite abundance in cancer cells](https://faseb.onlinelibrary.wiley.com/doi/10.1096/fj.202101921RR)


### Abstract  
Metabolic reprogramming is a hallmark of cancer characterized by global changes in metabolite levels. However, compared with the study of gene expression, profiling of metabolites in cancer samples remains relatively understudied. We obtained metabolomic profiling and gene expression data from 454 human solid cancer cell lines across 24 cancer types from the Cancer Cell Line Encyclopedia (CCLE) database, to evaluate the feasibility of inferring metabolite levels from gene expression data. For each metabolite, we trained multivariable LASSO regression models to identify gene sets that are most predictive of the level of each metabolite profiled. Even when accounting for cell culture conditions or cell lineage in the model, few metabolites could be accurately predicted. In some cases, the inclusion of the upstream and downstream metabolites improved prediction accuracy, suggesting that gene expression is a poor predictor of steady-state metabolite levels. Our analysis uncovered a single robust relationship between the expression of nicotinamide N-methyltransferase (NNMT) and 1-methylnicotinamide (MNA), however, this relationship could only be validated in cancer samples with high purity, as NNMT is not expressed in immune cells. Together, we have trained models that use gene expression profiles to predict the level of individual metabolites. Our analysis suggests that inferring metabolite levels based on the expression of genes is generally challenging in cancer.  



### Data & Code accessible
Metabolic and transcript profile in CCLE: https://depmap.org/portal/download/  
processed file: dat/ (RData in link)
R code: Can_metabolite_predicted_by_genes.html 








