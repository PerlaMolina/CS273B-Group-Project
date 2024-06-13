# CS273B-Group-Project

# Spatial Transcriptomics in Alzheimer’s Disease: Predicting Disease Stages Using CNNs
By Sohaib Hassan, Perla Molina, Junwei (Ivy) Sun, Shouvik Mani

Abstract
Advances in single-cell technology have enabled the detailed analysis of cell type compositions
and gene expressions at the individual cell level, enhancing our understanding of cellular
heterogeneity across various tissues. With the advent of spatial omics, researchers can now
pinpoint the exact locations of these single cells within tissue samples, offering unprecedented
opportunities to utilize spatial and cell-level data for predicting disease outcomes and patient
prognosis. Methods like SPACE-GM have demonstrated the potential to model disease
microenvironments and leverage spatial motifs for prognosis, primarily using proteomics data
from Co-Detection from Indexing (CODEX) imaging. However, the exploration of spatially-aware
transcriptomics remains limited. In this project, we utilized spatial transcriptomics data,
incorporating spatial coordinates, cell type information, and gene expression profiles from
middle temporal gyrus (MTG) sections affected by Alzheimer’s Disease (AD), to predict disease
progression. We developed a Convolutional Neural Network (CNN) that integrates a cell type
tensor to predict dementia status and LATE-stage labels. Our objectives were to: 1) leverage
spatial coordinates, cell types, and gene expression data from AD spatial transcriptomics to
predict patient dementia status and LATE-NC stages; 2) pinpoint specific cell types and genes
that contribute the most to disease progression through model interpretation; and 3) evaluate
the strengths and limitations of models applied to spatial transcriptomics data. This work aims
to advance the understanding and predictive capability of spatial transcriptomics in the context
of AD, potentially guiding more effective diagnostic and therapeutic strategies.
