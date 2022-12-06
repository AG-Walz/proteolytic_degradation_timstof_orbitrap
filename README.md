# Proteolytic degradation: timsTOF vs Orbitrap

This repository implements the analysis of putative proteolytic peptides of Hoenisch-Gravel et al. (DOI).
The full description of the method has been published by [Fritsche et al.](https://doi.org/10.1016/j.mcpro.2021.100110) and was applied in this notebook.

### Running the notebook
The input data needs to have 4 columns: `Sample`, `sequence`, `Uniprot`, `best score_netmhcpan-4.1`.
The best netmhcpan score is equivalent to the best netmhcpan rank of the peptide.
HLA binding predictions were performed using the [nf-core/epitopeprediction pipeline](https://nf-co.re/epitopeprediction).
Lastly, a reference proteome in fasta format is required.
