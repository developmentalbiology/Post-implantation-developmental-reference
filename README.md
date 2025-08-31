# Post-implantation-developmental-reference

This repository serves as a central portal for accessing downloadable reference atlases for post-implantation developmental data. It provides links to three key datasets: the **Human Reference**, **Monkey Reference**, and **Cross-species Reference**.

## Datasets Available

### 1. Human Reference
The **Human Reference** dataset is constructed from six published single-cell transcriptomic datasets, covering human post-implantation development from embryonic day (E) 6 to post-conception week 3 (PCW3, CS10). This reference enables the annotation of cell types in human single-cell and spatial transcriptomic datasets.

| Study                     | Data Accession Number | Species             | Embryo Type       | Stage                | Platform        | Raw Data Type | Number of Cells After QC |
|---------------------------|-----------------------|---------------------|-------------------|----------------------|-----------------|---------------|--------------------------|
| Zhou et al., 2019         | GSE109555            | Human              | ex vivo           | E6-E14              | STRT-seq/Smart-seq2 | fastq file    | 4,244                   |
| Xiang et al., 2020        | GSE136447            | Human              | ex vivo           | E6-E14              | Smart-seq2      | fastq file    | 521                     |
| Molè et al., 2021         | E-MTAB-8060          | Human              | ex vivo           | E9 and E11          | 10x-Genomics    | fastq file    | 5,229                   |
| Ai et al., 2023           | PRJCA017779          | Human              | ex vivo           | E10-E14             | 10x-Genomics    | fastq file    | 8,675                    |
| Tyser et al., 2021        | E-MTAB-9388          | Human              | in vivo           | CS7 (E16-E19)       | Smart-seq2      | fastq file    | 1,189                   |
| Yuan et al., 2025         | HRA010231            | Human              | in vivo           | CS9                 | 10x-Genomics    | fastq file    | 162                   |
| Zeng et al., 2023         | GSE155121            | Human              | in vivo           | PCW3 (CS10, E22)    | 10x-Genomics    | fastq file    | 13,774                 |

### 2. Monkey Reference
The **Monkey Reference** dataset is created from seven public datasets, representing cynomolgus monkey post-implantation development from E6 to E25. This reference facilitates the automated annotation of cell types in non-human primate datasets.

| Study                     | Data Accession Number | Species             | Embryo Type       | Stage                | Platform        | Raw Data Type | Number of Cells After QC |
|---------------------------|-----------------------|---------------------|-------------------|----------------------|-----------------|---------------|--------------------------|
| T. Nakamura et al., 2016  | GSE74767             | Cynomolgus monkeys | in vivo           | E6-E17              | SC3-seq         | count matrix  | 387                      |
| H. Ma et al., 2019        | GSE130114            | Cynomolgus monkeys | ex vivo           | E11-17              | Smart-seq2      | count matrix  | 1,422                   |
| Y. Niu et al., 2019       | PRJNA512422          | Cynomolgus monkeys | ex vivo           | E9-E20              | Smart-seq2      | count matrix  | 599                     |
| R. Yang et al., 2021      | GSE148683            | Cynomolgus monkeys | ex vivo           | E10, E12, E14       | 10x-Genomics    | fastq file    | 15,328                  |
| J. Zhai et al., 2022      | GSE193007            | Cynomolgus monkeys | in vivo           | CS8, CS9, CS11      | 10x-Genomics    | fastq file    | 61,789                  |
| J. Zhai et al., 2023      | GSE218525            | Cynomolgus monkeys | ex vivo           | E16-E25             | scChaRM-seq RNA | count matrix  | 340                     |
| Y. Gong et al., 2023      | GSE207534            | Cynomolgus monkeys | ex vivo           | E18-E25             | 10x-Genomics    | fastq file    | 62,708                 |

### 3. Cross-species Reference
The **Cross-species Reference** integrates the human and monkey reference atlases. This combined resource enables comparative studies of primate development and supports cross-species cell type annotation, allowing researchers to explore the conservation and divergence of cell lineage specification between humans and monkeys.

## Data Availability
All three reference cell atlases are publicly available for download from the National Genomics Data Center (NGDC) under the accession number **PRJCA045416** or **OMIX011658** ([https://ngdc.cncb.ac.cn/omix/release/OMIX011658](https://ngdc.cncb.ac.cn/omix/release/OMIX011658)).

## Annotation Guide
The complete annotation guide, including detailed descriptions of cell types and lineages, is available in this repository.

## License
This repository is licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0). Please see the LICENSE file for more details.

---
For any questions or issues related to downloading or using the references, please open an issue in this repository or contact the maintainer.
