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
 
### Dialectal Arabic (DA) 
- CALLHOME Egyptian Arabic Transcripts <a href="https://catalog.ldc.upenn.edu/LDC97T19">Link</a>.
- CALLHOME Egyptian Arabic Transcripts Supplement <a href="https://catalog.ldc.upenn.edu/LDC2002T38">Link</a>.
- Babylon Levantine Arabic Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2005S08">Link</a>.
- Levantine Arabic QT Training Data Set 4 Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2005S14">Link</a>.
- Levantine Arabic QT Training Data Set 5 Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2006T07">Link</a>.
- Gulf Arabic Conversational Telephone Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2006T15">Link</a>.
- Iraqi Arabic Conversational Telephone Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2006T16">Link</a>.
- Levantine Arabic Conversational Telephone Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2007T01">Link</a>.
- Fisher Levantine Arabic Conversational Telephone Transcripts <a href="https://catalog.ldc.upenn.edu/LDC2007T04">Link</a>.
- AOC Dataset <a href="https://www.cs.jhu.edu/data-archive/AOC-2010/?C=D;O=D">Link</a>.
- Arabic-Dialect/English Parallel Text <a href="https://catalog.ldc.upenn.edu/LDC2012T09">Link</a>.
- PADIC Corpus <a href="https://sourceforge.net/projects/padic/">Link</a>.
- Curras Corpus <a href="https://www.jarrar.info/publications/JHRAZ17.pdf">Link</a>.
- BOLT Egyptian Arabic SMS/Chat and Transliteration <a href="https://catalog.ldc.upenn.edu/LDC2017T07">Link</a>.
- SDC (Shami Dialect Corpus) <a href="https://github.com/GU-CLASP/shami-corpus">Link</a>.
- Gumar Corpus <a href="https://camel.abudhabi.nyu.edu/gumar/">Link</a>.
- MADAR Corpus <a href="https://sites.google.com/nyu.edu/madar/home#h.xpcfdhjyc95c">Link</a>.
- Habibi Corpus <a href="http://ucrel-web.lancaster.ac.uk/habibi/">Link</a>.
- NADI 2020 Corpus <a href="https://sites.google.com/view/nadi-shared-task">Link</a>.
- QADI Corpus <a href="https://alt.qcri.org/resources/qadi/">Link</a>.
- Darija-SFT-Mixture dataset <a href="https://huggingface.co/datasets/MBZUAI-Paris/Darija-SFT-Mixture">Link</a>.

## Monolingual Arabic LLMs
- AraBERT <a href="https://aclanthology.org/2020.osact-1.2">Link</a>.
- MARBERT <a href="https://aclanthology.org/2021.acl-long.551">Link</a>.
- ARBERT  <a href="https://aclanthology.org/2021.acl-long.551">Link</a>.
- QARiB   <a href="https://aclanthology.org/2020.wanlp-1.21">Link</a>.
- SudaBERT <a href="https://ieeexplore.ieee.org/abstract/document/9429651">Link</a>.
- AraELECTRA <a href="https://aclanthology.org/2021.wanlp-1.20">Link</a>.
- AraGPT2 <a href="https://aclanthology.org/2021.wanlp-1.21">Link</a>.
- CAMeLBERT <a href="https://aclanthology.org/2021.wanlp-1.10">Link</a>.
- JABER <a href="https://aclanthology.org/2022.emnlp-main.205">Link</a>.
- SABER <a href="https://aclanthology.org/2022.emnlp-main.205">Link</a>.
- AraBART <a href="https://aclanthology.org/2022.wanlp-1.4">Link</a>.
- AraLegal-BERT <a href="https://aclanthology.org/2022.nllp-1.31">Link</a>.
- AraRoBERTa <a href="https://aclanthology.org/2022.wanlp-1.24">Link</a>.
- DziriBERT <a href="http://arxiv.org/abs/2109.12346">Link</a>.
- TunBERT <a href="https://doi.org/10.1007/s42979-022-01541-y">Link</a>.
- DarijaBERT <a href="https://link.springer.com/10.1007/s41060-023-00498-2">Link</a>.
- AraMUS <a href="https://aclanthology.org/2023.findings-acl.181">Link</a>.
- MorRoBERTa <a href="https://www.researchgate.net/publication/375765718_Pre-training_Two_BERT-Like_Models_for_Moroccan_Dialect_MorRoBERTa_and_MorrBERT#fullTextFileContent">Link</a>.
- MorrBERT <a href="https://www.researchgate.net/publication/375765718_Pre-training_Two_BERT-Like_Models_for_Moroccan_Dialect_MorRoBERTa_and_MorrBERT#fullTextFileContent">Link</a>.
- JASMINE <a href="https://aclanthology.org/2023.emnlp-main.1040">Link</a>.
- AraQA <a href="https://ieeexplore.ieee.org/abstract/document/10479645">Link</a>.
- ArabianGPT <a href="http://arxiv.org/abs/2402.15313">Link</a>.
- AraPOEMBERT <a href="http://arxiv.org/abs/2403.12392">Link</a>.
- SaudiBERT <a href="http://arxiv.org/abs/2405.06239">Link</a>.
- AlcLaM <a href="https://aclanthology.org/2024.arabicnlp-1.14">Link</a>.
- AraStories <a href="https://aclanthology.org/2024.arabicnlp-1.13">Link</a>.
- EgyBERT <a href="http://arxiv.org/abs/2408.03524">Link</a>.
- Atlas-Chat <a href="http://arxiv.org/abs/2409.17912">Link</a>.

## Bilingual Arabic LLMS
- GigaBERT <a href="https://aclanthology.org/2020.emnlp-main.382">Link</a>.
- JAIS <a href="http://arxiv.org/abs/2308.16149">Link</a>.
- AceGPT <a href="https://aclanthology.org/2024.naacl-long.450">Link</a>.
- ALLaM <a href="http://arxiv.org/abs/2407.15390">Link</a>.

## Multilingual Arabic LLMS
- ArabicBERT 	<a href="https://aclanthology.org/2020.semeval-1.271">Link</a>.
- AraT5 <a href="https://aclanthology.org/2022.acl-long.47">Link</a>.

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
