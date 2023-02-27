# Centrifuge+
Classifier for metagenomic sequences

[Centrifuge+] is  based on Centrifuge with the same 
methods of reference database sequence compression and classification 
of microbial sequences, but is different from Centrifuge on the statistical model, 
which considers the influence of similarities among species in the reference 
database on estimating species abundance. The modified statistical model 
has been coded in the file aln_sink.h of Centrifuge developed by Kim et al. (2016). The modified Centrifuge is under the terms of the GNU General Public License and named as Centrifuge+. Centrifuge+ improved 
the accuracy of abundance estimates by modifying the statistical model in 
Centrifuge. The more accurate abundance estimates will be benefit to improve 
the precision-recall analysis for species identification.


The details on installing and running Centrifuge+ are the same to Centrifuge.
Please look at MANUAL.

