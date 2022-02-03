# Kids First Cloud Credit Program
## Exploring Datasets
The Kids First Program uses [the X01 funding mechanism](https://commonfund.nih.gov/kidsfirst/x01projects) in support of projects studying the underlying genetic basis of pediatric cancers and structural birth defects. Clinical data from the project investigators and genetic data from sequencing center partners are harmonized together by the Kids First DRC to support the research community.

The harmonized clinical and genomic datasets are available to access through the [Kids First Data Resource Portal](https://portal.kidsfirstdrc.org/). Once users log in, they can explore the available datasets using the [Studies](https://portal.kidsfirstdrc.org/studies) and [Explore Data](https://portal.kidsfirstdrc.org/explore) tools. Information about studies is also available outside the Portal in the Kids First [Studies and Access Page](https://www.notion.so/d3b/Studies-and-Access-a5d2f55a8b40461eac5bf32d9483e90f) in the [Kids First DRC Help Center](https://www.notion.so/d3b/Kids-First-DRC-Help-Center-c26b36ff66564417834f3f264475d10a). Once users identify studies for their research project, they have immediate access to open-source files and can request access to the controlled-access files within the datasets through [dbGaP](https://www.ncbi.nlm.nih.gov/gap/).

---
### Logging into the Kids First Data Resource Portal
Users can log in to the Kids First Data Portal using either...

1. The NIH Research Authentication Server to log in with an eRA Commons ID
2. An ORCID Login
3. Any Google-autneticated email address, such as a Gmail account
<img src="https://github.com/kids-first/kf-cloud-credits/blob/main/assets/LoginResearchAuthService.gif" width="800" align="center">

---
### Exploring Data on the Kids First Portal
Once logged in, the Portal's `Explore Data` Tool allows users to build a virtual cohort of participants based on clinical data fields, such as diagnosis, phenotype, or demographic information. By using the menus to apply filters, researchers can identify specific  

<img src="https://github.com/kids-first/kf-cloud-credits/blob/main/assets/ExploreDatasets.gif" width="800" align="center">

A demonstration of how to use the Explore Data tool from a recent workshop is [available here](https://youtu.be/uQ0soZQpYCU?t=1368).

---
### Exploring Studies on the Kids First Portal
Users can also review data on the Portal at a broad level using its `Studies` tab. This tab allows users to see an overview of studies on the Portal, including the number of participants and the number of data files that are available separated by file type. Links out to dbGaP are also available for each study. 

A demonstration of how to use the Studies tab from a recent workshop is [available here](https://youtu.be/uQ0soZQpYCU?t=1315).

---
### Studies and Access
The Studies and Access page within the Kids First DRC Help Center is another way to familiarize yourself with available datasets outside of the Portal. You can navigate to the page directly from the web [(linked here)](https://www.notion.so/d3b/Studies-and-Access-a5d2f55a8b40461eac5bf32d9483e90f?p=4726f88720474c5cad0a755b47dbc63d) or navigate to it through the Portal iteself.

<img src="https://github.com/kids-first/kf-cloud-credits/blob/main/assets/StudiesAndAccess.gif" width="800" align="center">

The Studies and Access page houses more information about the individual studies, including links to the original author abstracts and dbGaP study pages.

---
### Open- and Controlled-Access Datasets
While users are able to browse all available in the Kids First Portal, they may be limited to which files they can access for analysis. Kids First DRC deliverables are organized into two broad categories. Open-access files are available for immediate access and analysis by any user who creates an account on the Kids First Portal. Controlled-access files require dbGaP approval before access is granted.

| | Open-Access Files | Controlled-Access Files |
| ----------- | ----------- | ----------- |
| [Alignment and GATK Haplotype Caller](https://github.com/kids-first/kf-alignment-workflow) | -- | `Aligned Reads`; `Germline Variants in gVCF Format` |
| [Joint-Genotyping Workflow](https://github.com/kids-first/kf-jointgenotyping-workflow) | -- | `Trio-Based Joint-Called Germline Variants` |
| [Somatic Workflow](https://github.com/kids-first/kf-somatic-workflow) | `Annotated SNVs with Predicted Germline Variants Removed`; `Copy Number Variants`; `Structural Variants` | `Annotated SNVs with Predicted Germline Variants Flagged` |
| [RNA-Seq Workflow](https://github.com/kids-first/kf-rnaseq-workflow) | `Quantified Gene Expression`; `Called Gene Fusions` | `Aligned Reads`; `Unaligned Reads` |

Both levels of access require users to accept [the Kids First DRC Disclaimers, Terms & Conditions, and Privacy Policy](https://kidsfirstdrc.org/policies/), as they agreed to follow upon creating their Kids First Portal account.

Requesting dbGaP access requires a proposal submission. dbGaP has provided their own documentation with tips for preparing a successful request, as well as their own tutorial video to support users in the submission process.

[dbGaP - Tips for Preparing a Successful Data Access Request](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/GetPdf.cgi?document_name=GeneralAAInstructions.pdf)

[![dbGaP: Apply for Controlled Access Data](https://img.youtube.com/vi/m0xp_cCO7kA/0.jpg)](https://www.youtube.com/watch?v=m0xp_cCO7kA)

This submission can also help prepare users for applying for computational cloud credits to analyze these data on the Kids First DRC's cloud-based analysis platform [CAVATICA](https://cavatica.sbgenomics.com/). The platform allows users to run analyses with either existing applications or by developing one's own workflows and performing interactive analyses with Jupyter notebooks, achieved through the application Data Cruncher.
