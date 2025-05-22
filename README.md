# Breast milk exposure and preterm infant attachment

This repository contains the code used to reproduce the analyses from the study:

"Preterm infant attachment is independent of breast milk intake during neonatal care" Jiménez-Sánchez, L., Vaher, K., Ginnell, L., Corrigan, A., McKinnon, K., Sullivan, G., ... & Fletcher-Watson, S. (2024). Wellcome Open Research, 9, 629. Accessible at: https://wellcomeopenresearch.org/articles/9-629

Repository author: Lorena Jiménez Sánchez (lorena.jimenezs@ed.ac.uk).

This repository has been deposited on OSF (17/10/2024), DOI: 10.17605/OSF.IO/ECVDY


# Directory structure

The project assumes the following file directory system:
- 	.Rproj.file
- 	raw_data
- 	results
	- 	demographics
	- 	comparisons
	- 	figures
	- 	covariates
- 	scripts

# Scripts for data analysis

The repository consists of the following folder:

- 	scripts/ containing Rmarkdown/script files as following:
	- 	BM_Attachment_dem.Rmd: creating demographic or clinical variables' descriptive tables, comparisons of demographic or clinical characeristics between preterm infants in the low and high breast milk group.
	- 	BM_Attachment_comp.Rmd: comparisons of attachment behaviours and classification between preterm infants in the low and high breast milk group, and term comparators.
	- 	BM_Attachment_cov.Rmd: investigation of potential confounders in preterm infants only.
	- 	BM_Attachment_sens.Rmd: sensitivity analysis - comparisons of attachment behaviours and classification between preterm infants in the low and high breast milk group controlling for confounders.
