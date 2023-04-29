# BioSift: A Dataset for Filtering Biomedical Abstracts for Drug Repurposing and Clinical Meta-Analysis. 

Repository containining dataset described in the following paper:

> BioSift: A Dataset for Filtering Biomedical Abstracts for Drug Repurposing and Clinical Meta-Analysis <br>
> David Kartchner*, Irfan Al-Hussaini*, Haydn Turner*, Jennifer Deng, Shubham Lohiya, Prasanth Bathala, Cassie Mitchell <br>
> In 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023)

## PMID_Title_Abstract.csv
- Contains the PMID of the abstract, the Title of the abstract, and the entire abstract
- The first row contains the following headers: PMID,Split,Number of Annotators,Aggregate,Has Human Subjects,Has Target Disease,Cohort Study or Clinical Trial,Has Quantitative Outcome Measure,Has Study Drug(s),Has Population Size,Has Comparator Group


## PMID_BinaryLabels.csv:
- Contains the PMID of the abstract, the dataset split it belongs to, number of annotations, the binary labels of the 7 classes, and the Aggregate label.
- The first row contains the following headers: PMID,Split,Number of Annotators,Aggregate,Has Human Subjects,Has Target Disease,Cohort Study or Clinical Trial,Has Quantitative Outcome Measure,Has Study Drug(s),Has Population Size,Has Comparator Group


## PMID_SoftLabels.csv
- Contains the PMID of the abstract, the dataset split it belongs to, number of annotations, the soft labels of the 7 classes based on number of positive annotations relative to total number of annotations, and the Aggregate label.
- The first row contains the following headers: PMID,Split,Number of Annotators,Aggregate,Has Human Subjects,Has Target Disease,Cohort Study or Clinical Trial,Has Quantitative Outcome Measure,Has Study Drug(s),Has Population Size,Has Comparator Group

## Citation Bibtex:
```
@inproceedings{biosift2023,
 title = "BioSift: A Dataset for Filtering Biomedical Abstracts for Drug Repurposing and Clinical Meta-Analysis",
 author = "Kartchner, David and 
    Al-Hussaini, Irfan and 
    Turner, Haydn and 
    Deng, Jennifer and
    Lohiya, Shubham and 
    Bathala, Prasanth and 
    Mitchell, Cassie S.",
 booktitle = "Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023)",
 month = July,
 year = "2023",
 address = "Taipei, Taiwan",
 publisher = "Association for Computing Machinery"
}
```
