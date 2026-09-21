# Annotation package: 15 ciliate species (shortintron project)

Per species: gene annotation (GFF3, gzipped) and protein FASTA (gzipped).
Assemblies are not included; download from the sources below.

| Species | Annotation source |
|---|---|
| Pseudocohnilembus persalinus | NCBI GCA_001447515.1 |
| Moneuplotes crassus | NCBI GCA_946863485.1 |
| Tetrahymena utriculariae | MetaEuk ab initio prediction (this study; reference: T. malaccensis proteins, TGD v1) |
| Tetrahymena malaccensis | TGD v1 (ciliate.org) |
| Tetrahymena thermophila | TGD v6 (ciliate.org) |
| Oxytricha trifallax | oxy.ciliate.org 2020 update 3 |
| Ichthyophthirius multifiliis | NCBI GCF_000220395.1 |
| Stylonychia lemnae | StyloDB (ciliate.org) |
| Paramecium octaurelia | NCBI GCA_905182995.1 |
| Paramecium pentaurelia | NCBI GCA_905183005.1 |
| Paramecium primaurelia | NCBI GCA_905182975.1 |
| Paramecium sonneborni | NCBI GCA_905182985.1 |
| Paramecium tetraurelia | NCBI GCA_000165425.1 (MAC assembly) |
| Blepharisma stoltei | BlepharismaDB (ciliate.org) |
| Stentor coeruleus | NCBI GCA_001970955.1 |

Notes:
- T. utriculariae has no published gene models; the GFF3 is MetaEuk prediction from this study (reference proteins: T. malaccensis, TGD v1).
- P. tetraurelia uses the macronuclear assembly GCA_000165425.1.
- Ciliate translation table 6 (UAA/UAG=Q) for all species except Blepharisma stoltei (table 15).
- Intron-length class per species: see genome_qc_and_intron_stats.csv in the parent folder.