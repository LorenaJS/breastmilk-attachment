# Breast milk exposure and preterm infant attachment

Code to reproduce the analyses presented in: "Preterm infant attachment is independent of breast milk intake during neonatal care".

Repository author: Lorena Jiménez Sánchez (lorena.jimenezs@ed.ac.uk).

# Directory structure

The project assumes the following file directory system:
- 	.Rproj.file
- 	raw_data
- 	results
	- 		demographics
	- 		comparisons
	- 		figures
	- 		covariates
- 	scripts

# Scripts for data analysis

The repository consists of the following folder:

- 	scripts/ containing Rmarkdown/script files as following:
	- 		BM_Attachment_dem.Rmd: creating demographic or clinical variables' descriptive tables, comparisons of demographic or clinical characeristics between preterm infants in the low and high breast milk group.
	- 		BM_Attachment_comp.Rmd: comparisons of attachment behaviours and classification between preterm infants in the low and high breast milk group, and term comparators.
	- 		BM_Attachment_cov.Rmd: investigation of potential confounders in preterm infants only.
	- 		BM_Attachment_sens.Rmd: sensitivity analysis - comparisons of attachment behaviours and classification between preterm infants in the low and high breast milk group controlling for confounders.
