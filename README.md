# htseq-merge
R script for combine HTSeq outputs into one read count matrix in R

Ahmed Alhendi (Dr)

Dated: 20 March 2019

# Overview
The HTSeq has extracted counts from each BAM file and created one corresponding text file with column#1 providing Ensembl Gene-IDs and column #2 the raw counts. We need to merge all these tables (within each experiment) into a single table with a leading identifier column followed by one labelled column for each replicate/condition. This is easily done using htseq-merge Rscript

# Installation 
No installation required


# Usage 

From Linux/UNIX terminal run

Rscript htseq-combine_all.R <Path_To_HTSEQ_Outputs> <Reacount_matrix_output_name>
