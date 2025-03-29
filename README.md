!!! ./ric.broccoli/kubacki.michal/SRF_SET/Multiome_SETBP1/Multiome_SETBP1 has been moved to the new location: ./ric.briccoli/ric.briccoli/Multiome_SETBP1 !!!

To do:

- analyse multiome data, stratyfied by P2 and Embryo development stages
- check gene expression in mulitome data (validate their derivation)

Genes to check:
Difference between mutant and control at the two different timpoints.

AMPAR auxiliary subunits:
- TARP γ-2
- TARP γ-8
- CNIH-2
- CNIH-3
- CKAMP44
- GSG1L

PV-enriched genes:
- cFos
- PGC-1𝛂
- Pvalb
- Cplx1
- Syt2
- Kcnc1
- Kcna1
- Bcan

Neural microcircuits:
- Bmp2
- Bdnf
- Id1
- Id3
- Smad1
- Smad5
- Samd6
- Smad7


## Balanced SET levels favor the correct enhancer repertoire during cell fate acquisition

[Balanced SET levels favor the correct enhancer repertoire during cell fate acquisition | Nature Communications](https://www.nature.com/articles/s41467-023-39043-x)


## GSE212252: Description and Specification:
[GSE212252](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212252)

### Data description
The `CRE_POSITIVE` samples are associated with **SETBP1 overexpression**:
1. CRE_POSITIVE samples: These represent the *experimental condition* where Cre recombinase is expressed, leading to the activation of the SETBP1 transgene. In this case, these samples have SETBP1 overexpression, modeling the Schinzel-Giedion Syndrome (SGS) condition.
2. CRE_NEGATIVE samples: These are the *control samples* where Cre recombinase is not expressed, so the SETBP1 transgene remains inactive. These samples represent the normal, non-SGS condition.
   
The datasets are divided into:
- Embryonic samples (NUCLEI_EMBRYO)
- Postnatal samples (NUCLEI_POST_NATAL)

Each of these is further divided into CRE_POSITIVE (SETBP1 overexpression) and CRE_NEGATIVE (control) conditions.


## GSE171266: Description and Specification:
[GSE171266](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE171266)

This study contains RNA sequencing data from human neural progenitor cells (NPCs) and cerebral organoids modeling Schinzel-Giedion syndrome (SGS). Key details include:

1. Sample types:

   - iPSC-derived NPCs
   - Cerebral organoids
2. Experimental conditions:

   - SETBP1 wildtype (D868D, I871I)
   - SETBP1 SGS mutations (D868N, I871T)
3. Sample details:

   - 9 NPC samples (3 per genotype: D868D, D868N, I871T)
   - 2 cerebral organoid samples (WT D868D vs Mut D868N)
4. Sequencing details:

   - NPCs: Bulk RNA-seq on Illumina HiSeq 3000
   - Organoids: Single-cell RNA-seq on Illumina NovaSeq 6000
5. Key analyses:

   - Differential gene expression between wildtype and SGS mutant cells
   - Functional enrichment analysis
   - Single-cell transcriptomics of cerebral organoids
6. Data processing:

   - Bulk RNA-seq: STAR aligner, DESeq2 for differential expression
   - scRNA-seq: Cell Ranger pipeline, Seurat for analysis
7. Genome build: hg38

This dataset allows for analysis of transcriptional changes in neural progenitors and developing cortical cells due to SGS-associated SETBP1 mutations. The combination of bulk and single-cell approaches provides insights into both overall expression changes and cell type-specific effects in SGS.
