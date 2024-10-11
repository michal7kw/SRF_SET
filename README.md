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
