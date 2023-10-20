# ag advisory workflows

Guiding principles to ensure reproducibility and efficiency

1) each project ("use-case") is 100% self-contained (except for private input data). 
2) all the code for a project lives in a single git repo exclusive to the project 
	(grouped into an organization)
3) the only configuration for a needed is the local name of the projects directory
4) all data cleaning is done in an R script
5) code shared between projects is accessed through one or more R packages (was modules)
6) code and data should be in seperate folders
7) all the project specific data is in a folder exclusive to the project (raw / intermediate / final)
8) general use data such as GADM are accessed via R packages (not CGlabs specific)


