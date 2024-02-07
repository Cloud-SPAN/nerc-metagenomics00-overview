---

---
This hands-on, online course teaches data analysis for metagenomics projects. It is aimed at those with little or no experience of using high performance computing (HPC) for data analysis. In the course we will cover:
- navigating file directories and using the command line
- logging into a remote cloud instance
- using common commands and running analysis programs in the command line
- what is metagenomics?
- following a metagenomics analysis workflow including:
  - performing quality control on reads
  - assembly of reads into a metagenome
  - improving your assembly with polishing
  - binning into species/metagenome-assembled genomes (MAGs)
  - taxonomic assignment and functional annotation using your binned reads

The course is taught as a mixture of live coding, online lectures, self-study and drop-in sessions.

> ## Prerequisites
> This course assumes no prior experience with the tools covered in the workshop but learners are expected to have some familiarity with biological concepts, including the concept of genomes and microbiomes. Participants should bring their own laptops and plan to participate actively.
> To get started, follow the directions in the Setup tab to get access to the required software and data for this workshop. **Windows users** need to install Git Bash in their laptop. **Mac users** may need to configure the **terminal** program in their laptop to use the Bash shell.
>
{: .prereq}

> ## Data
> This course uses data from a 2022 paper published in BMC Environmental Microbiome titled [In-depth characterization of denitrifier communities across different soil ecosystems in the tundra](https://environmentalmicrobiome.biomedcentral.com/articles/10.1186/s40793-022-00424-2). In this course we will compare data from two of the sites studied.
> 
> You can read more about the data used in the course [here](data/index.html).
{: .prereq}

# Course format

This workshop is designed to be run on pre-imaged Amazon Web Services (AWS) instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI). We will give you details as to how to access these instances after registration.

The course will take place over three weeks and will combine live coding and teaching with offline work. We will guide you through the analysis each session but some steps may need to completed offline due to the amount of time they take to complete. There will also be drop-in sessions to offer support and troubleshooting help, and a Slack workspace for questions.

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Files and Directories](https://cloud-span.github.io/nerc-metagenomics01-file-directories/) |Learn about files and directories, log onto a cloud instance and get a basic introduction to the shell.|
| [Using the Command Line](https://cloud-span.github.io/nerc-metagenomics02-command-line/)  |Learn more about using the shell to navigate directories, manipulate and search files and use basic loops to iterate commands.|
| [QC & Assembly](https://cloud-span.github.io/nerc-metagenomics03-qc-assembly/) | How to quality control and assemble a genome.|
| [Polishing](https://cloud-span.github.io/nerc-metagenomics04-polishing/) | How to use short reads to polish your metagenome assembly |
| [Binning & Functional Annotation](https://cloud-span.github.io/nerc-metagenomics05-binning/)| How to separate an assembly into MAGs and add functional annotation to these MAGs. |
| [Taxonomic Annotations](https://cloud-span.github.io/nerc-metagenomics06-taxonomic-anno/) | How to add taxonomic annotations onto contigs in an assembly. |

