Computational prediction of isochores in genome sequences

The algorithm IsoFinder [1] is able to predict isochores at the sequence level. Most of the IsoFinder isochores show correlation with biological features such as gene density, SINE and LINE densities, recombination rate or SNP variability. The reliability of this algorithm in predicting isochore-like regions at the sequence level has been established through the analysis of large-scale genome patchiness by an independent method: the analysis of the deviations in the power-law behavior of long-range correlations [2,3].

Recently, the organization of isochores into high-level chromosome superstructures has been shown [4]. Every human chromosome seems composed of a few huge segments (~ 10 Mbp) of relatively homogeneous G+C content, which become the largest compositional organization of the genome.

On the website http://bioinfo2.ugr.es/isochores/, the isochores predicted by IsoFinder for the best-assembled mammalian genome sequences are listed ['isochores' link on the left menu]. When available, genome coverages of each isochore for genes, SINEs, LINEs and PhastCons are also provided. In addition, through the UCSC Track Hub facility, the resulting isochore genome maps are shown ['map' link].

Minor code updates:
1.	Output file in BED-like format
2.	Better identification of chromosome-contigs for recent genome assemblies
3.	Increased minimum segment size to improve the reliability of statistical tests

[1] Oliver JL, Carpena P, Hackenberg M, Bernaola-Galván P. 2004. IsoFinder: computational prediction of isochores in genome sequences. Nucleic Acids Research 32: W287-W292.
http://dx.doi.org/10.1093/nar/gkh399

[2] Oliver JL, Bernaola-Galván P, Hackenberg M, Carpena P. 2008. Phylogenetic distribution of large-scale genome patchiness. BMC Evolutionary Biology 8: 107.
http://dx.doi.org/10.1186/1471-2148-8-107

[3] Bernaola-Galván P, Oliver JL, Hackenberg M, Coronado AV, Ivanov P Ch, Carpena P. 2012. Segmentation of time series with long-range fractal correlations. The European Physical Journal B 85: 211
http://dx.doi.org/10.1140/epjb/e2012-20969-5

[4] Carpena P, Oliver JL, Hackenberg M, Coronado AV, Barturen G, Bernaola-Galván, P. 2011.
High-level organization of isochores into gigantic superstructures in the human genome. Physical Review E 83: 031908 (1-7)
http://dx.doi.org/10.1103/PhysRevE.83.031908


