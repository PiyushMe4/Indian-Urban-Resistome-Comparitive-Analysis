# Software Documentation

| Software | Version | Purpose | Input | Output |
|---|---|---|---|---|
| **FastQC** | (latest) | Initial read quality assessment | Raw .fastq files | QC reports (HTML/ZIP) |
| **MultiQC** | (latest) | Aggregating QC metrics | FastQC output archives | Summarized QC report |
| **fastp** | (latest) | Read trimming and quality filtering | Raw .fastq files | Cleaned .fastq files |
| **Bowtie2** | 2.x | Host sequence removal (subtraction) | Cleaned .fastq & host index | Host-filtered .fastq files |
| **DIAMOND** | (latest) | Accelerated sequence alignment against CARD | Host-filtered .fastq | Alignment tables (m8/tsv) |
| **Python / Jupyter** | 3.x | Statistical modeling and visualization | Merged ARG matrices | Publication figures (PDF/PNG) |
| **Python Packages** | (various) | pandas, numpy, seaborn, matplotlib, scikit-learn | Dataframes | Plots / Statistics |

*(Note: Centrifuge and taxonomic profiling tools were discarded from the final methodology and are explicitly not included here.)*
