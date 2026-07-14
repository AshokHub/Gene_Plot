# Karyotype Gene Plot

This example demonstrates how to locate specific genes within a genome and visualize them in a plot. Using the [biomaRt](https://bioconductor.org/packages/biomaRt) Bioconductor package, we will automatically retrieve these gene coordinates from the Ensembl BioMart database. The resulting data frame will then be converted into a GRanges object using regioneR's `toGRanges` function. Because our target genome uses UCSC conventions, we will use `seqlevelsStyle` to adjust the chromosome naming format from Ensembl to UCSC. All examples are based on the GRCh38 assembly (_Homo sapiens_ (human) genome assembly (hg38) - Human Build 38 Organism), which aligns with the current version of BioMart.

The sample image output generated for genes SPTLC3, A2MP1, MT1M, GJB1, ITIH3, GSTM1, HPD, RPL10L, GMFG, SERPINC1, CMIP, BASP1, AP1G1, PI4KB, PHF3, GOLGB1, DENND4B, ZSWIM8, MARK2, ANKRD17 is below,

[![N|Solid](https://raw.githubusercontent.com/AshokHub/Gene_Plot/main/GenePlot.jpg)](https://github.com/AshokHub/Gene_Plot)

## Demo

The interactive demo to try using Google Colab is here: [Demo](https://github.com/AshokHub/Gene_Plot/blob/main/genePlot.ipynb).

## License

MIT

**Free Program, Hell Yeah!**

   [AshokHub]: <https://github.com/AshokHub>
