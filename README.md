# COVID19_Host_Response_DESeq2

# Host Transcriptomic Response to SARS-Cov-2 Infection

# Overview
The project analyses the Host transcriptomic response to SARS-Cov-2 infection using RNA-Seq data from NHBE (Primary human bronchial epithelial ) cells.

| Category | Details |
| Dataset | GSE147507 (NCBI GEO)|
| Cell Type | NHBE (primary human bronchial epithelial cells) |
|Sequencing | Illumina NextSeq 500, single-end |

## Total samples analyzed = 24

## Tools and Technologies
| Step | Tools |
|------|-------|
| **Data Download** | AWS CLI, SRA Tools |
| **Quality Control** | FastQC, Trim Galore, MultiQC |
| **Alignment** | STAR (splice-aware aligner) |
| **Quantification** | featureCounts (Subread package) |
| **DGE Analysis** | DESeq2 (R/Bioconductor) |
| **Visualization** | ggplot2, pheatmap |
| **Annotation** | biomaRt |

## Key findings 
### Known SARS-CoV-2 Response Genes (Expected to be Upregulated)

| Gene | Function | Expected in Your Results |
|------|----------|--------------------------|
| **CSF3** | Colony stimulating factor 3 | ✅ Upregulated |
| **CXCL8** | Chemokine (IL-8) | ✅ Upregulated |
| **ISG15** | Interferon-stimulated gene | ✅ Upregulated |
| **MX1** | Antiviral GTPase | ✅ Upregulated |
| **OAS1** | Antiviral enzyme | ✅ Upregulated |
| **STAT1** | IFN signaling transcription factor | ✅ Upregulated |

## Biological interpretation
NHBE is Normal Human Bronchial Epithelial cells these are the primary target cells of SARS-Cov-2 in the respiratory tract 

## Key pathways affected
- Cytokine-cytokine receptor interaction
- Interferon signaling
- Inflammatory response

  
