# A Survey of Large Language Models for Arabic Language and its Dialects
<div align="center">
  <a href="https://arxiv.org/abs/2410.20238">
    <img src="https://img.shields.io/badge/arXiv-Paper%20Download-b31b1b.svg" alt="Download from arXiv">
  </a>
</div>
This survey offers a comprehensive overview of Large Language Models (LLMs) designed for Arabic language and its dialects. It covers key architectures, including encoder-only, decoder-only, and encoder-decoder models, along with the datasets used for pre-training, spanning Classical Arabic, Modern Standard Arabic, and Dialectal Arabic. The study also explores monolingual, bilingual, and multilingual LLMs, analyzing their architectures and performance across downstream tasks, such as sentiment analysis, named entity recognition, and question answering. Furthermore, it assesses the openness of Arabic LLMs based on factors, such as source code availability, training data, model weights, and documentation. The survey highlights the need for more diverse dialectal datasets and attributes the importance of openness for research reproducibility and transparency. It concludes by identifying key challenges and opportunities for future research and stressing the need for more inclusive and representative models.

### Aspects of the survey
![Arabic LLM Survey](https://github.com/iwan-rg/ArabicLLMs/blob/main/Arabic%20LLM%20Survey.png?raw=true)

### Geographic Distribution and Development of Arabic LLMs. Model names with the same color indicate collaborative development efforts between different countries.

![Geographic Distribution and Development of Arabic LLMs. Model names with the same color indicate collaborative development efforts between different countries.](https://github.com/iwan-rg/ArabicLLMs/blob/main/LLM%20Map.png?raw=true)


## Datasets for Arabic LLMs Pretraining

### Classical Arabic (CA) 
- OpenITI corpus (v1.2) <a href="https://openiti.org/projects/OpenITI%20Corpus.html" target="_blank">Link</a>.
  
### Modern Standard Arabic (MSA) 
- 1.5 billion Words Arabic Corpus <a href="https://arxiv.org/pdf/1611.04033v1" target="_blank">Link</a>.
- OSIAN Corpus <a href="https://aclanthology.org/W19-4619/" target="_blank">Link</a>.
- Gigaword Corpus <a href="https://catalog.ldc.upenn.edu/LDC2003T12" target="_blank">Link</a>.
- Oscar Corpus <a href="https://oscar-project.org/" target="_blank">Link</a>.
- Arabic Wikipedia Dump <a href="https://archive.org/details/arwiki-20190201" target="_blank">Link</a>.
- ArabicText 2022 <a href="https://data.baai.ac.cn/details/ArabicText-2022" target="_blank">Link</a>.
- AraC4 <a href="https://www.tensorflow.org/datasets/catalog/c4" target="_blank">Link</a>.
- Maktabah <a href="https://www.kaggle.com/datasets/mahmoudqaddoumi/arabic-library" target="_blank">Link</a>.
- TyDi dataset <a href="https://github.com/google-research-datasets/tydiqa?tab=readme-ov-file#download-the-dataset" target="_blank">Link</a>.
- ARCD <a href="https://metatext.io/datasets/arabic-reading-comprehension-dataset-(arcd)" target="_blank">Link</a>.
- CC100-Arabic <a href="https://metatext.io/datasets/cc100-arabic" target="_blank">Link</a>.
- OpenSubtitles2016 corpus <a href="https://www.opensubtitles.org/en/search/subs" target="_blank">Link</a>.
- AraNews <a href="https://github.com/UBC-NLP/wanlp2020_arabic_fake_news_detection" target="_blank">Link</a>.
- Hindawi <a href="https://huggingface.co/datasets/alielfilali01/Hindawi-Books-dataset" target="_blank">Link</a>.





-  ....
  
### Dialectal Arabic (DA) 
- CALLHOME Egyptian Arabic Transcripts 
- CALLHOME Egyptian Arabic Transcripts Supplement
- Babylon Levantine Arabic Transcripts
- ...
  
## Monolingual Arabic LLMs
- AraBERT
- MARBERT
- ARBERT
- QARiB
- SudaBERT
- AraELECTRA
- AraGPT2
- CAMeLBERT
- JABER
- SABER
- AraBART
- AraLegal-BERT
- AraRoBERTa
- DziriBERT
- TunBERT
- DarijaBERT
- AraMUS
- MorRoBERTa
- MorrBERT
- JASMINE
- AraQA
- ArabianGPT
- AraPOEMBERT
- SaudiBERT
- AlcLaM
- AraStories
- EgyBERT
- Atlas-Chat

## Bilingual Arabic LLMS
- GigaBERT 
- JAIS 
- AceGPT
- ALLaM

## Multilingual Arabic LLMS
- ArabicBERT 	
- AraT5 

## Citation
Please cite our paper if you use it in your work:

**BibTeX**
```bibtex
@misc{mashaabi2024survey,
      title={A Survey of Large Language Models for Arabic Language and its Dialects}, 
      author={Malak Mashaabi and Shahad Al-Khalifa and Hend Al-Khalifa},
      year={2024},
      institution={iWAN Research Group, College of Computer and Information Sciences, King Saud University},
      url={https://arxiv.org/abs/2410.20238}, 
}
