# Ranunculus-genomics

## The genomic annotation data for _Ranunculus cassubicifolius_

The genome assembly and the protein-coding genes annotation is submitted at the National Center for Biotechnology Information (NCBI) database under SAMN44350262 in the Bioproject PRJNA831351.

## In this repository, we released the non-coding genes and repeats annotation files

- `Ranunculus_cassubicifolius.EDTA.TEanno.gff3.tar.gz`: the _Ranunculus cassubicifolius_ transposable elements (TE) annotation in gff3 format
- `Ranunculus_cassubicifolius.tRNA.gff3.tar.gz`: the _Ranunculus cassubicifolius_ tRNA annotation in gff3 format
- `Ranunculus_cassubicifolius.rRNA.gff.tar.gz`: the _Ranunculus cassubicifolius_ other short non-coding RNA in gff3 format


## Summary of repeat content identified in the Ranunculus genome using [EDTA](https://github.com/oushujun/EDTA) 

|                      | Total sequences| Total length     |    |
|----------------------|----------|--------------|-----------|
|                      | 320    | 2,690,854,146bp |    |
|----------------------|----------|--------------|-----------|
| Class                | Count    | bpMasked     | %masked   |
|----------------------|----------|--------------|-----------|
| LINE  
|   L1                | 31842    | 21,678,526     | 0.81%     |
| LTR                
|   Copia             | 147394   | 80,810,425     | 3.00%     |
|   Gypsy             | 1105626  | 654,391,560    | 24.32%    |
|   unknown           | 2075881  | 1,353,935,235   | 50.32%    |
| SINE            
|   tRNA              | 309      | 114,573       | 0.00%     |
|   unknown           | 347      | 444,295       | 0.02%     |
| TIR                      
|   CACTA             | 85851    | 32,242,719     | 1.20%     |
|   Mutator           | 134007   | 38,209,632     | 1.42%     |
|   PIF_Harbinger     | 86910    | 30,275,684     | 1.13%     |
|   Tc1_Mariner       | 32184    | 12,038,336     | 0.45%     |
|   hAT               | 133119   | 40,436,252     | 1.50%     |
| nonTIR             
|   helitron          | 123174   | 38,735,549     | 1.44%     |
| rDNA                | --       | --           | --        |
|   45S               | 191      | 42,204        | 0.00%     |
| repeat_fragment     | 44541    | 11822,897     | 0.44%     |
| satellite_DNA       | 186      | 83887        | 0.00%     |
|----------------------|----------|--------------|-----------|
| total interspersed  | 4001562  | 2,315,261,774   | 86.04%    |
|----------------------|----------|--------------|-----------|
| Total               | 4001562  | 2,315,261,774   | 86.04%    |




## Summary of tRNAs identified in the Ranunculus genome using [tRNA-Scan-SE](https://github.com/UCSC-LoweLab/tRNAscan-SE)

| Isotype   |       |   |       |       |       |       |       |       |       |       |       |       |       |
|:----------|:------|:-------------------|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|
| Ala:      | 32    | AGC:               | 11.0  | GCG:  |       | CGC:  | 3.0   | TGC:  | 18.0  |       |       |       |       |
| Gly:      | 49    | ACC:               | 2.0   | GCC:  | 28.0  | CCC:  | 10.0  | TCC:  | 9.0   |       |       |       |       |
| Pro:      | 41    | AGG:               | 15.0  | GGG:  | 2.0   | CGG:  |       | TGG:  | 24.0  |       |       |       |       |
| Thr:      | 45    | AGT:               | 16.0  | GGT:  | 6.0   | CGT:  | 3.0   | TGT:  | 20.0  |       |       |       |       |
| Val:      | 55    | AAC:               | 5.0   | GAC:  | 26.0  | CAC:  | 7.0   | TAC:  | 17.0  |       |       |       |       |
| Ser:      | 82    | AGA:               | 17.0  | GGA:  | 26.0  | CGA:  | 6.0   | TGA:  | 15.0  | ACT:  | 1.0   | GCT:  | 17.0  |
| Arg:      | 68    | ACG:               | 35.0  | GCG:  |       | CCG:  | 3.0   | TCG:  | 3.0   | CCT:  | 5.0   | TCT:  | 22.0  |
| Leu:      | 61    | AAG:               | 5.0   | GAG:  |       | CAG:  | 4.0   | TAG:  | 17.0  | CAA:  | 27.0  | TAA:  | 8.0   |
| Phe:      | 21    | AAA:               |       | GAA:  | 21.0  |       |       |       |       |       |       |       |       |
| Asn:      | 78    | ATT:               | 29.0  | GTT:  | 49.0  |       |       |       |       |       |       |       |       |
| Lys:      | 41    | CTT:               | 10.0  | TTT:  | 31.0  |       |       |       |       |       |       |       |       |
| Asp:      | 69    | ATC:               | 4.0   | GTC:  | 65.0  |       |       |       |       |       |       |       |       |
| Glu:      | 39    | CTC:               | 9.0   | TTC:  | 30.0  |       |       |       |       |       |       |       |       |
| His:      | 29    | ATG:               | 6.0   | GTG:  | 23.0  |       |       |       |       |       |       |       |       |
| Gln:      | 35    | CTG:               | 8.0   | TTG:  | 27.0  |       |       |       |       |       |       |       |       |
| Ile:      | 22    | AAT:               | 14.0  | GAT:  |       | CAT:  |       | TAT:  | 8.0   |       |       |       |       |
| Met/iMet: | 103   | CAT:               | 103.0 |       |       |       |       |       |       |       |       |       |       |
| Tyr:      | 56    | ATA:               | 19.0  | GTA:  | 37.0  |       |       |       |       |       |       |       |       |
| Supres:   | 5     | CTA:               |       | TTA:  | 4.0   | TCA:  | 1.0   |       |       |       |       |       |       |
| Cys:      | 32    | ACA:               | 3.0   | GCA:  | 29.0  |       |       |       |       |       |       |       |       |
| Trp:      | 21    | CCA:               | 21.0  |       |       |       |       |       |       |       |       |       |       |
| TOTAL     | 984    |              |   |       |       |       |       |       |       |       |       |       |       |


## Summary of short ncRNAs identified by [Infernal](http://eddylab.org/infernal/) cmscan by searching against [Rfam](https://rfam.org/) covariance models

| ncRNA type                                   | Number |
|---------------------------------------------|--------|
| _**Housekeeping ncRNAs**_                     |        |
| tRNA                                        | 984    |
| SSU rRNA                                    | 1154   |
| LSU rRNA                                    | 1204   |
| 5s rRNA                                     | 3013   |
| 5.8s rRNA                                   | 1077   |
| Spliceosomal RNA (snRNA)                    | 99     |
| _**Short regulatory RNAs**_                   |        |
| Plant signal recognition partition RNA      | 6      |

## Citations

If you want to use the data in your research, then please cite: 
