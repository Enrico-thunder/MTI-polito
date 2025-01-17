Master Thesis Instructions
=================
Contact Points:

- Luca Cagliero: luca.cagliero@polito.it 
- Moreno La Quatra: moreno.laquatra@polito.it

This repository contains the information used for the development a master thesis in the NLP domain at PoliTO.


Table of contents
=================

   * [Instructions and templates](#instructions-and-templates)
   * [Thesis proposals](#thesis-proposals)
     * [Active Learning meets NLP](#al-meets-nlp-)
     * [Generative Sentiment Analysis](#generative-sentiment-analysis-)
     * [Unsupervised Representation Learning (Contrastive Learning)](#unsupervised-representation-learning-)
     * [NLP-aided voice cloning](#nlp-aided-voice-cloning-) **NEW**
   * [Graduated Students](#graduated-students)

Instructions and templates
============

The latex template to write the master thesis is avaiable in [Overleaf](https://it.overleaf.com/latex/templates/master-thesis-template-polito/jvfrbmxqkscw)

The first step is to create a GitHub Educational account and create an ad-hoc repository containing all relevant code and information for the master thesis.

The research work expected during the development of the master thesis will cover the following steps.

### State-of-the-art exploration
Collect, read and analyze the most recent and relevant publications in the proposed application field. Related works could be summarized and presented by using the Markdown Template available [here](/RW_template.md). Publication could be searched by using the following services:
- [Google Scholar](https://scholar.google.com/)
- [Arxiv](https://arxiv.org/search/)

### Data collection and finding
The majority of the thesis requires a step of data collection or data search. 
During the exploration of the state of the art the student is asked to collect and organize the data used by each publication.
Dataset must be presented in an organized way by expoiting the Markdown template available [here](/DS_template.md)
If a new data collection is created/parsed please create a specific Markdown file (template available [here](/NEWDS_template.md)) explaining both the data collection procedure and the statistics of the data collection.


A video tutorial explaining how to create a Python package is available here: [YouTube](https://www.youtube.com/watch?v=GIF3LaRqgXo) .

Thesis proposals
============

### AL meets NLP <a href="mailto:moreno.laquatra@polito.it,luca.cagliero@polito.it?subject=[Master Thesis] AL meets NLP - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>
<a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><img src="https://img.shields.io/badge/AL-Active%20Learning-red" alt="Active Learning"></a>
<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

![immagine](https://user-images.githubusercontent.com/10062811/138847790-ee16d16f-4583-42e5-8f5c-f2448f5b9898.png)
_image source: https://www.semanticscholar.org/paper/Deep-active-learning-using-Monte-Carlo-Dropout-Moura/5418d0d92165270afa20cf84e93b0beeba41202f_

Active Learning is a subfield of machine learning that aims at reducing the number of supervised samples needed to train a machine learning model. 
It include an human-in-the-loop procedure aimed at selecting the most relevant examples for model's learning.

The **main objectives** of this thesis are:

- Explore the state of the art in Active Learning
- Define and propose an Active Learning approach for the fine-tuning of *deep* neural language models.
- Simulate the process on existing benchmark dataset

**References :books::**

Citovsky, G., DeSalvo, G., Gentile, C., Karydas, L., Rajagopalan, A., Rostamizadeh, A., & Kumar, S. (2021). Batch Active Learning at Scale. arXiv preprint arXiv:2107.14263. [article](https://arxiv.org/abs/2107.14263)

Peshterliev, S., Kearney, J., Jagannatha, A., Kiss, I., & Matsoukas, S. (2019, June). Active Learning for New Domains in Natural Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Industry Papers) (pp. 90-96). [article](https://www.aclweb.org/anthology/N19-2012.pdf)

Schröder, C., & Niekler, A. (2020). A Survey of Active Learning for Text Classification using Deep Neural Networks. arXiv preprint arXiv:2008.07267. [article](https://arxiv.org/pdf/2008.07267.pdf)


**Interesting projects :computer::**

- [modAL](https://github.com/modAL-python/modAL)
- [libact](https://github.com/ntucllab/libact)


**Additional Material:**

Active Learning: Algorithmically Selecting Training Data to Improve Alexa’s Natural-Language Understanding [post](https://www.amazon.science/blog/active-learning-algorithmically-selecting-training-data-to-improve-alexas-natural-language-understanding)

Active Learning for Natural Language Processing. [post](https://crowintelligence.org/2020/06/04/active-learning-for-natural-language-processing/)






***





### Generative Sentiment Analysis <a href="mailto:moreno.laquatra@polito.it,luca.cagliero@polito.it?subject=[Master Thesis] Generative Sentiment Analysis - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

![immagine](https://user-images.githubusercontent.com/10062811/138848047-665b02df-33a9-4d23-8cb1-073c55be7884.png)
_image by: https://github.com/soobinseo/cycle-gan_

Sentiment analysis is one of the most important task in several NLP pipelines.
It consists in the analysis of text for classifying its sentiment being both positive or negative.
Generative models such as [GPT3](https://arxiv.org/abs/2005.14165) open a large set of possibilities in this scenario.
This master thesis will cover both generative language and sentiment analysis.

The **main objectives** of this thesis are:

- Define and explore the state of the art in Language Generation.
- Analyze state of the art methodologies in Sentiment Anaysis.
- Simulate an innovative pipeline on existing benchmark dataset.

**References :books::**

Wang, H., & Zhai, C. (2017). Generative models for sentiment analysis and opinion mining. In A practical guide to sentiment analysis (pp. 107-134). Springer, Cham. [article](https://link.springer.com/chapter/10.1007/978-3-319-55394-8_6)

Gupta, R. (2019, May). Data augmentation for low resource sentiment analysis using generative adversarial networks. In ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 7380-7384). IEEE. [article](https://arxiv.org/abs/1902.06818)



***





### Text Paraphrasing <a href="#"><img src="https://shields.io/badge/Click%20to%20candidate-not available-red" alt="Not Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

![synonymNew](https://user-images.githubusercontent.com/10062811/138848869-d0b5693a-7574-41e7-9411-61e8b5bafdad.gif)
_image by: https://quillbot.com/_

Text paraphrasing aims at reformulating natural language by conveying the same meaning with different words. For example:
- I would like to know if tomorrow will be sunny in Turin.
- Will it be sunny tomorrow in Turin?
- Will be a sunny day in Turin tomorrow?

All those sentences bring the same meaning using slightly different formulations. The syntactic element are different, however the semantic behind the is the same.

The **main objectives** of this thesis are:

1. Analyze the state-of-the-art in text paraphrasing models.
2. Exploit latest advancement in deep learning techniques to create a text paraphrasing tool based on Transformers.
3. Evaluate the proposed pipeline on benchmark datasets ([Quora](https://paperswithcode.com/dataset/quora-question-pairs), [ParaSCI](https://github.com/dqxiu/ParaSCI), etc.).

**References :books::**

Dong, Q., Wan, X., & Cao, Y. ParaSCI: A Large Scientific Paraphrase Dataset for Longer Paraphrase Generation. [article](https://aclanthology.org/2021.eacl-main.33.pdf)

Hosking, T., & Lapata, M. (2021). Factorising Meaning and Form for Intent-Preserving Paraphrasing. arXiv preprint arXiv:2105.15053. [article](https://aclanthology.org/2021.acl-long.112.pdf)





***





### Unsupervised Representation Learning <a href="mailto:moreno.laquatra@polito.it,luca.cagliero@polito.it?subject=[Master Thesis] Unsupervised Representation Learning  - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

![immagine](https://user-images.githubusercontent.com/10062811/138849271-71e64021-1ada-46a1-b4f6-9a1d1838c1ee.png)
_image by: https://arxiv.org/abs/2009.12061_

Learning effective representations of the input data is one of the main challenges of deep learning algorithms. While it is framed as an independent task, effective representations are beneficial in a variety of contexts and domains. **Contrastive Learning** is one of the hot-topics in current research. It allows exploiting un-annotated data to let the model learns by contrastive examples. It all started in the Computer Vision domain with some groundbreaking publications (e.g., [SimCLR](https://arxiv.org/abs/2002.05709)), however, at the time of writing, almost 400 papers have been published both for CV and NLP.

The **main objectives** of this thesis are:

1. Analyze the state-of-the-art in contrastive learning and data augmentation techniques (mainly in NLP).
2. Find interesting spots where Contrastive Learning can be effectively exploited (e.g., structured data representation)
3. Define a novel contrastive learning algorithm and demonstrate its effectiveness in real-world scenarios. The model should be trained and evaluated on benchmark dataset (the Master Thesis could involve also data collection).


**References :books::**

Radford, Alec, et al. "Learning transferable visual models from natural language supervision." arXiv preprint arXiv:2103.00020 (2021). [article](https://arxiv.org/abs/2103.00020)

Chen, Ting, et al. "A simple framework for contrastive learning of visual representations." International conference on machine learning. PMLR, 2020. [article](https://arxiv.org/abs/2002.05709) 

Hosking, T., & Lapata, M. (2021). Factorising Meaning and Form for Intent-Preserving Paraphrasing. arXiv preprint arXiv:2105.15053. [article](https://aclanthology.org/2021.acl-long.112.pdf)

Zhang, Yan, et al. "An unsupervised sentence embedding method by mutual information maximization." arXiv preprint arXiv:2009.12061 (2020). [article](https://arxiv.org/abs/2009.12061)

Lilian Weng - [Contrastive Representation Learning](https://lilianweng.github.io/lil-log/2021/05/31/contrastive-representation-learning.html)

**Interesting projects :computer::**

[solo-learn library](https://github.com/vturrisi/solo-learn)

[TensorFlow Similarity](https://github.com/tensorflow/similarity)



***





### NLP-aided voice cloning <a href="mailto:moreno.laquatra@polito.it,luca.cagliero@polito.it?subject=[Master Thesis] NLP-aided Voice Cloning  - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>
<a href="https://en.wikipedia.org/wiki/Audio_signal_processing"><img src="https://img.shields.io/badge/AP-Audio%20Processing-blue" alt="Audio Processing"></a>

![immagine](https://lh3.googleusercontent.com/XMJlFDtiFU7WtZYnPDMDhT6jTFEXvTpY7c7sY70PtTkzEIDm6DvUv5nvHHwbOrUrDckS34aIu5fiZx0615p1-nf3rFxzhza387ud=w1440)

_image by: https://deepmind.com/blog/article/wavenet-generative-model-raw-audio_

What if you can speak with someone else voice? _Voice imitation_ is usually challenging from an human perspective. It requires both specific training and great voice flexibility. This thesis aims at exploring the intersection of audio and natural language processing domain for the task of voice cloning.

The **main objectives** of this thesis are:

1. Analyze the state-of-the-art voice cloning.
2. Leverage state-of-the-art NLP models.
3. Define a novel approach and demonstrate its effectiveness both using benchmark datasets and real-world data (Master Thesis could involve also data collection).


**References :books::**

Voice Cloning: a Multi-Speaker Text-to-Speech Synthesis Approach based on Transfer Learning [article](https://arxiv.org/abs/2102.05630)

Neural Voice Cloning with a Few Samples [article](https://proceedings.neurips.cc/paper/2018/file/4559912e7a94a9c32b09d894f2bc3c82-Paper.pdf) 

[Blog post](https://towardsdatascience.com/you-can-now-speak-using-someone-elses-voice-with-deep-learning-8be24368fa2b)

**Interesting projects :computer::**

[Real time voice cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)


Graduated Students
============

- Simone Manni (2021) [@simonemanni](https://github.com/simonemanni)
- Sofia Perosin (2021) [@sofiaperosin](https://github.com/sofiaperosin)
