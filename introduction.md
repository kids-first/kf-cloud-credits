# Kids First Cloud Credit Program
## Introduction to Kids First and the Kids First Data Resource Center
### Overview of the Kids First Program
The [NIH Common Fund](https://commonfund.nih.gov/) is a funding entity within the NIH that supports bold scientific programs that catalyze discovery across all biomedical and behavioral research. These programs create a space where investigators and multiple NIH Institutes and Centers collaborate on innovative research expected to address high priority challenges for the NIH as a whole and make a broader impact in the scientific community.

The [Gabriella Miller Kids First Pediatric Research Program (Kids First)](https://commonfund.nih.gov/kidsfirst) is a trans-NIH Common Fund program whose goal is to help researchers uncover new insights into the biology of childhood cancer and structural birth defects, including the discovery of shared genetic pathways between these disorders. 

Since 2015, the Kids First program has funded whole-genome sequencing for [20,000 patients and their families](https://commonfund.nih.gov/kidsfirst/x01projects). The program’s vision is to alleviate suffering from childhood cancer and structural birth defects by fostering collaborative research to uncover the etiology of these diseases and supporting data sharing within the pediatric research community. 

The [Kids First Data Resource Center (DRC)](http://kidsfirstdrc.org/) supports two tools for pediatric disease research. The [Kids First Data Resource Portal](https://portal.kidsfirstdrc.org/) allows users to query, or search, Kids First datasets, build virtual cohorts, or collections, of individual participants, and identify genomic files for analysis. [CAVATICA](https://cavatica.sbgenomics.com/), built by [Seven Bridges Genomics](https://www.sevenbridges.com/), allows users to analyze and visualize data using bioinformatics workflows in a cloud-based environment. Together, this powerful tandem of tools are accelerating research in pediatric cancer and structural birth defects. 

These documents are organized to support all researchers working with Kids First datasets, especially those interested in applying for cloud credits, funding to support cloud-based analysis of Kids First data on our platforms.

### Why Choose Cloud-Based Analysis?
High performance computing necessary for genome-scale analysis requires advanced computer infrastructure. By networking a collection of servers and storage devices, researchers can utilize these machines to carry out the large-scale calculations and computations required for genome alignment and variant calling. High performance computing incurs large upfront costs associated with purchasing equipment as well as ongoing costs associated with staff to maintain this environment and electricity to keep everything running.

Cloud-based computing allows access to this same infrastructure without owning and managing the machines themselves. Rather than purchase the computers themselves, users of cloud computing pay to work in this environment on an amount relative to their usage. Dozens of machines can be activated rapidly when an analysis is beginning - and then shut off just as quickly once the work is complete and they are no longer needed.
CAVATICA provides the service of activating and deactivating these computers when called upon by its users. This allows researchers to focus on the biological and bioinformatic aspects of their project, such as experimental design and analysis, without having to set up cloud infrastructure from scratch.

Data analysis requires genomic files to be in the same location as the software tools that are processing them. The increasing scale and size of genomic data is becoming a burden to moving these files onto an institutional location where the software has been installed. Cloud-based analysis offers an alternative – move the relatively small software files to the location where the data is stored.

Furthermore, cloud computing also allows users to share data seamlessly with collaborators. Any collaborator can create an account and receive access to the same platforms. Useful data products, tools, and results can also be quickly disseminated and shared with the broader research community following publication.

Overall, cloud platforms represent a sustainable alternative to users downloading datasets and carrying out analysis locally. For more information, the [2018 NIH Strategic Plan for Data Science](https://datascience.nih.gov/nih-strategic-plan-data-science) emphasizes the powerful and cost-effective role cloud computing can play in the future of research by streamlining data use, allowing rapid access, and minimizing infrastructure and maintenance costs.

### Kids First DRC Harmonized Datasets
The Kids First DRC provides harmonized clinical and genomic datasets through its web platforms. The Kids First DRC receives source clinical data from each independent investigator, along with paired genomic sequencing produced by one of their sequencing center partners. The Kids First DRC processes each study dataset according to the same standard workflows, producing harmonized datasets which are directly comparable to one another, facilitating cross-disease analyses.

*Harmonized clinical data* includes basic demographic information (age, sex, race and ethnicity). Patient phenotypic data is assigned with [Human Phenotype Ontology (HPO)](https://hpo.jax.org/app/) terms and diagnostic information is harmonized using the [MONDO Disease Ontology](https://www.ebi.ac.uk/ols/ontologies/mondo). The Kids First DRC uses these to ontologies provide a consistent vocabulary of terminology across all Kids First Studies for use on the Kids First Portal and analyses by investigators.

Harmonized genomic data includes aligned reads and called variants. Studies with transcriptomic data include quantified gene expression and called gene fusion events. All Kids First bioinformatic pipelines, workflows of linked software tools for processing genomic data, are provided within the Kids First DRC’s GitHub repository as well as on CAVATICA for users to review and run analyses on their own files.

| Pipeline | GitHub | CAVATICA App |
| ----------- | ----------- | ----------- |
| **Kids First Data Resource Center Alignment and GATK HaplotypeCaller Workflows** | [GitHub](https://github.com/kids-first/kf-alignment-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-alignment-workflow) |
| **Kids First DRC Joint Genotyping Workflow** | [GitHub](https://github.com/kids-first/kf-jointgenotyping-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-jointgenotyping-refinement-workflow) |
| **Kids First DRC Somatic Variant Workflow** | [GitHub](https://github.com/kids-first/kf-somatic-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-somatic-variant-workflow) |
| **Kids First RNA-Seq Workflow** | [GitHub](https://github.com/kids-first/kf-rnaseq-workflow) | [CAVATICA App](https://cavatica.sbgenomics.com/public/apps/cavatica/apps-publisher/kfdrc-rnaseq-workflow) |

### Presentation: Introduction to Kids First Resources
For an introduction to Kids First, its platforms, and data process, we encourage you to watch this recent presentation from the ASHG2021 Virtual Meeting.

[![Kids First DRC at ASHG 2021](https://img.youtube.com/vi/uQ0soZQpYCU/0.jpg)](https://www.youtube.com/watch?v=uQ0soZQpYCU)
