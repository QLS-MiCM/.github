# QLS-MiCM Workshop Themes Analysis

*Analysis Date: January 2026*

This document provides a comprehensive analysis of the current QLS-MiCM workshop offerings, identifies thematic categories, and recommends missing topics for future development.

---

## Current Workshop Inventory

The QLS-MiCM organization currently hosts **37 repositories** covering various computational biology and data science topics.

---

## Workshop Themes & Categories

### Theme 1: Programming Fundamentals
*Foundation skills for computational work*

| Workshop | Language | Description |
|----------|----------|-------------|
| IntroToPython | Python | Python fundamentals |
| IntroToR | R | R programming basics |
| Intro-to-UNIX | Shell | Command-line computing |
| Intro-to-MATLAB | MATLAB | MATLAB introduction |
| Exploring_MATLAB | MATLAB | Extended MATLAB exploration |
| HowToThinkInCode | - | Computational thinking concepts |
| IntroToGitHub | R | Version control basics |
| intermediate_python_fall_2023 | Python | Intermediate Python skills |

**Coverage Assessment:** ✅ Strong coverage of major scientific computing languages

---

### Theme 2: Data Processing & Wrangling
*Handling and transforming data*

| Workshop | Language | Description |
|----------|----------|-------------|
| DataProcessingInPython | Python | Data manipulation with Python |
| Data_Wrangling_Fall2022 | R | Data wrangling techniques |
| DataProcessingForGenetics | Python | Genetics-specific data processing |

**Coverage Assessment:** ⚠️ Moderate - could expand with more domain-specific data handling

---

### Theme 3: Statistics & Visualization
*Statistical methods and data presentation*

| Workshop | Language | Description |
|----------|----------|-------------|
| StatsInR | R | Statistical analysis fundamentals |
| Advanced-Data-Visualization | R | Advanced visualization (most popular: 9 stars) |
| 2022_Dim_Reduction | Python | Dimensionality reduction techniques |

**Coverage Assessment:** ⚠️ Moderate - statistics coverage could be expanded

---

### Theme 4: RNA Sequencing & Transcriptomics
*Bulk RNA-seq analysis pipeline*

| Workshop | Language | Description |
|----------|----------|-------------|
| Introduction-to-RNA-seq | Shell | RNA-seq basics |
| RNA-seq-Data-Processing | Python | RNA-seq data processing |
| Statistical-Foundations-of-RNA-seq | R | Statistical methods for RNA-seq |
| Differential-Gene-Expression-Analysis | HTML/R | DGE analysis |
| BootcampF22_RNAseqQuantification | - | RNA-seq quantification |
| BootcampF22_IntroRNAseqFormats | - | RNA-seq file formats |
| BootcampF22_LongRead_RNAseq | - | Long-read sequencing |
| Transcriptomics-Bootcamp-2022 | - | Comprehensive bootcamp |
| ngsintro_summer2022 | HTML | NGS formats and preprocessing |

**Coverage Assessment:** ✅ Excellent - comprehensive RNA-seq curriculum

---

### Theme 5: Single-Cell Analysis
*Single-cell technologies*

| Workshop | Language | Description |
|----------|----------|-------------|
| Single-Cell-RNA-seq | R | Single-cell RNA-seq analysis |
| BootcampF22_Intro_Singlecell | HTML | Introduction to single-cell |
| BootcampF22_singleCell_Clustering_trajectoryInference | - | Clustering & trajectory analysis |

**Coverage Assessment:** ✅ Good foundation coverage

---

### Theme 6: Genetics & Genomics
*Genetic variation and association studies*

| Workshop | Language | Description |
|----------|----------|-------------|
| GWAS-and-Polygenic-Risk-Scores | Python | GWAS and PRS analysis |
| Intro_PRS | R | Introduction to PRS |
| ChIP_seq | - | ChIP-seq analysis (forked) |
| Proteogenomics | HTML | Proteogenomics approaches |

**Coverage Assessment:** ⚠️ Moderate - could expand variant analysis

---

### Theme 7: Machine Learning & AI
*ML/AI applications in life sciences*

| Workshop | Language | Description |
|----------|----------|-------------|
| Summer23-Intro-to-ML-with-Python | Python | ML fundamentals |
| SupervisedML | Python | Supervised learning methods |
| Fall23_Intro-to-CNNs | Python | Convolutional neural networks |

**Coverage Assessment:** ⚠️ Limited - significant expansion opportunity

---

### Theme 8: Structural Biology & Simulations
*Molecular structures and dynamics*

| Workshop | Language | Description |
|----------|----------|-------------|
| IntroToMolecularSimulations | Python | Molecular dynamics basics |
| ImageProcessingInMATLAB | MATLAB | Image processing for biology |

**Coverage Assessment:** ❌ Minimal - major gap area

---

## Gap Analysis: Missing Topics

### High Priority (Essential for Modern Computational Biology)

#### 1. **Deep Learning & Neural Networks Expansion**
- Transformer models for biology (protein language models, genomic foundation models)
- Graph neural networks for molecular data
- Generative AI applications in drug discovery
- Natural language processing for biomedical text mining

#### 2. **Cloud Computing & High-Performance Computing**
- Introduction to HPC clusters (SLURM, PBS)
- Cloud computing for bioinformatics (AWS, Google Cloud, Azure)
- Containerization (Docker, Singularity) for reproducible research
- Workflow managers (Nextflow, Snakemake)

#### 3. **Multi-Omics Integration**
- Integrative multi-omics analysis
- Spatial transcriptomics
- ATAC-seq and chromatin accessibility
- Metabolomics data analysis
- Epigenomics (DNA methylation, histone modifications)

#### 4. **Reproducibility & Best Practices**
- Reproducible research practices
- Data management and FAIR principles
- Scientific computing best practices
- Literate programming (R Markdown, Quarto, Jupyter best practices)

### Medium Priority (Valuable Additions)

#### 5. **Variant Analysis & Clinical Genomics**
- Variant calling and annotation
- Structural variant analysis
- Clinical interpretation of variants
- Pharmacogenomics

#### 6. **Structural Bioinformatics**
- Protein structure prediction (AlphaFold, ESMFold)
- Molecular docking
- Structure-based drug design
- Cryo-EM data processing

#### 7. **Metagenomics & Microbiome**
- 16S rRNA analysis
- Shotgun metagenomics
- Microbiome data analysis with QIIME2
- Functional annotation of microbial communities

#### 8. **Systems Biology**
- Pathway analysis
- Network biology
- Gene regulatory networks
- Metabolic modeling

### Lower Priority (Specialized Topics)

#### 9. **Time Series & Longitudinal Data**
- Time series analysis for biological data
- Longitudinal study design and analysis
- Dynamic modeling

#### 10. **Advanced Statistics**
- Bayesian statistics for biology
- Causal inference methods
- Survival analysis in clinical research
- Mixed effects models

#### 11. **Image Analysis**
- Deep learning for biological image analysis
- Cell segmentation and tracking
- Histopathology image analysis
- High-content screening analysis

#### 12. **Database & Data Engineering**
- SQL for biological databases
- Building and querying biological databases
- APIs for biological data retrieval
- Data pipelines and ETL

---

## Recommendations Summary

### Immediate Development Priorities

| Rank | Workshop Topic | Rationale |
|------|---------------|-----------|
| 1 | **Workflow Managers (Nextflow/Snakemake)** | Critical for reproducible pipelines; bridges all sequencing workshops |
| 2 | **Intro to HPC & Cloud Computing** | Essential skill gap; enables larger-scale analyses |
| 3 | **Multi-Omics Integration** | Builds on strong RNA-seq foundation |
| 4 | **AlphaFold & Protein Structure Prediction** | High interest topic; minimal structural biology coverage |
| 5 | **Spatial Transcriptomics** | Natural extension of single-cell expertise |

### Suggested Workshop Series

**Series A: From Sequences to Systems**
1. Intro to RNA-seq (existing)
2. Single-Cell RNA-seq (existing)
3. *NEW: Spatial Transcriptomics*
4. *NEW: Multi-Omics Integration*

**Series B: Reproducible Bioinformatics**
1. IntroToGitHub (existing)
2. *NEW: Containerization with Docker/Singularity*
3. *NEW: Workflow Managers*
4. *NEW: HPC & Cloud Computing*

**Series C: AI for Life Sciences**
1. Intro to ML (existing)
2. Supervised ML (existing)
3. CNNs (existing)
4. *NEW: Deep Learning for Genomics*
5. *NEW: Protein Language Models & AlphaFold*

**Series D: Genomic Variation**
1. GWAS & PRS (existing)
2. *NEW: Variant Calling & Annotation*
3. *NEW: Clinical Genomics Interpretation*

---

## Current Strengths

1. **RNA-seq Pipeline**: Comprehensive coverage from basics to advanced analysis
2. **Programming Languages**: Good coverage of R, Python, MATLAB, and Shell
3. **Single-Cell**: Solid foundation with room to grow
4. **Accessibility**: Materials are public and well-organized

## Areas for Growth

1. **Reproducibility Infrastructure**: Containers, workflows, version control expansion
2. **AI/ML Depth**: Current coverage is introductory; deeper content needed
3. **Structural Biology**: Minimal coverage despite field importance
4. **Cloud/HPC**: Missing critical computational infrastructure skills
5. **Multi-Omics**: Siloed by data type; integration workshops needed

---

## Appendix: Complete Repository List

| Repository | Primary Language | Stars | Theme |
|------------|-----------------|-------|-------|
| Advanced-Data-Visualization | R | 9 | Statistics & Viz |
| SupervisedML | Python | - | Machine Learning |
| Workshop_Template | - | - | Infrastructure |
| DataProcessingInPython | Python | - | Data Processing |
| Exploring_MATLAB | MATLAB | - | Programming |
| IntroToPython | Python | - | Programming |
| Single-Cell-RNA-seq | R | 2 | Single-Cell |
| Statistical-Foundations-of-RNA-seq | R | 3 | RNA-seq |
| Introduction-to-RNA-seq | Shell | - | RNA-seq |
| RNA-seq-Data-Processing | Python | - | RNA-seq |
| Differential-Gene-Expression-Analysis | HTML | - | RNA-seq |
| DataProcessingForGenetics | Python | - | Genetics |
| GWAS-and-Polygenic-Risk-Scores | Python | - | Genetics |
| Proteogenomics | HTML | - | Genetics |
| IntroToR | R | - | Programming |
| StatsInR | R | - | Statistics |
| Intro-to-UNIX | Shell | 2 | Programming |
| Intro-to-MATLAB | MATLAB | - | Programming |
| HowToThinkInCode | - | - | Programming |
| IntroToGitHub | R | - | Programming |
| IntroToMolecularSimulations | Python | 2 | Structural |
| Fall23_Intro-to-CNNs | Python | - | Machine Learning |
| Summer23-Intro-to-ML-with-Python | Python | 2 | Machine Learning |
| Transcriptomics-Bootcamp-2022 | - | 3 | RNA-seq |
| intermediate_python_fall_2023 | Python | - | Programming |
| ImageProcessingInMATLAB | MATLAB | - | Structural |
| ChIP_seq | - | - | Genetics |
| BootcampF22_RNAseqQuantification | - | - | RNA-seq |
| BootcampF22_IntroRNAseqFormats | - | - | RNA-seq |
| BootcampF22_Intro_Singlecell | HTML | - | Single-Cell |
| BootcampF22_singleCell_Clustering_trajectoryInference | - | - | Single-Cell |
| BootcampF22_LongRead_RNAseq | - | - | RNA-seq |
| Data_Wrangling_Fall2022 | R | - | Data Processing |
| ngsintro_summer2022 | HTML | - | RNA-seq |
| Intro_PRS | R | - | Genetics |
| 2022_Dim_Reduction | Python | - | Statistics |

---

*Document prepared for QLS-MiCM workshop planning*
