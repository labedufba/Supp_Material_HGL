# Supp_Material_HGL: Supplementary Material for Heteropia glomerosa (HGL) Genome

This repository contains supplementary data, annotations, alignments, and plots related to the genomic analysis of Heteropia.

## Repository Files and Descriptions

### Genomes and Assemblies
* `heteropia_glomerosa_hologenome.fasta`: Hologenome assembly sequence (FASTA format).
* `heteropia_glomerosa.genome.masked.fasta`: Masked genome assembly of *Heteropia glomerosa* (repeat masked).
* `Heteropia_rRNA_28S.fasta`: 28S ribosomal RNA sequences.

### Annotations and Functional Predictions
* `heteropia_glomerosa.genome.EVM.gff3`: EvidenceModeler structural gene annotations for *H. glomerosa* (GFF3).
* `heteropia_sp.helixer.gff3`: Helixer automated gene predictions (GFF3).
* `heteropia_sp.te_annotation.gff3`: Transposable elements (TE) annotation file (GFF3).
* `NCRNA_final.gff`: Final non-coding RNA (ncRNA) annotations.

### Functional Annotation Spreadsheets & Tables (Excel/TSV)
* `Heteropia_evm_withsimbionts.annotations.xlsx`: EVM functional annotations including symbiont data.
* `swissprot_annotation_withsimbiont.xlsx`: Swiss-Prot functional annotations with symbiont analysis.
* `heteropia_interproscan.xlsx`: InterProScan domain and functional motif annotations.
* `Ribosomal_and_mitochondrial-related_machineries.xlsx`: Curated components of ribosomal and mitochondrial machineries.
* `per_GO_BP_hmmer.tsv`: Gene Ontology (Biological Process) profiling based on HMMER.
* `blastp_mitos004.tsv`: BLASTP results against mitochondrial databases.

### Homology Searches (DIAMOND & HMMER)
* `diamond_* / hmmer_*`: Functional homology search outputs (Auto and Metazoa profiles) against EVM and Helixer gene sets.

### Plots and Statistics
* `genomescope_transformed_linear_plot.png`: GenomeScope transformed linear plot for genome size estimation and heterozygosity.

## Requirements & Tools
The analyses in this project were processed using tools such as:
* [BlobToolkit](https://github.com/blobtoolkit/blobtoolkit)
* Node.js
* Gene prediction and annotation pipelines (Helixer, EVM, DIAMOND, HMMER, InterProScan).
