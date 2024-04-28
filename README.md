# Peter Darley
I'm currently working at the [Mullins Retrovirology Lab](https://mullinslab.microbiol.washington.edu/) at the [University of Washington Department of Microbiology](https://microbiology.washington.edu/uw-microbiology-home) where I develop tools for the collection, distribution, and analysis of scientific data.  The projects I've worked on here are:

## Full Applications
Some of these are available at the [Mullins Lab GitHub page](https://github.com/MullinsLab)

### Phylobook
[Phylobook GitHub Repo](https://github.com/MullinsLab/phylobook)

Phylobook is a tool to display related sequences (necleotides or amino acids) using a phylogenitic tree, a mismatched plot (Highlighter) that displayes differences from a reference sequences, and a matched plot that shows similarities to consensus sequences for the lineages assigned by the user.  This is used to generate lineage information for each sequences.  In the Mullins Lab this information is being applied to the question of how many strains of HIV are people being exposed to on initial infection.

The Phylobook paper is pending publication in the journal [BioTechniques](https://www.biotechniques.com/)

Phylobook is fed data from the Phylobook_Pipeline, which is mostly written by my coleague, Wenjie Deng, but which I contributed a small amount of work toward. ([GitHub Repo](https://github.com/MullinsLab/phylobook_pipeline))

<img src="Phylobook.png" alt="Phylobook screen shot" width="300"/>

### Viroverse
Viroverse GitHub Repo is private until completion

### HiRIS - HIV-1 Reservoirs Integration Sites “high-rise”
HiRIS GitHub Repo is private until completion

HiRIS

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
