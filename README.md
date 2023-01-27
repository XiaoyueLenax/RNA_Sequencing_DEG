# RNA_Sequencing_DEG
Differential expression analysis of toxoplasma infected mice

## Notice:
The file path contained in the codes may no longer be available due to rearrangements, but in such case, explaination will be given in a markdown statment, with the new file path given/what content has been processed in the step. If any questions regarding the file path, please contact xiaoyue.deng@students.unibe.ch . 

### Overview of steps:
1. General Preparation: Directories of the files & Workspace
2. Quality check: fastqc and multiqc [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/2_Quality_Check)
3. HISAT2 mapping to reference genome 
  3.1 HISAT [BASH script]()
4. FeatureCounts [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/4_FeatureCounts)
  4.1 Trimming file for DESeq2 [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/4.2_FeatureCounts_Trimming%20output)
5. DESeq2 quality check [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts)
6. Differential expression analysis [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts) 
7. Overrepresentation Analysis [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts)
Extra: result visualization & misc [Folder](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/tree/main/Images)
