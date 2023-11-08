# ag advisory workflows

The goal is to make it easier to develop and run workflows that are 

- reproducible (can run anywhere with a single line of code)
- use standards are simple and efficient (can be understood)
- support research to evaluate and contrast different choices

Guidelines 

- each project ("use-case") is 100% self-contained (except for private input data)
- all the code for a project lives in a single git repo exclusive to the project 
	(grouped into an organization)
- the only configuration for a needed is the local name of the projects directory
- code should be in a git repo. Data should be in separate folders (and normally not in a repo)
- code shared between projects is accessed through R packages
- all data cleaning is done in an R script 
- cleaned data should follow the Carob standard
- all the project specific data is in a folder exclusive to the project (raw / intermediate / final)
- other standard folders: output, img
- general use data are accessed via R packages (not CGlabs specific)
- no hard-coded paths for data or "source()"



