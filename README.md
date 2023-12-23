## Data Source
The data is sourced from TCGA, specifically the BRCA cohort, using the `curatedTCGAData` R package.

## Analysis
- **Downloading TCGA Data**: The analysis begins with downloading multiomic data (RNASeq, Mutation, Methylation) for the BRCA cohort using `curatedTCGAData`.
- **Sample Mapping and Clinical Data Analysis**: Processing sample mapping and clinical data, including creating factors for pathology stages and examining relationships between tumor stage and vital status.
- **Mutation Data Analysis**: Accessing and processing mutation data, analyzing mutation prevalence, and ensuring consistency with clinical data.
- **RNA-Seq Data Analysis**: Analyzing gene expression levels and examining the relationship between gene expression and clinical features.
- **Methylation Data Analysis**: Processing methylation data and preparing for correlation analysis.
- **Correlation Analysis**: Calculating correlations between methylation and RNA-Seq data for specific genes.
- **Visualization**: Creating visualizations for mutation frequencies, gene expressions, and methylation patterns.

## Getting Started
1. Clone the repository.
2. Install required R packages.
3. Run the Rmd notebooks to replicate the analysis.

## Dependencies
- R version 4.3.1

Refer to `requirements.txt` for a full list of required R packages.

## Author
Tarsus Lam
