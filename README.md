## Mouse_Whole_Brain_Interactome

Mouse Brain interactome that was used in the analysis that identied Nr3c1 as candidate driver for chronic alcohol addiction. 

Associated Paper : 
[Identification of Neurodegenerative Factors Using Translatome-Regulatory Network Analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4410476/)

Interactome was reverse engineered with ARACNe from a mouse whole brain expression dataset (437 samples, GSE10415). ARACNe was run with 100 bootstrap iterations using all array probes that mapped to a set of 1,507 mouse transcriptional regulators (defined as genes annotated in the Gene Ontology Molecular Function database as GO:0003700 - ‘transcription factor activity’) for the human dataset. Parameters were set to 0 DPI tolerance and a MI P value threshold (P<10-7), as recommended for bootstrap ARACNe analysis of a dataset with this size, to achieve a Bonferroni corrected significance (P = 0.05) for getting a single false-positive in the dataset.
