# Peter Darley
I'm currently working at the [Mullins Retrovirology Lab](https://mullinslab.microbiol.washington.edu/) at the [University of Washington Department of Microbiology](https://microbiology.washington.edu/uw-microbiology-home) where I develop tools for the collection, distribution, and analysis of scientific data.  The projects I've worked on here are:

## Full Applications
Some of these are available at the [Mullins Lab GitHub page](https://github.com/MullinsLab)

### Phylobook
[Phylobook GitHub Repo](https://github.com/MullinsLab/phylobook)

Phylobook is a tool to display related sequences (nucleotides or amino acids) using a phylogenitic tree, a mismatched plot (Highlighter) that displayes differences from a reference sequences, and a matched plot that shows similarities to consensus sequences for the lineages assigned by the user.  This is used to generate lineage information for each sequences.  In the Mullins Lab this information is being applied to the question of how many strains of HIV are people being exposed to on initial infection.

The Phylobook paper is pending publication in the journal [BioTechniques](https://www.biotechniques.com/)

Phylobook is fed data from the Phylobook_Pipeline, which is mostly written by my coleague, Wenjie Deng, but which I contributed a small amount of work toward. ([GitHub Repo](https://github.com/MullinsLab/phylobook_pipeline))

<img src="Phylobook.png" alt="Phylobook screen shot" width="300"/>

### HiRIS - HIV-1 Reservoirs Integration Sites “high-rise”
HiRIS GitHub Repo is private until completion

I am the sole contributor to HiRIS, a tool to collect and display viral integration sights, specifically HIV integration sights.  Based on the [ISDB](https://mullinslab.microbiol.washington.edu/isdb/) implimentation of a previous [HiRIS tool](https://mullinslab.microbiol.washington.edu/hiris/), the project includes an entirely new PostgreSQL data base design, and all new code, with the goal of increasing the variety of sequence data collected, including the provirus sequence, adding data access rules, and allowing for importing data by the users.  

<img src="HiRIS.png" alt="HiRIS screen shot" width="300"/>

### Viroverse
Viroverse GitHub Repo is private until completion

Viroverse is a platform for the collection, storage, retrieval, and analysis of experimental data for laboratory workflows. Developed in-house for twelve years, it serves as the principal data store for HIV sequencing experiments conducted in the Mullins Lab. Viroverse currently houses tens of thousands of viral nucleotide sequences, together with comprehensive metadata about their creation including PCR protocols, gel images, subject clinical data, and more.

I am involved in a ground up rewrite in Python and Django where the goal is to make it more flexible and to give it better data management tools in an effort to eliminate manual changes to the database and improve workflow.

## Reusable Open Source Components

### Highlighter
[Highlighter GitHub Repo](https://github.com/MullinsLab/Highlighter)

Hilighter is a pure Python extension to [Biopython](https://github.com/biopython/biopython) to detect point mutations in the members of a sequence alignment, and to plot either matching or mismatched nucleotides or amino acids.  It's written with a focus on adjustable formatting.

This is a rewrite of the excelent web based [LANL Highlighter ](https://www.hiv.lanl.gov/content/sequence/HIGHLIGHT/highlighter_top.html) tool.

It is currently needing more documentation before it gets submitted to Biopython, so is monkey patching at the moment.  My hope is that it will be part of the standard Biopython at some point.

<img src="DEMO_highlighter.png" alt="Highlighter Demo" width="300"/>

### ML Import Wizard
[ML_Import_Wizard GitHub Repo](https://github.com/MullinsLab/ML_Import_Wizard)

### ML Export Wizard
[ML_Export_Wizard GitHub Repo](https://github.com/MullinsLab/ML_Export_Wizard)
