## Page 1 Title

Cancer Variant Predictor  
A Bioinformatics and Machine Learning Research Project

Presented by: Xiaonuan Fu  
Mentor: Prof. Zhang, Tsinghua University  
Date: July 2025

## Page 2 Motivation

- Curious about how gene mutations contribute to cancer development  
- Interested in using computational tools to explore biological questions  
- Hope to combine biology, programming, and data analysis in one project 
- 更好的掌握和结合AP生物、AP统计学、AP计算机的学习知识。

## Page 3 Research Goals

1. Use GATK and nextflow to process cancer genome data (BAM → VCF)  
2. Analyze mutation patterns from datasets (TCGA)  
3. Apply statistical and machine learning tools to identify predictive mutation features  
4. Build a simple model to predict potential disease-associated mutations  
5. Learn from lab members and gain hands-on experience
6. 项目记录在Git上，并完成一篇研究型论文


## Page 4 Tools and technologies

- GATK (Genome Analysis Toolkit)
- nextflow(batch job process tool)  
- TCGA Data (from GDC Portal or 清华 lab)  
- Python (pandas, matplotlib, scikit-learn)  
- Google Colab  （online python editor）
- GitHub （code and document control management）
- Docker （GATK and nextflow container management）

## Page 5 Proposed Workflow

1. Acquire BAM files from sources (e.g., TCGA)  
2. Use GATK to call variants → generate VCF files  
3. Annotate and filter variants  
4. Extract mutation features  
5. Train a machine learning classifier  
6. Evaluate and visualize results

## Page 6 Data 

- TCGA-COAD or 清华lab data
- 150–200 patient samples  
- Paired BAM files, clinical metadata, and annotations  
- Focus on somatic mutation types (e.g., SNPs, Indels)  


## Page 7 Project Plan

1. month 1 ： Study basic 生物 和 GATK knowdge. 学习实验室知识。
2. month 2 ： test a simple gatk flow, call variants. 进行基础实验。
3. month 3 ： acquire cancer BAM file (150 -200) and use nextflow to run
4. month 4 ： Study python and 统计学知识，对VCF的结果进行统计
5. month 5 ： use colab进行 mutation features anaylize
6. month 6 ： study machine learing 知识
7. month 7 ： Train a machine learning classifier  
8. month 8 ： Evaluate and visualize results
9. month 9 ： review code and doc ，write 论文
10. month 10 ： 导师对论文评审 及修改。

## Page 8  Expected Outcomes

- A complete mutation analysis and prediction pipeline  
- Visualizations and summary statistics of key mutations  
- A GitHub repository with code, notebooks, and reports  
- A final summary presentation and (optional) student research paper  

## Page 9 Help Needed

- Looking forward to learning from PhD and lab members
- looking for some 可用的 data from 清华

## Page 10 Thank you

Thank you for the opportunity to join the lab!  
I look forward to your guidance and feedback.  
— Xiaonuan Fu