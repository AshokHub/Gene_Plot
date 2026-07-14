# Karyotype Gene Plot
This example shows how to determine the position of some genes in the genome 
and create a plot showing them. We'll use Ensembl's Biomart database to 
automatically retrieve their position using the [biomaRt](https://bioconductor.org/packages/biomaRt)
Bioconductor package. We'll automatically convert the returned data frame into 
a GRanges with regioneR's `toGRanges` and since our genome is from UCSC, we'll
need to change the chromosome name style from Ensembl to UCSC with
`seqlevelsStyle`. We'll use genome GRCh38, the one used in the current biomart
version.

The sample image output generated for genes SPTLC3, A2MP1, MT1M, GJB1, ITIH3, GSTM1, HPD, RPL10L, GMFG, SERPINC1, CMIP, BASP1, AP1G1, PI4KB, PHF3, GOLGB1, DENND4B, ZSWIM8, MARK2, ANKRD17 is below,

[![N|Solid](https://raw.githubusercontent.com/AshokHub/Gene_Plot/main/GenePlot.jpg)](https://github.com/AshokHub/Gene_Plot)

## Demo

The interactive demo to try using Google Colab is here: [Demo](https://github.com/AshokHub/Gene_Plot/blob/main/genePlot.ipynb).

## License

MIT

**Free Program, Hell Yeah!**

   [AshokHub]: <https://github.com/AshokHub>
