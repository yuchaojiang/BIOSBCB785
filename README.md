![Image description](https://github.com/yuchaojiang/BIOSBCB785/blob/master/Title.png)

### Instructor

[Yuchao Jiang](https://yuchaojiang.github.io/), Assistant Professor, Departments of Biostatistics & Genetics, UNC Chapel Hill<br /> 
Office: 4115D McGavran-Greenberg Hall<br /> 
Phone:  919-843-3656<br /> 
Email:  yuchaoj@email.unc.edu (contact via slack is preferred)


### Course Information

* **Description**: This course is designed to provide graduate students interested in statistical genetics and genomics with an opportunity to gain or enhance knowledge in gene expression analysis by next-generation sequencing. The course is aimed at preparing students for conducting methodological research in high-throughput transcriptomic studies. The course includes two sections: bulk RNA-seq and single-cell RNA-seq (scRNA-seq). Each section starts with biological background, followed by statistical and computational methods, and finishes with biological interpretations and follow-ups. Topics include data normalization, measurement of error models, dispersion shrinkage, dimensionality reduction, zero-inflated factor analysis, batch correction, clustering algorithm, deconvolution, pseudotime reconstruction, deep neural network, and autoencoder, etc.

* **[Course Slack](http://unc785spring2023.slack.com/)**

* **[Syllabus](https://www.dropbox.com/s/wjb3c4ihva60f3g/BIOS785_Spring2023_Yuchao_Jiang.pdf?dl=0)**

* **[Course Schedule](https://docs.google.com/spreadsheets/d/1TjQCCgqk-1s0F8PrYYB7yeJAWmy6xEWw5RiEmpNhVRw/edit?usp=sharing)**

* **Class Time & Location**: Tuesdays and Thursdays, 9:30am – 10:45am; McGavran-Greenberg 2301.

* **Office Hours**: Thursdays 11am - noon; McGavran-Greenberg 4115D.

* **Grader**: Wancen Mu (wancen@live.unc.edu)


### Lecture Slides/Papers/Videos

* **Lecture 1**: Introduction to Molecular Biology ([slides](https://www.dropbox.com/s/8gmtr40ru33od5n/Lecture_1.pdf?dl=0))
* **Lecture 2**: Introduction to RNA Sequencing ([slides](https://www.dropbox.com/s/iq049r01h5hy496/Lecture_2.pdf?dl=0), [paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8))
* **Lecture 3**: RNA Sequencing Data Normalization ([slides](https://www.dropbox.com/s/q3buwqo7b29b8vl/Lecture_3.pdf?dl=0), [paper](https://www.nature.com/articles/nbt.2931))
* **Lecture 4**: RNA Sequencing Batch Correction ([slides](https://www.dropbox.com/s/hpe3y5j7ssfy5kw/Lecture_4.pdf?dl=0), [paper1](https://academic.oup.com/biostatistics/article/8/1/118/252073), [paper2](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.0030161))
* **Lecture 5**: Isoform Expression ([slides](https://www.dropbox.com/s/yc32x8roea1uk9i/Lecture_5.pdf?dl=0), [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2666817/))
* **Lecture 6**: Allele-Specific Gene Expression and Mapping of eQTLs ([slides](https://www.dropbox.com/s/m7a2x1ffxwb287i/Lecture_6.pdf?dl=0), [paper](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1541-0420.2011.01654.x))
* **Lecture 7**: Bulk Gene Expression Deconvolution ([slides](https://www.dropbox.com/s/xfxtgxnczgdo22d/Lecture_7.pdf?dl=0), [paper1](https://www.nature.com/articles/nmeth.1439), [paper2](https://www.nature.com/articles/nmeth.3337))
* **Lecture 8**: Differential Gene Expression Analysis by Bulk RNA Sequencing ([slides](https://www.dropbox.com/s/0yctgxsa4gp0nim/Lecture_8.pdf?dl=0), [paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0550-8))
* **Lecture 9**: Gene Set Enrichment Analysis ([slides](https://www.dropbox.com/s/80n38aj9ws3h7b3/lecture_9_new.pdf?dl=0), [paper1](https://www.pnas.org/content/102/43/15545.long), [paper2](https://academic.oup.com/nar/article/40/17/e133/2411151))
* **Lecture 10**: Multiple Hypothesis Testing Correction ([slides](https://www.dropbox.com/s/dy1geo1qly8skhv/Lecture_10.pdf?dl=0), [paper](https://www.pnas.org/content/100/16/9440.long), [script](https://www.dropbox.com/s/n7vb4ztpxob4ogh/lec10.R?dl=0))
* **Lecture 11**: Introduction to Single-Cell RNA Sequencing ([slides](https://www.dropbox.com/s/kafci5whovtj614/Lecture_11.pdf?dl=0), [paper1](https://www.sciencedirect.com/science/article/pii/S1097276515002610), [paper2](https://www.nature.com/articles/nrg3833))
* **Lecture 12**: Dimensionality Reduction and Data Visualization ([slides](https://www.dropbox.com/s/ngsch65gjrn1k24/Lecture_12.pdf?dl=0), 
[paper1](https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf), [paper2](https://www.nature.com/articles/nbt.4314), [script](https://www.dropbox.com/s/6yxdds6vehj1ko9/lecture12.R?dl=0))
* **Lecture 13**: Single-Cell RNA Sequencing Analysis Workflow ([slides](https://www.dropbox.com/s/zs93y79mlhn7dfn/lecture13.pdf?dl=0), [paper1](https://www.embopress.org/doi/full/10.15252/msb.20188746), [paper2](https://www.nature.com/articles/s41592-019-0654-x))
* **Lecture 14**: Clustering of Single-Cell RNA Sequencing Data 
([slides](https://www.dropbox.com/s/wudpn8ukz4v4bko/lecture14.pdf?dl=0), 
[paper1](https://academic.oup.com/bioinformatics/article-abstract/35/8/1269/5092931?redirectedFrom=fulltext), 
[paper2](https://www.nature.com/articles/s41598-019-41695-z))
* **Lecture 15**: Mid-Semester Review and Project Overview ([slides](https://www.dropbox.com/s/q88f2cay2cwjnec/Lecture_15.pdf?dl=0), [review](https://www.dropbox.com/s/9g5zbsjft68fudb/review.pdf?dl=0))
* **Lecture 16**: Single-Cell RNA Sequencing Denoising and Imputaton ([slides](https://www.dropbox.com/s/7fj8tsq681vg80m/Lecture_16.pdf?dl=0), [paper1](https://www.nature.com/articles/s41592-018-0033-z), [paper2](https://www.cell.com/cell/fulltext/S0092-8674(18)30724-4))
* **Lecture 17**: Single-Cell RNA Sequencing Batch Correction ([slides](https://www.dropbox.com/s/wyoty7bfizmg5zu/Lecture_17.pdf?dl=0), [paper1](https://www.nature.com/articles/nbt.4096), [paper2](https://www.nature.com/articles/nbt.4091))
* **Lecture 18**: Introduction to Deep Neural Network ([slides](https://www.dropbox.com/s/0smnnacb2g0zy2s/Lecture_18.pdf?dl=0), [book](http://www.deeplearningbook.org/))
* **Lecture 19**: Allele-Specific Gene Expression by Single-Cell RNA Sequencing ([slides](https://www.dropbox.com/s/hx0af78zqkzrivw/Lecture_19.pdf?dl=0), [paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1200-8))
* **Lecture 20**: Gene Expression Distribution ([slides](https://www.dropbox.com/s/ajvnvs2far11651/Lecture_20.pdf?dl=0), [paper1](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-1077-y), [paper2](https://www.pnas.org/content/115/28/E6437))
* **Lecture 21**: Bulk Gene Expression Deconvolution by Single-Cell RNA Sequencing ([slides](https://www.dropbox.com/s/umyrfm56oxxx7dh/Lecture_21.pdf?dl=0), [paper1](https://www.nature.com/articles/s41467-018-08023-x), [paper2](https://projecteuclid.org/euclid.aoas/1520564486))
* **Lecture 22**: Autoencoder and Transfer Learning for Single-Cell RNA Sequencing ([slides](https://www.dropbox.com/s/cz24fgci3709ehj/lecture22.pdf?dl=0), [paper1](https://www.nature.com/articles/s41467-018-07931-2), [paper2](https://www.nature.com/articles/s41592-019-0537-1))
* **Lecture 23**: Single-Cell Multimodal Alignment ([slides](https://www.dropbox.com/s/skh4316ij503osx/Lecture_23.pdf?dl=0), [paper1](https://www.pnas.org/content/115/30/7723.long), [paper2](https://www.cell.com/cell/fulltext/S0092-8674(19)30504-5?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867419305045%3Fshowall%3Dtrue), [paper3](https://www.cell.com/cell/fulltext/S0092-8674(19)30559-8?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867419305598%3Fshowall%3Dtrue))
* **Lecture 24**: Integrative Analysis of Genome-Wide Association Studies and Single-Cell Omics  ([slides](https://www.dropbox.com/s/4mdtuot5vkox4v1/lecture24.pdf?dl=0), [paper1](https://www.cell.com/ajhg/fulltext/S0002-9297(17)30378-6), [paper2](https://www.nature.com/articles/s41588-018-0081-4), [paper3](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1010251))
* **Lecture 25**: Single-Cell RNA Sequencing in Cancer Genomics ([slides](https://www.dropbox.com/s/7y04v6vfxz64eeo/Lecture_25.pdf?dl=0), [paper1](https://genome.cshlp.org/content/28/8/1217.long), [paper2](https://www.nature.com/articles/s41592-020-0766-3?proof=t))
* **Lecture 26**: Single-Cell Trajectory Inference and RNA Velocity ([slides](https://www.dropbox.com/s/rbaq8eu4yuln9hu/BIOSBCB785_trajectory_analysis.pdf?dl=0), [paper1](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-4772-0), [paper2](https://www.nature.com/articles/s41587-019-0071-9), [paper3](https://www.nature.com/articles/s41586-018-0414-6), [script](https://colab.research.google.com/drive/14LRc76ltDEnHi4v2jUWCS9Tad-RbXOLz?usp=sharing))
* **Lecture 27**: Single-Cell QTL Mapping ([slides](https://www.dropbox.com/s/4lec987h5kjdt8n/lecture27_single_cell_QTL.pdf?dl=0), [paper1](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02293-3), [paper2](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1009666))

### Coding Assignment
* [Instructions](https://www.dropbox.com/s/yre9bhlj33tk87z/BIOS_BCB_785_Spring2023_coding_assignment.pdf?dl=0)
* [Solutions1](https://www.dropbox.com/s/6r5acolodtlzb02/BIOS785_Fall2020_Krajewski_coding_assignment.pdf?dl=0), [Solutions2](https://www.dropbox.com/s/uxeh14hbgxc7vyv/Abdalla_Alkhawaja_bios785_coding_assignment.html?dl=0)

### Tutorials & Workflows

* [RNA-seq analysis](https://github.com/crazyhottommy/RNA-seq-analysis)
* [RNA-seqlopedia](https://rnaseq.uoregon.edu)
* [Informatics for RNA-seq](https://github.com/griffithlab/rnaseq_tutorial)
* [Analysis of single cell RNA-seq data](https://hemberg-lab.github.io/scRNA.seq.course)
* [Awesome single cell](https://github.com/seandavi/awesome-single-cell)
* [simpleSingleCell](http://bioconductor.org/packages/simpleSingleCell)
* [Orchestrating Single-Cell Analysis with Bioconductor](https://osca.bioconductor.org)


### Resources & Datasets

* [GTEx Portal](https://gtexportal.org)
* [10X Genomics single-cell expression](https://support.10xgenomics.com/single-cell-gene-expression/datasets)
* [Single Cell Portal](https://portals.broadinstitute.org/single_cell)
* [Single Cell Expression Atlas](https://www.ebi.ac.uk/gxa/sc)
* [conquer](http://imlspenticton.uzh.ch:3838/conquer)
* [Human Cell Atlas](https://www.humancellatlas.org/)
* [Mouse Cell Atlas](http://bis.zju.edu.cn/MCA)


### Other Resources

* [Tips for Presentation](https://www.dropbox.com/s/k5ymqz8qflpeskl/Tips_for_presentations.pdf?dl=0)
* [Guidelines for Written Review](https://www.dropbox.com/s/rr82bz5alp8ewcx/Written_review_assignments.pdf?dl=0)
