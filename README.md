[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9155981&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-group-assigment-group_2/main)

# 27410 - Group assignment - Group 2 - Production of Vitamin E in *Escherichia coli*

## Project summary (<300 words)
On an international scale, an increase in demand for vitamin E is seen, mainly due to the increased market of dietary supplements for the health focused individuals and increasingly elderly generations. As vitamin E is mainly extracted and purified from seed oils, this project has been investigating the possibility of shifting to a fermentation based production. The proposed solution was found to be engineering of heterologous production of vitamin E in *E. coli* K-12 MG1655 based on model iML1515, with glucose as the main carbon source. A theoretical yield of 13% was found before exploring the optimal growth parameters. These investigations found that under ordinary, aerobic conditions, most glucose was used to increase biomass and not in producing vitamin E. This was attempted to control, by restricting biomass production to half of the maximal growth rate. Other strategies to further increase the production rate, such as the use of gene knockOpt and OptGene algorithms were attempted, yet unsuccessful. Since down regulating the biomass production proved to increase the production of the individual cell, the reduced number of cells, also reduced the overall yield of vitamin E. Knowing this, a different approach was chosen, by adding the amino acid tyrosine, that is used both as a proteinogenic amino acid and as a precursor in the vitamin E synthesis. Addition of tyrosine did increase the vitamin E production by 30%, since the abundance of the amino acid was shutting down the cells own tyrosine-synthesis.  A flux variability analysis was performed in effort to overexpress the TYRTA reaction, but with no significant results. An dFBA was attempted, but due to the large distance from the main metabolism, and lack of available models, the effort bore no results.

## Project overview
- Our project is organized with six notebooks  in the main folder.
- The report lives in the Report.ipynb notebook and contains references to the notebooks 1-6 in the main folder.
- Picture files used in the report are stored in the Pics folder.

