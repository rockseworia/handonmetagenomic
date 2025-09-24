# handonmetagenomic
This document is a simple guidance of conducting metagenomic analysis.


This guidnce included two ways of conducting metagenomic analysis: qualit_control----hostremove----assembly----bin----drep----GTDB-tk----anno
and also, the annotation using contigs, that is, kraken2 and prodigal


# Requirement
Main CPU and ram limitations are in the assembly and bin. For assembly, one sample may take 10 hours to finish assembly with 20 threads. Bin require at least 500GB ram(For gut microbiota, 180GB can approximately suitbale for runing 2-4 samples in one time), I would suggest you to use a server or work station with higher ram.
