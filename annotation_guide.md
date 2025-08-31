# 🧬 Single-Cell Cell Type Annotations for Human and Macaca fascicularis Embryos

> **Purpose**: This document provides a comprehensive annotation guide for the `reanno` cell types in human and macaque embryonic single-cell datasets, including their developmental stage distributions. It is intended to help researchers unfamiliar with these datasets understand the biological context of each annotated cell population.

---

## 1. Human Embryo Cell Type Annotations

The annotations provided here are based on an integration of six published single-cell transcriptomic datasets, covering human embryonic development from embryonic day (E) 6 to approximately post-conception week 3 (PCW3, E22, Carnegie stage (CS) 10). The integrated dataset was systematically reannotated using a multi-tiered approach. We defined 12 major developmental lineage labels (stored as 'lineage') and a more granular set of 49 cell type labels (stored as 'reanno'). Original cell type and subtype annotations from the source studies were stored as 'orig_anno' and 'orig_sub_anno', respectively. A preliminary harmonized annotation (harmo.anno) was created by classifying the original annotations before integration. The details of the final lineage and reanno labels in our reannotation system are explained in bellow.


### ✅ Lineage Descriptions 

| Annotation | Description | Including Cell Types |
|-----------|-------------|-------------|
| **TE/TrB** | Trophectoderm and trophoblast | TE, CTB_1, CTB_2, STB_1, STB_2, STB_3, EVT_1, EVT_2 |
| **epi** | Epiblast and its early derivative | Epiblast_1, Epiblast_2, Epiblast_3, Ectoderm |
| **Primitive.streak** | Cells originating from the primitive streak | Primitive.streak |
| **NMP** | Neuromesodermal progenitors, bipotent precursors for spinal cord and paraxial mesoderm | Neuromesodermal.progenitor |
| **Notochord** | The embryonic precursor to the vertebral column | Notochord |
| **PGC** | Primordial germ cells | PGC |
| **Exe.endo** | Hypoblast-derived extraembryonic endoderm cells | Hypoblast_1, Hypoblast_2, AVE, VE, YS.endoderm |
| **Amniotic_ecto** | Amniotic ectoderm cells | Amniontic.epi, Amniontic.ectoderm |
| **neural_ecto** | Neural ectoderm and its derivatives | Neural.crest, Neural.ectoderm.forebrain, Neural.ectoderm.hindbrain, Neural.ectoderm.midbrain, Spinal.cord |
| **Endoderm** | Definitive endoderm and its early derivative | DE, Gut |
| **meso_Exe.meso** | Mesoderm and extraembryonic mesoderm lineages | Paraxial.mesoderm, Emergent.mesoderm, Pre-somatic.mesoderm, Somite, Rostral.mesoderm, Lateral.plate.mesoderm_1, Lateral.plate.mesoderm_2, Lateral.plate.mesoderm_3, Cardiac.mesoderm, Amniotic.mesoderm, Exe.meso.progenitor, YS.mesoderm_1, YS.mesoderm_2 |
| **hemogenic** | Hemogenic populations, including endothelial, immune, and erythroid lineages, distinguished by *PECAM1*, *PTPRC*, and *HBZ*, respectively | Hemogenic.endothelial.progenitor, Endothelium, Erythroid, Primitive.megakaryocyte, Myeloid.progenitor |



### ✅ Cell Type Descriptions with Stage Distribution

| Annotation | Description |
|-----------|-------------|
| **TE** | Trophectoderm, collected from E6. | 
| **CTB_1** | A subtype of cytotrophoblast most abundant at the E8_IVC stage. |
| **CTB_2** | A subtype of cytotrophoblast enriched at the E9_IVC stage. |
| **STB_1** | A subtype of syncytiotrophoblast primarily observed at the E11_IVC stage. |
| **STB_2** | A subtype of syncytiotrophoblast enriched at the E9_IVC to E11_IVC stages. | 
| **STB_3** | A subtype of syncytiotrophoblast most abundant at the E11_IVC to E14_IVC stages. | 
| **EVT_1** | A subtype of extravillous trophoblast upregulating CTB markers *TEAD4* and *ITGA6*, detected across E9_IVC to CS10. | 
| **EVT_2** | A subtype of extravillous trophoblast upregulating EVT markers *HLA-G*, *CSH1*, and *ERBB2*, highly abundant from E13_IVC to E14_IVC. |
| **Epiblast_1** | A subtype of epiblast primarily observed at the E6_IV and E7_IVC stages. | 
| **Epiblast_2** | A subtype of epiblast enriched at the E8_IVC to E12_IVC stages. | 
| **Epiblast_3** | A subtype of epiblast enriched at the E13_IVC, E14_IVC and CS7 stage. | 
| **Ectoderm** | Epiblast derivative, present at the CS7 stage. |
| **NMP** | Neural-mesodermal progenitors, distinguished by *TBXT⁺SOX2⁺* co-expression, observed at CS7–CS10. | 
| **Primitive.streak** | The primitive streak, marked by *TBXT* expression, mainly detected between E11_IVC to CS7. | 
| **PGC** | Primordial germ cells specifically expressing *NANOS3*, present at CS7–CS10. | 
| **DE** | Definitive endoderm predominantly located at the CS7 stage. |
| **Gut** | Gut tissue primarily observed at the CS10 stage. | 
| **Notochord** | Notochord present at the CS7 and CS10 stages. | 
| **Paraxial.mesoderm** | Paraxial mesoderm observed at the CS7 and CS10 stages. | 
| **Emergent.mesoderm** | Emergent mesoderm primarily observed at the CS7 stage, compared to other mesodermal populations, specifically expresses *OTX2*, *MESP2*, and *LEFTY2*. |
| **Pre-somatic.mesoderm** | Pre-somatic mesoderm observed at CS7 to CS10 stage. |
| **Somite** | Somites observed in CS9 and CS10 stage. |
| **Rostral.mesoderm** | Originally named myocyte progenitor, enriched at the CS10 stage. |
| **Lateral.plate.mesoderm_1** | A subpopulation of Lateral plate mesoderm, differentiated by expressing *CDX2*, *WNT5A*, *WNT5B*, and *OSR1*; enriched at the CS10 stage. | 
| **Lateral.plate.mesoderm_2** | A subpopulation of Lateral plate mesoderm, located on both sides of the embryonic axis, detected from CS7 to CS10. | 
| **Lateral.plate.mesoderm_3** | A subpopulation of Lateral plate mesoderm, upregulated expression of *COL3A1*, potentially a second source of extra-embryonic mesodermal progenitors, primarily observed at CS10. |
| **Cardiac.mesoderm** | Cardiac mesoderm enriched at the CS10 stage. |
| **Amniotic.mesoderm** | Amniotic mesoderm predominantly located at the CS7 to CS10 stage. | 
| **Exe.meso.progenitor** | Extraembryonic mesoderm progenitor observed at the E11_IVC to CS7 stage. | 
| **YS.mesoderm_1** | A subtype of yolk sac mesoderm broadly localized in the yolk sac, present across multiple stages. |
| **YS.mesoderm_2** | A subtype of yolk sac mesoderm detected in the distal region. |
| **Amniotic.ectoderm** | Amniotic ectoderm primarily observed at the CS7 to CS10 stage. |
| **Amniotic.epi** | Amniotic epiblast cells, newly differentiated from epiblast and still showing expression of *POU5F1*, peaking at E12_IVC to E14_IVC stages. |
| **Neural.crest** | Neural crest enriched at the CS10 stage. |
| **Neural.ectoderm.forebrain** | A subpopulation of neural ectoderm, highly expressing forebrain markers such as *SIX3*, *RAX*, *LHX5*, *OTX2*, *LHX2*, *FEZF1*, and *EMX2*; primarily observed at the CS10 stage. |
| **Neural.ectoderm.hindbrain** | A subpopulation of neural ectoderm, highly expressing hindbrain markers such as *EGR2*, *MAFB*, *HOXA2*, and *CRABP1*; enriched at the CS10 stage. |
| **Neural.ectoderm.midbrain** | A subpopulation of neural ectoderm, highly expressing midbrain markers such as *EN1*; observed at CS10. |
| **Spinal.cord** | The caudal part of the neural tube that develops into the spinal cord, primarily observed at CS9 and CS10. | 
| **Hemogenic.endothelial.progenitor** | Hemogenic endothelial progenitors, most abundant at CS7–CS10. |
| **Endothelium** | Endothelium upregulating the endothelial marker *KDR*, enriched at CS7–CS10. |
| **Erythroid** | Erythroid lineage upregulating markers such as *HBZ* and *HBE1*, primarily observed at CS7–CS10. |
| **Primitive.megakaryocyte** | Primitive megakaryocytes, present at CS7–CS10. |
| **Myeloid.progenitor** | Myeloid progenitor upregulating the marker *LYVE1*, enriched at CS7–CS10. | 
| **Hypoblast_1** | A subpopulation of Hypoblast, largely composed of cells from E6–E10_IVC. |
| **Hypoblast_2** | A subpopulation of Hypoblast, largely composed of cells from E9_IVC–E11_IVC. | 
| **AVE** | Anterior visceral endoderm, observed from E9_IVC to E14_IVC stages. | 
| **VE** | Visceral endoderm, observed from E10_IVC to CS7 stages. |
| **YS.endoderm** | Yolk sac endoderm, enriched at CS7. |
---

## 2. Macaca fascicularis Embryo Cell Type Annotations

The annotations provided here integrated seven published single-cell transcriptomic datasets covering cynomolgus monkey development from embryonic day (E) 6 to Carnegie stage (CS) 11 (approximately E24). A total of 55 cell type annotations were integrated from the original cell type and subtype annotations reported in multiple previously published studies, and are represented as `"reanno"` in the single-cell dataset. For reference to the original annotations from individual studies, please refer to the columns `"orig_anno"` and `"orig_sub_anno"` in the single-cell data. The dataset encompasses 28 distinct developmental stages across in vivo and in vitro conditions.


### ✅ Monkey Lineage Descriptions 

| Annotation | Description | Including Cell Types |
|-----------|-------------|-------------|
| **TE/TrB** | Trophectoderm and trophoblast | TE, CTB_1, CTB_2, CTB_3, CTB_4, STB_1, STB_2, EVT_1, EVT_2 |
| **epi** | Epiblast and its early derivative | Epiblast_1, Epiblast_2, Ectoderm_1, Ectoderm_2, Ectoderm_3, Ectoderm_4 |
| **Primitive.streak** | Cells originating from the primitive streak | Primitive.streak |
| **NMP** | Neuromesodermal progenitors, bipotent precursors for spinal cord and paraxial mesoderm | Neuromesodermal.progenitor |
| **Notochord** | The embryonic precursor to the vertebral column | Notochord_1, Notochord_2 |
| **PGC** | Primordial germ cells | PGC |
| **Exe.endo** | Hypoblast-derived extraembryonic endoderm cells | Hypoblast, AVE, VE_YE, YS.endoderm_1, YS.endoderm_2 |
| **Amniotic_ecto** | Amniotic ectoderm cells | Amniotic.epi, Amniontic.ectoderm_1, Amniontic.ectoderm_2 |
| **neural_ecto** | Neural ectoderm and its derivatives | Neural.crest, Neural.ectoderm.fore_midbrain, Spinal.cord |
| **Endoderm** | Definitive endoderm and its early derivatives | DE, Gut_1, Gut_2 |
| **meso_Exe.meso** | Mesoderm and extraembryonic mesoderm lineages | Paraxial.mesoderm, Emergent.mesoderm, Pre-somatic.mesoderm, Somite, Rostral.mesoderm, Lateral.plate.mesoderm_1, Lateral.plate.mesoderm_2, Cardiac.mesoderm_1, Cardiac.mesoderm_2, Allantois, Connecting.stalk, Amniotic.mesoderm, Exe.meso.progenitor_1, Exe.meso.progenitor_2, Pre-YS.mesoderm, YS.mesoderm |
| **hemogenic** | Hemogenic populations, including endothelial, immune, and erythroid lineages, distinguished by *PECAM1*, *PTPRC*, and *HBZ*, respectively | Hemogenic.endothelial.progenitor, Endothelium, Erythroid, Primitive.megakaryocyte, Myeloid.progenitor |


### ✅ Cell Type Descriptions with Stage Distribution

| Annotation | Description |
|-----------|-------------|
| **TE** | Trophectoderm, observed largely from E6-E7. | 
| **CTB_1** | A subtype of cytotrophoblast observed at the E7-E12_IVC stage, peaking at E10_IVC. |
| **CTB_2** | A subtype of cytotrophoblast primarily observed at the E12_IVC to E20_IVC stages. |
| **CTB_3** | A subtype of cytotrophoblast most abundant at the E20_IVC to E25_IVC stages. | 
| **CTB_4** | A subtype of cytotrophoblast composed of cells from the E25_IVC stage. |
| **STB_1** | A subtype of syncytiotrophoblast, enriched at the E12_IVC to E14_IVC stage. |
| **STB_2** | A subtype of syncytiotrophoblast most abundant at the E18_IVC to E25_IVC stage. | 
| **EVT_1** | A subtype of extravillous trophoblast enriched at the E12_IVC to E14_IVC and CS8 stages. | 
| **EVT_2** | A subtype of extravillous trophoblast mainly present at the E14_IVC to E25_IVC stage. |
| **Epiblast_1** | A subtype of epiblast present between E7 to E14_IVC, enriched at the E10_IVC stage. | 
| **Epiblast_2** | A subtype of epiblast primarily observed at the E14_IVC and CS8 stages. | 
| **Ectoderm_1** | A subtype of ectoderm enriched at the CS8 stage. | 
| **Ectoderm_2** | A subtype of ectoderm primarily observed at the CS9 stage. | 
| **Ectoderm_3** | A subtype of ectoderm most abundant at the CS11 stage. | 
| **Ectoderm_4** | A subtype of ectoderm enriched at the CS11 stage. |
| **Neural.crest** | Neural crest primarily observed at the CS11 stage. | 
| **Neural.ectoderm.fore_midbrain** | Neural ectoderm primarily located at the CS11 stage to form the forebrain and midbrain. | 
| **Spinal.cord** | Spinal cord primarily observed at the CS11 stage. | 
| **Primitive.streak** | The primitive streak widely distributed at E10_IVC, CS8, and CS9 stages. | 
| **NMP** | Neuromesodermal progenitors primarily located at the CS9 to CS11 stages. | 
| **Paraxial.mesoderm** | Paraxial mesoderm observed mainly at E14_IVC and CS8 to CS9 stages. | 
| **Emergent.mesoderm** | Emergent mesoderm primarily observed at the CS8 and CS9 stages. | 
| **Pre-somatic.mesoderm** | Pre-somatic mesoderm enriched at the CS11 stage. |
| **Somite** | Somites most abundant at the CS11 stage. | 
| **Rostral.mesoderm** | Rostral mesoderm enriched at the CS11 stage. | 
| **Lateral.plate.mesoderm_1** | A sub-population of Lateral plate mesoderm, likely located at the E18_IVC to E25_IVC and CS8, CS9 stages. | 
| **Lateral.plate.mesoderm_2** | A sub-population of Lateral plate mesoderm, predominantly located at the CS11 stage. | 
| **Cardiac.mesoderm_1** | Cardiac mesoderm_1, forming the anterior (top) end of the heart tube, enriched at the CS11 stage. | 
| **Cardiac.mesoderm_2** | Cardiac mesoderm_2, located beneath the Cardiac.mesoderm_1, observed at CS11. |
| **Allantois** | Allantois, present from E12 to E25_IVC, and CS8 to CS11. | 
| **Connecting.stalk** | Connecting stalk enriched at the E18_IVC to E25_IVC and CS8 stage. | 
| **Amniotic.mesoderm** | Amniotic mesoderm, mainly present from E16_IVC to E25_IVC, and CS8 to CS11. | 
| **Exe.meso.progenitor_1** | Extraembryonic mesoderm progenitor_1 mainly containing cells from E18_IVC to E21_IVC stage. | 
| **Exe.meso.progenitor_2** | Extraembryonic mesoderm progenitor_2 enriched at the E19_IVC to E25_IVC stages. | 
| **Pre-YS.mesoderm** | Pre-yolk sac mesoderm, containing cells mainly from E18_IVC to E25_IVC, and CS8 to CS11. | 
| **YS.mesoderm** | Yolk sac mesoderm primarily observed at the CS11 stage. | 
| **Notochord_1** | A subtype of notochord enriched at the CS8-CS9 stage. |
| **Notochord_2** | A subtype of notochord primarily observed at the CS11 stage. | 
| **PGC** | Primordial germ cells, containing cells from E14_IVC to E25_IVC, and CS8 to CS11 stage. | 
| **Amniotic.epi** | Amniotic epiblast, mainly containing cells from E12_IVC to E25_IVC, and CS8, CS9 stages. |
| **Amniontic.ectoderm_1** | A sub-population of the amniotic ectoderm, Amniontic.ectoderm_1 is more ventrally located. | 
| **Amniontic.ectoderm_2** | A sub-population of the amniotic ectoderm, Amniontic.ectoderm_2 is more dorsally located. |
| **Hypoblast** | Hypoblast, mainly containing cells from E7 to E12_IVC stages. |
| **AVE** | Anterior visceral endoderm, observed from E10_IVC to E25_IVC, and CS8 stage. |
| **VE_YE** | Visceral and yolk sac endoderm, observed from E12_IVC to E25_IVC, and CS8 stage. | 
| **YS.endoderm_1** | Yolk sac endoderm_1 containing cells mainly from CS8-CS11, and E18_IVC to E25_IVC. | 
| **YS.endoderm_2** | Yolk sac endoderm_2, containing cells predominantly from CS11. | 
| **DE** | Definitive endoderm more abundant at the CS8, CS9 and E18_IVC to E24_IVC stages. |
| **Gut_1** | A subtype of gut, detected mainly from CS9 to CS11 and E19_IVC to E25_IVC stage. |
| **Gut_2** | A subtype of gut primarily observed at the CS11 stage. | 
| **Hemogenic.endothelial.progenitor** | Hemogenic endothelial progenitors enriched at the CS8 to CS11, and E23_IVC to E25_IVC stages. |
| **Endothelium** | Endothelium upregulating the endothelial marker *KDR*, observed across E13_IVC to E25_IVC and CS8–CS11. |
| **Erythroid** | Erythroid lineage upregulating markers such as *HBZ* and *HBE1*, enriched at CS8–CS11. |
| **Primitive.megakaryocyte** | Primitive megakaryocytes, mainly detected from CS8 to CS11 stage. |
| **Myeloid.progenitor** | Myeloid progenitors, mainly detected from CS8 to CS11, and E24_IVC to E25_IVC stage. |

---

## 3. Abbreviations

| Abbreviation | Full Term |
|-------------|-----------|
| **PCW** | Post-conception week |
| **E** | Embryonic day |
| **IVC** | In Vitro Culture |
| **CS** | Carnegie stage |