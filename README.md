# Karyotype Gene Plot
This example shows how to determine the position of some genes in the genome 
and create a plot showing them. We'll use Ensembl's Biomart database to 
automatically retrieve their position using the [biomaRt](https://bioconductor.org/packages/biomaRt)
Bioconductor package. We'll automatically convert the returned data frame into 
a GRanges with regioneR's `toGRanges` and since our genome is from UCSC, we'll
need to change the chromosome name style from Ensembl to UCSC with
`seqlevelsStyle`. We'll use genome GRCh38, the one used in the current biomart
version.

[![N|Solid](https://raw.githubusercontent.com/AshokHub/Gene_Plot/main/GenePlot.jpg)](https://github.com/AshokHub/Gene_Plot)
