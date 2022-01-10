# Kids First Cloud Credit Program
## Introduction to Kids First and the Kids First Data Resource Center
### Overview of the KF Program
The [Gabriella Miller Kids First Pediatric Research Program (Kids First)](https://commonfund.nih.gov/kidsfirst) is an NIH Common Fund program whose goal is to help researchers uncover new insights into the biology of childhood cancer and structural birth defects, including the discovery of shared genetic pathways between these disorders. 

Since 2015, the Kids First program has funded whole-genome sequencing for [20,000 patients and their families](https://commonfund.nih.gov/kidsfirst/x01projects). The program’s vision is to alleviate suffering from childhood cancer and structural birth defects by fostering collaborative research to uncover the etiology of these diseases and supporting data sharing within the pediatric research community. 

The [Kids First Data Resource Center (DRC)](http://kidsfirstdrc.org/) supports two tools for pediatric disease research. The [Kids First Data Resource Portal](https://portal.kidsfirstdrc.org/) allows users to query, or search, Kids First datasets, build virtual cohorts, or collections, of individual participants, and identify genomic files for analysis. [CAVATICA](https://cavatica.sbgenomics.com/), built by [Seven Bridges Genomics](https://www.sevenbridges.com/), allows users to analyze and visualize data using bioinformatics workflows in a cloud-based environment. Together, this powerful tandem of tools are accelerating research in pediatric cancer and structural birth defects. 

These documents are organized to support all researchers working with Kids First datasets, especially those interested in applying for cloud credits, funding to support cloud-based analysis of Kids First data on our platforms.

### Kids First DRC Harmonized Datasets
The Kids First DRC provides harmonized clinical and genomic datasets through its web platforms. Although each Kids First study originates with a domain-specific expert, the Kids First DRC processes each study according to the same standard workflows. These harmonized datasets are then directly comparable to one another, facilitating cross-disease analyses.

*Harmonized clinical data* includes basic demographic information (age, sex, race and ethnicity). Patient phenotypic data is assigned with [Human Phenotype Ontology (HPO)](https://hpo.jax.org/app/) terms and diagnostic information is harmonized using the [MONDO Disease Ontology](https://www.ebi.ac.uk/ols/ontologies/mondo).

*Harmonized genomic data* includes aligned reads in `BAM` and `CRAM` formats and called variants in `gVCF`, `VCF`, and `MAF` formats. Studies with transcriptomic data include quantified gene expression and called gene fusion events. All Kids First bioinformatic pipelines are provided within this same GitHub repo as well as on CAVATICA for users to review and run analyses on their own files.

| Pipeline | GitHub | CAVATICA App |
| ----------- | ----------- | ----------- |
| **Kids First Data Resource Center Alignment and GATK HaplotypeCaller Workflows** | [GitHub](https://github.com/kids-first/kf-alignment-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-alignment-workflow) |
| **Kids First DRC Joint Genotyping Workflow** | [GitHub](https://github.com/kids-first/kf-jointgenotyping-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-jointgenotyping-refinement-workflow) |
| **Kids First DRC Somatic Variant Workflow** | [GitHub](https://github.com/kids-first/kf-somatic-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-somatic-variant-workflow) |
| **Kids First RNA-Seq Workflow** | [GitHub](https://github.com/kids-first/kf-rnaseq-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-rnaseq-workflow) |

### Presentation at ASHG 2021
For an introduction to Kids First, its platforms, and data process, we encourage you to watch this recent presentation from the ASHG2021 Virtual Meeting.

[![Kids First DRC at ASHG 2021](https://img.youtube.com/vi/uQ0soZQpYCU/0.jpg)](https://www.youtube.com/watch?v=uQ0soZQpYCU)
