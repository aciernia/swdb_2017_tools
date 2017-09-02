This project examined the relationship between gene expression, morphology and electrophysiology from the cell types database

Single cell RNAseq data was taken from Tasic, et al. 2016: http://www.nature.com/neuro/journal/v19/n2/full/nn.4216.html?WT.feed_name=subjects_development-of-the-nervous-system&foxtrotcallback=true
RPKM values for single cells from V1, crelines, and layers were downloaded from:http://casestudies.brain-map.org/celltax

Morphology and Electrophysiology data were taken from the SDK from the Cell Types Observatory: http://celltypes.brain-map.org/

Analysis included:
1. Comparing gene expression for each cre line/layer to each measure from the morphology and electrophysiology data
by partial correlation analysis
2.  Go term analysis was conduced on significantly correlated genes (FDR corrected pvalues from partial correlation)
3. Variation in gene expression within each cre line was compared to variation in morphology and electrophysiology measures
4. Comparison of selected signature marker genes from Tasic, et al 2016 were examined within the brainspan data to attempt to 
identify the earliest timepoint of detection of a specific cell type with the developing human brain