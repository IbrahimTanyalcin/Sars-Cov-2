# Sars-Cov-2
MutaFrame Covid19 and ACE 2 Analysis

## METHODS

### Generation of I-PV plots

Input fasta and variation files were downloaded from [NCBI](https://www.ncbi.nlm.nih.gov/nuccore/), [Ensembl](https://www.ensembl.org/index.html) and [Uniprot](https://www.uniprot.org/) and generated as shown [here](https://www.youtube.com/watch?v=v7bLO1nIrIk).

### Alignments

Sequences available as of 01/04/2020 were downloaded from NCBI. They were aligned using [Clustal Omega](http://www.clustal.org/omega/). Consensus scores were obtained using [Jalview](https://www.jalview.org/). Scores were rescaled between 0 - 1, log transformed, rescaled between 0 - 1 using -3 and 0 as boundaries, square rooted and rescaled between 0 - 10. Taking MT019529.1 as reference, resulting scores were redistributed between existing nucleotides at each column of the alignment.

### Visualization

Alignment analysis were visualized using [lexicon-mono-seq](https://github.com/IbrahimTanyalcin/lexicon-mono-seq).

Protein sequence features were visualized using [I-PV](https://github.com/IbrahimTanyalcin/I-PV).
