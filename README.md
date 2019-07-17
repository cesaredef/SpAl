# SpAl
Estimating Sthe proportion of spurious alignments in ancient DNA as escribed in de Filippo, Meyer and Prüfer, "Quantifying and reducing spurious alignments for the analysis of ultra-short ancient DNA sequences" 2018 BMC Biology 2018 16:121.

Although the method is applied directly to hominin DNA, it works with any spiecies as long as there is a close reference genome and some data of the variation within spieces.

Make sure you have the following software/tool/languages/packages installed: (1) samtools and tabix (2) python3 (including pysam and scipy.stats module)
(3) MapL.pl, i.e. our script to pre-filter bam files for mapability by taking fragment length into account.

