# Computational tools for the Human Cell Atlas

A list of collaborative computational projects supported by CZI!

Here is a sample template you can copy and paste to add your project:

TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS
----- | ----------- | ------- 
[name](link to repo) | description of the project | Jeremy Freeman, PhD @ CZI Science
[another project name](link to repo) | description of the project | Joe Hand and Danielle Robinson, PhD @ CS&S


## Projects

### Bioconductor

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [SingleCellExperiment](https://github.com/drisso/SingleCellExperiment) | R container for storing data from single-cell experiments | Davide Risso @ Weill Cornell Medicine and Aaron Lun @ CRUK Camrbidge Institute |
| [beachmat](https://github.com/LTLA/beachmat) | Provides a consistent R/C++ class interface for a variety of commonly used matrix types, including sparse and HDF5-backed matrices.| Aaron Lun @ CRUK Camrbidge Institute |

### Cell Type

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
|[PicturedRocks](https://picturedrocks.github.io/)]| Implementation of feature selection algorithms | Anna Gilbert, Alexander Vargo, Umang Varma at University of Michigan|

### Cell State

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |

### Compression 
| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |

### Imaging
| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |

### Latent Spaces

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [Tybalt](https://github.com/greenelab/tybalt) | Variational Autoencoder for Gene Expression ([Paper](https://doi.org/10.1142/9789813235533_0008 "Extracting a biologically relevant latent space from cancer transcriptomes with variational autoencoders")) | Greg Way, Qiwen Hu, and Casey Greene [@Greenelab](https://github.com/greenelab) [@Penn](http://www.greenelab.com/) |
| [PHATE](https://github.com/KrishnaswamyLab/PHATE) |  Visualizing high-dimensional data ([Paper](https://doi.org/10.1101/120378 "Visualizing Transitions and Structure for High Dimensional Data Exploration")) | Kevin Moon, David van Dijk, and Smita Krishnaswamy [@KrishnaswamyLab](https://github.com/KrishnaswamyLab) [@Yale](http://www.krishnaswamylab.com/) |
| [CoGAPS](https://github.com/FertigLab/CoGAPS) | Bayesian Non-Negative Matrix Factorization | Elana Fertig, Genevieve Stein-O'Brien, and Tom Sherman [@FertigLab](https://github.com/FertigLab)|


### Manifold Alignment

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |

### Multiomics 

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [CellBench](https://github.com/LuyiTian/CellBench_data/blob/master/cellbench.md) | Benchmark data for scRNA-seq | Matt Ritchie, Luyi Tian [@LuyiTian](https://github.com/LuyiTian), WEHI|
[mixOmics](www.mixOmics.org) [paper](http://journals.plos.org/ploscompbiol/article/related?id=10.1371/journal.pcbi.1005752) | A suite of latent component based methods encompassing different data integration frameworks ([cross-platform](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1553-8), [multi-omics](https://www.biorxiv.org/content/early/2018/03/20/067611)) and feature selection| Kim-Anh Le Cao[@lecaolab](https://github.com/lecaolab), University of Melbourne|
[The Rosetta project: translating data across single-cell technologies to define human cell types](https://github.com/broadinstitute/2018_04_25_Rosetta) | Use parallel population-level mRNA & morphology data to uncover relationships between the two data types; test predictivity at a single-cell level | Anne Carpenter, Juan Caicedo [@CarpenterLab](http://www.broadinstitute.org/~anne/), Broad Institute

### Population Variation 

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [IA-SVA](https://github.com/UcarLab/IA-SVA) | Iteratively Adjusted Surrogate Variable Analyses ([Paper](https://www.biorxiv.org/content/early/2018/04/24/151217 "A statistical framework for the robust detection of hidden variation in single cell transcriptomes"))| Donghyung Lee [@LeeLab](https://github.com/dleelab/iasvaExamples), Anthony Cheng, Mohan Bolisetty, Duygu Ucar [@UcarLab](https://github.com/UcarLab/) [@JAX](http://ucarlab.org/) |


### Portals

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [ASAP](https://github.com/DeplanckeLab/ASAP) | Automated Single-cell Analysis Pipeline ([Web portal](https://asap.epfl.ch)) ([Paper](https://doi.org/10.1093/bioinformatics/btx337 "ASAP: a web-based platform for the analysis and interactive visualization of single-cell RNA-seq data")) | Vincent Gardeux, Fabrice David, and Bart Deplancke [@DeplanckeLab](https://github.com/DeplanckeLab) [@EPFL](http://deplanckelab.epfl.ch) |
| [Xena](http://xena.ucsc.edu) | Web-browser based integrative functional genomics data visualization ([Web site](https://singlecell.xenahubs.net)) | Brian Craft, Mary Goldman, Jing Zhu [@ucscXena](https://github.com/ucscXena) [@UCSCXena](https://twitter.com/UCSCXena)

### Scale

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
| [ADAM](https://github.com/bigdatagenomics/adam) | ADAM is a genomics analysis platform with specialized file formats built using Apache Avro, Apache Spark and Parquet. | Michael Heuer, Anthony Joseph, UC Berkeley; Ryan Williams, Uri Laserson, Icahn School of Medicine at Mount Sinai. |

### Trajectories

| TITLE | DESCRIPTION | PEOPLE & AFFILIATIONS |
| ----- | ----------- | --------------------- |
|[STREAM](https://github.com/pinellolab/stream)|STREAM is an interactive computational pipeline for reconstructing complex celluar developmental trajectories from sc-qPCR, scRNA-seq or scATAC-seq data (and soon scMethyl-Data!) [Paper](https://www.biorxiv.org/content/early/2018/04/18/302554.1). We also provide an interactive website to compute and visualize trajectories and a database of precomputed trajectories: [http://stream.pinellolab.org](http://stream.pinellolab.org)| H Chen, L Albergante, JY Hsu, CA Lareau, GL Bosco, J Guan, S Zhou, AN Gorban, DE Bauer, MJ Aryee, DM Langenau, A Zinovyev, JD Buenrostro, GC Yuan, L Pinello [@PinelloLab](http://pinellolab.org)|
|[traj-formats](https://github.com/Stuartlab-UCSC/traj-formats)| Traj-formats contains json-schema specifications for trajectory information. | Collaborative effort from the trajectory community. Maintained by the [@Stuart Lab at UCSC](https://sysbiowiki.soe.ucsc.edu/)|
