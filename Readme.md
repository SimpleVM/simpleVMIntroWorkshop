# SimpleVM Workshop

This workshop demonstrates a typical workflow of a SimpleVM user.
In this workshop your goal will be to identify pathogenic bacteria
that were classified as "greatest threat to human health" by the 
World Health Organisation (WHO) in 2017: https://www.who.int/news/item/27-02-2017-who-publishes-list-of-bacteria-for-which-new-antibiotics-are-urgently-needed

You will search for those microbes
in publicly available metagenomic datasets that are stored in the 
Sequence Read Archive ([SRA](https://www.ncbi.nlm.nih.gov/sra)). 
In metagenomics, microbial genetic material 
is extracted from environmental samples like human gut, soil, 
freshwater or biogas plants in order to investigate the functions and
interactions of the microbial community.

In order to find those microbes, you will have to interact with 
the de.NBI Cloud via SimpleVM. This workshop is divided into five
parts.

### Section 1: Big things start small  

In the first part you will learn the basic concept of virtual machines
and how to configure them.

**[Go to the first section](part1.md)**

### Section 2: Verify your VM properties and tools

In the second section you will test whether SimpleVM correctly
provisioned your VM with all your tools installed on it.

**[Go to the second section](part2.md)**

### Section 3: Access S3 and scale up your analysis vertically 

In the third section you will learn about object storage and the 
Sequence Read Archive. Further, you will run your analysis pipeline.

**[Go to the third section](part3.md)**

### Section 4: Inspect your generated data via a research environment

In the fourth section you will start a virtual machine with a RStudio research
environment installed.

**[Go to the fourth section](part4.md)**

### Section 5: Scale up your analysis horizontally to further analyze the detected Microbiomes

In this part you will use a SimpleVM Cluster to distribute your analysis 
on multiple machines instead of just one. You will use the Metagenomics-Toolkit to analyze the detected Microbiomes.

**[Go to the fifth section (Part 1)](part51.md)**

**[Go to the fifth section (Part 2)](part52.md)**
