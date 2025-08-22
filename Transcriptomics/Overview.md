# Overview
Transcriptomics is the study of the complete set of RNA transcripts (the transcriptome) produced by the genome under specific conditions. It provides insight into gene expression, splicing variants, non-coding RNAs, and regulatory mechanisms.  
Applications include:
1. Identifying differentially expressed genes in diseases.
2. Understanding cell-type specific expression (single-cell RNA-Seq).
3. Exploring regulatory networks (transcription factors, miRNAs, lncRNAs).
4. Biomarker and therapeutic target discovery.

# 🛠️Tools and Databases
## Data Repositories
1. GEO (NCBI Gene Expression Omnibus) – RNA-seq, microarray datasets.
2. ArrayExpress (EBI) – functional genomics experiments.
3. SRA (Sequence Read Archive) – raw sequencing reads.
4. Human Protein Atlas – tissue-specific expression.
## Quality Control and Preprocessing
1. FastQC – raw read quality check.
2. Trimmomatic / Cutadapt – adapter/quality trimming.
3. MultiQC – combined QC reports.
## Read Alignment and Quantification
1. STAR – spliced read alignment.
2. HISAT2 – fast alignment for RNA-seq.
3. Salmon / Kallisto – alignment-free quantification.
4. RSEM – transcript abundance estimation.
## Differential Expression Analysis
1. DESeq2 (R) – negative binomial modeling.
2. edgeR (R) – DE analysis for RNA-seq.
3. limma (R) – originally for microarrays, works with RNA-seq too.
## Functional Enrichment and Pathways
1. clusterProfiler (R) – GO, KEGG enrichment.
2. GSEA (Gene Set Enrichment Analysis) – pathway-level changes.
3. DAVID / Enrichr – gene function databases.
## Single-cell Transcriptomics (scRNA-seq)
1. Seurat (R) – single-cell data processing.
2. Scanpy (Python) – scalable single-cell analysis.
3. CellRanger (10x Genomics) – preprocessing single-cell RNA-seq.
# Roadmap to Learning Transcriptomics 🎯
## Step 1: Fundamentals
1. Revise molecular biology basics: transcription, splicing, RNA types.
2. Learn about sequencing technologies: microarrays vs. RNA-seq vs. scRNA-seq.
## Step 2: Data Acquisition and Quality Control
1. Practice downloading data from GEO or SRA.
2. Run FastQC → Trimmomatic → MultiQC on a dataset.
## Step 3: Mapping and Quantification
1. Align reads with HISAT2 or STAR.
2. Try alignment-free quantification with Salmon/Kallisto.
3. Generate a count matrix for downstream analysis.
## Step 4: Differential Expression (DE)
1. Use DESeq2 (R) to compare treated vs. control samples.
2. Visualize results with volcano plots, heatmaps, PCA.
## Step 5: Functional Analysis
1. Perform GO & KEGG enrichment using clusterProfiler.
2. Explore gene sets with GSEA.
## Step 6: Single-cell Transcriptomics
1. Learn Seurat (R) or Scanpy (Python).
2. Explore clustering, trajectory inference, and cell–cell interaction analysis.
## Step 7: Integration and Reproducibility
1. Learn workflow managers (Snakemake, Nextflow).
2. Use Docker/Conda for reproducibility.
3. Document workflows on GitHub.
