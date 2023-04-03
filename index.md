---

---
[Cloud-SPAN](https://cloud-span.york.ac.uk) is a collaboration between the [Department of Biology](https://www.york.ac.uk/biology/) at the University of York and [The Software Sustainability Institute](https://www.software.ac.uk/) funded by the UKRI Innovation Scholars award. It aims to train researchers to effectively generate and analyse a range of 'omics data using Cloud computing resources.

This "Getting started with High Performance Computing: FAIR training for environmental scientists" course is additionally funded by a NERC Advanced Training: Short Courses award.

This hands-on, online course teaches data analysis for metagenomics projects. It is aimed at environmental scientists with little or no experience of using high performance computing (HPC) for data analysis. In the course we will cover:
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
> To get started, follow the directions in the Setup tab to get access to the required software and data for this workshop.
>
{: .prereq}

> ## Data
> This course uses data from a 2022 paper published in BMC Environmental Microbiome titled [In-depth characterization of denitrifier communities across different soil ecosystems in the tundra](https://environmentalmicrobiome.biomedcentral.com/articles/10.1186/s40793-022-00424-2). In this course we will compare data from two of the sites studied.
> 
> You can read more about the data used in the course [here](_extras\data.md).
{: .prereq}

# Course format

This workshop is designed to be run on pre-imaged Amazon Web Services (AWS) instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI). We will give you details as to how to access these instances after registration.

This course is available on both a 'taught' and 'self-study' basis. Instances will be available for use by registered participants from 11th - 17th April 2023. 

### For those registered for a taught course: 

The course will take place over two weeks and will combine live coding and teaching with offline work. We will guide you through the analysis each session but some steps may need to completed offline due to the amount of time they take to complete. There will also be drop-in sessions to offer support and troubleshooting help, and a Slack workspace for questions.

### For those registered for self-study:

Instances will be available for two weeks and you are free to work through the course content at your own pace. You may still find it useful to use the drop-in sessions and Slack workspace to troubleshoot any problems that arise.

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Files and Directories](https://cloud-span.github.io/nerc-metagenomics01-file-directories/) |Learn about files and directories, log onto a cloud instance and get a basic introduction to the shell.|
| [Using the Command Line](https://cloud-span.github.io/nerc-metagenomics02-command-line/)  |Learn more about using the shell to navigate directories, manipulate and search files and use basic loops to iterate commands.|
| [QC & Assembly](https://cloud-span.github.io/nerc-metagenomics03-qc-assembly/) | How to quality control and assemble a genome.|
| [Polishing](https://cloud-span.github.io/nerc-metagenomics04-polishing/) | How to use short reads to polish your metagenome assembly |
| [Binning & Functional Annotation](https://cloud-span.github.io/nerc-metagenomics05-binning/)| How to separate an assembly into MAGs and add functional annotation to these MAGs. |
| [Taxonomic Annotations](https://cloud-span.github.io/nerc-metagenomics06-taxonomic-anno/) | How to add taxonomic annotations onto contigs in an assembly. |

