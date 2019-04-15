# htseq-merge
R script for combine HTSeq outputs into one read count matrix in R

Ahmed Alhendi (Dr)

Dated: 20 March 2019

# Overview
The HTSeq has extracted counts from each BAM file and created one corresponding text file with column#1 providing Ensembl Gene-IDs and column #2 the raw counts. We need to merge all these tables (within each experiment) into a single table with a leading identifier column followed by one labelled column for each replicate/condition. This is easily done using htseq-merge Rscript.

# Installation 
No installation required


# Usage example

1- Download the Rscript `htseq-merge_all.R` to your Linux/Unix Machine:

```shell
wget "https://github.com/AAlhendi1707/htseq-merge/blob/master/htseq-merge_all.R?raw=true" -O htseq-merge_all.R
```

2- From Linux/UNIX terminal run
```shell
Rscript htseq-combine_all.R <Path_To_HTSEQ_Outputs> <Reacount_matrix_output_name>
```

A detailed example can be found [here](https://ahmedalhendi0.wordpress.com/2019/03/20/combine-htseq-outputs-into-one-read-count-matrix-in-r/)
