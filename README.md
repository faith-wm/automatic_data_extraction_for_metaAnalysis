# Automatic data extraction from PubMed abstracts

NER models for extracting information from randomized controlled trials (RCTs) abstracts crawled from the PubMed database.
We extract core elements of RCTs, i.e., Participants, Intervention, Control, and Outcome (PICO).

# Dataset
The dataset consists of 1011 abstracts annotated using BRAT web annotation tool.
The dataset can be downloaded freely from this <a href="https://github.com/sociocom/PICO-Corpus">Github repository</a>.

# BERT models
BioBERT: <a href="https://github.com/dmis-lab/biobert">https://github.com/dmis-lab/biobert</a>

BlueBERT: <a href="https://github.com/ncbi-nlp/bluebert">https://github.com/ncbi-nlp/bluebert</a>

LongFormer: <a href="https://github.com/allenai/longformer">https://github.com/allenai/longformer</a>

Clinical longformer: <a href="https://huggingface.co/yikuan8/Clinical-Longformer">https://huggingface.co/yikuan8/Clinical-Longformer</a>


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
