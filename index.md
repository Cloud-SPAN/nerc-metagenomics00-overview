---
bioschemas:
  "@context": "https://schema.org"
  "@type": "LearningResource"
  "@id": "https://cloud-span.github.io/metagenomics00-overview/"
  "http://purl.org/dc/terms/conformsTo":
  - "@type": CreativeWork
    "@id": "https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE"
  about:
  - "@id": "http://edamontology.org/topic_3174"
  - "@id": "http://edamontology.org/topic_3372"
  - "@id": "http://edamontology.org/topic_0769"
  - "@id": "http://edamontology.org/topic_3365"
  abstract: "This course teaches data analysis for metagenomics projects. It covers how to (1) generate and QC a metagenome assembly, (2)' bin’ the assembly into metagenome assembled genomes (MAGs) (also known as bins), (2)identify the taxonomy of these MAGs, and (4) calculate diversity metrics and add functional annotation to identify the products of genes identified in the assembled MAGs."
  author: ["Emma Rand", "Sarah Forrester", "Annabel Cansdale", "Jorge Buenabad-Chavez", "Evelyn Greeves"]
  contributor: ["James Chong", "Emma Barnes", "University of York", "Software Sustainability Institute"]
  educationalLevel: "Intermediate"
  identifier: ""
  name: "Cloud-SPAN Genomics Course"
  url: "https://cloud-span.github.io/metagenomics00-overview"
  inLanguage: "en"
  keywords: "metagenomics, assembly, polishing, taxonomic annotation, binning, functional annotation, shell, command line tools, cloud computing, AWS, HPC, data analysis"
  license: CC-BY 4.0
  timeRequired: "PT12H"
  mentions: ["Git for Windows", "Cloud-SPAN Genomics course", "Data Carpentries Genomics workshop"]
---
[Cloud-SPAN](https://cloud-span.york.ac.uk) is a collaboration between the [Department of Biology](https://www.york.ac.uk/biology/) at the University of York and [The Software Sustainability Institute](https://www.software.ac.uk/) funded by the UKRI Innovation Scholars award. It aims to train researchers to effectively generate and analyse a range of 'omics data using Cloud computing resources.

This course teaches data analysis for metagenomics projects. It covers how to:
- generate and QC a metagenome assembly
- 'bin' the assembly into metagenome assembled genomes (MAGs) also known as bins
- identify the taxonomy of these MAGs.
- calculate diversity metrics and add functional annotation to identify the products of genes identified in the assembled MAGs.

> ## Prerequisites
This course assumes no prior experience with the tools covered in the workshop but learners are expected to have some familiarity with biological concepts, including the concept of microbiome. Participants should bring their own laptops and plan to participate actively.
To get started, follow the directions in the Setup tab to get access to the required software and data for this workshop.
>
{: .prereq}

> ## Data
> This course uses data from a mock metagenome community published from [Ultra-deep, long-read nanopore sequencing of mock microbial community standards](https://academic.oup.com/gigascience/article/8/5/giz043/5486468) which has long and short read sequencing data and has been used for benchmarking metagenome tools.
{: .prereq}

# Course format

This workshop is designed to be run on pre-imaged Amazon Web Services (AWS) instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI). CloudSPAN will give details as to how to access these images. Unlike our [genomics course](https://cloud-span.github.io/00genomics/) which is available as a self study option with a guide on [how to create your own instance](https://cloud-span.github.io/create-aws-instance-0-overview/), the resources required to run this course on your own instance are much greater and will not be available on a free tier basis. We will be running this course more than once and if you would like to wait until the next course is available to use our own AMIs, then please check our website for [course date updates](https://cloud-span.york.ac.uk/).

The course will take part over 4 weeks and will be done largely as a self study to take place at your own pace. Each week there will a recorded teaching session covering background required for the lesson. There will also be a drop-in session to offer support and troubleshooting help. The content that we will be covering in the teaching each week will follow the course overview, however support for other sections of the course will be offered as required at the drop-in sessions and over slack. 

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [QC & Assembly](https://cloud-span.github.io/metagenomics01-qc-assembly/) | How to quality control and assemble a genome.|
| [Polishing](https://cloud-span.github.io/metagenomics02-polishing/) | How to use short reads to polish your metagenome assembly |
| [Taxonomic Annotations](https://cloud-span.github.io/metagenomics03-taxonomic-anno/) | How to add taxonomic annotations onto contigs in an assembly. |
| [Binning & Functional annotation](https://cloud-span.github.io/metagenomics04-binning_funa/)| How to seperate an assembly into MAGs and add functional annotation to these MAGs. |
