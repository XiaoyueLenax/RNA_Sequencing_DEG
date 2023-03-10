# RNA_Sequencing_DEG


Differential expression analysis of toxoplasma infected mice

## Notice:

In some cases the file path used in the script may be in our personal IBU space or no long availiable, but explaination will be given in a markdown statment, with the new file path given/what content has been processed in the step. If any questions regarding the file path, please contact xiaoyue.deng@students.unibe.ch . 

### Overview of steps:

1. General Preparation: Directories of the files & Workspace
2. Quality check: fastqc and multiqc [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/2_Quality_Check)
3. HISAT2 mapping to reference genome 
  - HISAT [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/3_Mapping_HISAT2)
  - Convert sam files [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/3_Mapping_Sam_to_Bam)
  - Sort bam files [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/3_Mapping_Sorting%20Bam%20Files)
  - Index bam files [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/3_Mapping_Indexing)
4. FeatureCounts [BASH script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/4_FeatureCounts)
  - Trimming file for DESeq2 [BASH command line](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/4.2_FeatureCounts_Trimming%20output)
5. DESeq2 quality check [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts)
6. Differential expression analysis [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts) 
7. Overrepresentation Analysis [R script](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/blob/main/5-7_R%20scripts) </p>
8. Extra: result visualization & misc [Folder](https://github.com/XiaoyueLenax/RNA_Sequencing_DEG/tree/main/Images)
