# ag advisory workflows

General rules to ensure reproducibility and efficiency

1) each project ("use-case") is 100% self-contained (except for private input data)
2) all the code for a project lives in a single git repo exclusive to the project 
	(grouped into an organization)
3) code shared between projects is accessed through one or more R packages
4) all the project specific data is in a folder exclusive to the project (raw / intermediate / final)
5) general use data such as GADM are accessed via R packages (not CGlabs specific)

