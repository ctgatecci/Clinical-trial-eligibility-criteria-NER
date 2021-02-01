# Benchmarking transformer models with named entity recognition in clinical trial eligibility criteria 

Chia dataset can be downloaded here: https://figshare.com/articles/dataset/Chia_Annotated_Datasets/11855817/2

Facebook Research Data can be downloaded here: https://github.com/facebookresearch/Clinical-Trial-Parser/blob/master/data/ner/medical_ner.tsv

transformer.zip file contains the prediction and evaluation results of Chia dataset and FRD dataset using different models.

Reference:
1. Kury, Fabrício, et al. “Chia, a Large Annotated Corpus of Clinical Trial Eligibility Criteria.” Nature News, Nature Publishing Group, 27 Aug. 2020, www.nature.com/articles/s41597-020-00620-0. 

2. @article{10.1093/jamia/ocaa189,
    author = {Yang, Xi and Bian, Jiang and Hogan, William R and Wu, Yonghui},
    title = "{Clinical concept extraction using transformers}",
    journal = {Journal of the American Medical Informatics Association},
    year = {2020},
    month = {10},
    abstract = "{The goal of this study is to explore transformer-based models (eg, Bidirectional Encoder Representations from Transformers [BERT]) for clinical concept extraction and develop an open-source package with pretrained clinical models to facilitate concept extraction and other downstream natural language processing (NLP) tasks in the medical domain.We systematically explored 4 widely used transformer-based architectures, including BERT, RoBERTa, ALBERT, and ELECTRA, for extracting various types of clinical concepts using 3 public datasets from the 2010 and 2012 i2b2 challenges and the 2018 n2c2 challenge. We examined general transformer models pretrained using general English corpora as well as clinical transformer models pretrained using a clinical corpus and compared them with a long short-term memory conditional random fields (LSTM-CRFs) mode as a baseline. Furthermore, we integrated the 4 clinical transformer-based models into an open-source package.The RoBERTa-MIMIC model achieved state-of-the-art performance on 3 public clinical concept extraction datasets with F1-scores of 0.8994, 0.8053, and 0.8907, respectively. Compared to the baseline LSTM-CRFs model, RoBERTa-MIMIC remarkably improved the F1-score by approximately 4\\% and 6\\% on the 2010 and 2012 i2b2 datasets. This study demonstrated the efficiency of transformer-based models for clinical concept extraction. Our methods and systems can be applied to other clinical tasks. The clinical transformer package with 4 pretrained clinical models is publicly available at https://github.com/uf-hobi-informatics-lab/ClinicalTransformerNER. We believe this package will improve current practice on clinical concept extraction and other tasks in the medical domain.}",
    issn = {1527-974X},
    doi = {10.1093/jamia/ocaa189},
    url = {https://doi.org/10.1093/jamia/ocaa189},
    note = {ocaa189},
    eprint = {https://academic.oup.com/jamia/advance-article-pdf/doi/10.1093/jamia/ocaa189/34055422/ocaa189.pdf},
}
