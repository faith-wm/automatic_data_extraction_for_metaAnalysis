# Automatic data extraction from PubMed abstracts

NER models for extracting information from randomized controlled trials (RCTs) abstracts crawled from the PubMed database.
We extract core elements of RCTs, i.e., Participants, Intervention, Control, and Outcome (PICO).

# Dataset
The dataset consists of 1011 abstracts annotated using BRAT web annotation tool.
The dataset can be downloaded freely from this <a href="https://github.com/sociocom/PICO-Corpus">Github repository</a>.

# BERT models
BioBERT

BlueBERT

LongFormer

Clinical longformer


# Reference
For detailed information on this task please check the <a href="">project website</a> and read the paper below.

If you use this dataset please cite our paper:
```
@article{mutinda2022automatic,
  title={Automatic data extraction to support meta-analysis statistical analysis: a case study on breast cancer},
  author={Mutinda, Faith Wavinya and Liew, Kongmeng and Yada, Shuntaro and Wakamiya, Shoko and Aramaki, Eiji},
  journal={BMC Medical Informatics and Decision Making},
  volume={22},
  number={1},
  pages={1--13},
  year={2022},
  publisher={BioMed Central}
}
```
