# Single cell RNA-Seq of transplanted human organoids into the degenerating rd1 mouse retina

10x Single-cell RNA sequencing (scRNA-seq) data from the study of transplanted human retinal organoids into the subretinal space of degenerating rd1 mouse retinas which is accessible on bioRxiv:

<img align="left" src="./image/sample.png" width="350"><img align="left" src="./image/celltype.png" width="350"/>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


### Sample Information
The following contains sample information for the scRNA-seq runs.

| Condition        | Replicate Number           | Sample Name  |
| ------------- |:-------------:|:-----:|
Cultured organoid | 1 |hgorg1
Cultured organoid | 2 |hgorg2
Transplant organoid | 1 |rd1_hgorg1
Transplant organoid | 2 |rd1_hgorg2
Transplant organoid | 3 |rd1_hgorg3

### Count Matrix
The cell by gene count matrix contains the gene counts for the merged dataset used in this study and is provided in .csv format and can be downloaded here:
[counts.csv](https://www.dropbox.com/)

### Meta Data 
The metadata file contains the assigned clusters, celltype annotations and UMAP coordinates that were used in the study.
The metadata is provided in .csv format and can be downloaded here:
[metadata.tsv](https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/csanti10_jh_edu/EWXXyDe-OWdMrWa8UVmFo2QBFrayir4lldRmHHzlJzwn2g?e=btcPYO)
|                          |orig.ident  |nCount_RNA |nFeature_RNA |percent.mt |Condition |Celltype   |Clusters |UMAP_1      |UMAP_2      |
|:-------------------------|:-----------|----------:|------------:|----------:|:---------|:----------|--------:|-----------:|-----------:|
|hgorg1_AAACCCAAGGTGGCTA-1 |hgorg1      |	11508     |	3742	      |5.604643105|	Cultured |Muller glia|	0      |-6.105595963|	5.110958343|
|hgorg1_AAACCCAGTACGAGCA-1 |hgorg1	    | 31242	    | 6046	      |5.282331512|	Cultured |Muller glia|	0	     |-5.782360452|	5.963640934|
|hgorg1_AAACGCTGTTTCGATG-1 |hgorg1	    | 10886	    | 3626	      |10.20707348|	Cultured |Muller glia|	0	     |-3.410245078|	5.206082111|
|hgorg1_AAAGAACTCAATCAGC-1 |hgorg1	    | 14062	    | 3857	      |7.043953703|	Cultured |Muller glia|	0	     |-3.868779796|	5.773703342|
|hgorg1_AAAGGATGTTTGAAAG-1 |hgorg1	    | 24932	    | 5078	      |3.31409794	| Cultured |Muller glia|	0	     |-5.3565463	| 6.888954406|


