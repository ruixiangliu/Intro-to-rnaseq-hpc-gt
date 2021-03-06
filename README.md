## Introduction to RNA-seq using high-performance computing (HPC)

### Description

This repository has teaching materials for a 2-day Introduction to RNA-sequencing data analysis workshop. This workshop focuses on teaching basic computational skills to enable the effective use of an high-performance computing environment to implement an RNA-seq data analysis workflow. It includes an introduction to shell (bash) and shell scripting. In addition to running the RNA-seq workflow from FASTQ files to count data, the workshop covers best practice guidlelines for RNA-seq experimental design and data organization/management.

> These materials were developed for a trainer-led workshop, but are also amenable to self-guided learning.

### Learning Objectives

1.	Understand the necessity for, and use of, the command line interface (bash) and HPC for analyzing high-throughput sequencing data.
2.	Understand best practices for designing an RNA-seq experiment and analysis the resulting data.


### Contents

**Basics of Shell**

| Lessons            | Estimated Duration |
|:------------------------|:----------|
|[Introduction to the shell](lessons/01_the_filesystem.md) | 70 min |
|[Searching and redirection in shell](lessons/02_searching_files.md) | 45 min |
|[Introduction to the Vim text editor ](lessons/03_vim.md) | 30 min |
|[Shell scripts and `for` loops](lessons/04_loops_and_scripts.md) | 75 min |
|[Permissions and environment variables](lessons/05_permissions_and_environment_variables.md) | 50 min |
|[Project and data organization](lessons/06_data_organization.md) | 40 min |

**HPC and RNA-seq workflow**

| Lessons            | Estimated Duration |
|:------------------------|:----------|
| RNA-seq experimental design best practices | 50 min |
| Introduction to High-Performance Computing | 45 min |
| [RNA-seq data QC with FastQC](lessons/07_assessing_quality.md) | 75 min |
| [RNA-seq workflow: Alignment and Counting](lessons/08_rnaseq_workflow.md) | 90 min |
| [Automating the RNA-seq workflow](lessons/09_automating_workflow.md) | 60 min |
| Alternative workflows for analyzing RNA-seq data | 15 min |
| Quantifying expression using alignment-free methods (Salmon) | 75 min |

## Installations

This workshop requires that the following programs are installed on your laptop: 

**Mac users**

1. [Java](https://www.java.com/en/download/)

2. [Integrative Genomics Viewer (IGV)](https://software.broadinstitute.org/software/igv/download)

3. [Sublime Text](http://www.sublimetext.com/)

**Windows users**

1. [Git Bash](https://git-scm.com/download/win)

2. [Java](https://www.java.com/en/download/)

3. [Integrative Genomics Viewer (IGV)](https://software.broadinstitute.org/software/igv/download)

4. [Notepad++](http://notepad-plus-plus.org/)

***
*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*

* *Some materials used in these lessons were derived from work that is Copyright © Data Carpentry (http://datacarpentry.org/). 
All Data Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).*
