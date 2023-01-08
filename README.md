# Awesome text mining ⛏️ for materials science
A collection of papers on text mining for materials science. **Note: this is a work in progress, I will constantly update this page.**

If you find an interesting paper and would like to add it here, please create a PR request.
## Intersting Papers
- [VisualUrText: A Text Analytics Tool for Unstructured Textual Data](https://iopscience.iop.org/article/10.1088/1742-6596/1018/1/012011):  This tool, VisualUrText, is developed to assist students and researchers for extracting interesting patterns and trends in document analyses.
- [Feature extraction for document text using Latent Dirichlet Allocation](https://iopscience.iop.org/article/10.1088/1742-6596/953/1/012047): feature extraction using kmeans
## Tools and codes

### Plain text

- [spaCy](https://spacy.io): Fast NLP toolkit with pre-built deep learning models for tokenization, NER, POS, dependency parsing, word2vec, etc.
- [textacy](https://github.com/chartbeat-labs/textacy): Pre-/post- processing of text used in conjunction with spaCy, such as text normalization, garbage text cleaning, extraction of ngrams, entities, etc.
- [ChemDataExtractor](http://chemdataextractor.org/): A full-fledged toolkit for sentence segmentation, tokenization, chemical NER, and extracting chemical information.
- []
### PDF files
- [PDFMiner](https://github.com/pdfminer/pdfminer.six): A pure Python implementation of PDF parser.
- [textract](https://textract.readthedocs.io/en/stable/): A bundle of markup-to-plain-text converters including PDF files.

### OCR tools

- [tesseract](https://github.com/tesseract-ocr/tesseract): An open-source C++ OCR tool based on LSTM that supports many languages.
- [Google Cloud OCR](https://cloud.google.com/functions/docs/tutorials/ocr): Google Cloud OCR is highly accurate for books but may suffer from bad recognition accuracy for chemical/materials science symbols and equations.

### Image data extraction
- [ImageDataExtractor: A Tool To Extract and Quantify Data from Microscopy Images by Mukaddem et al](https://doi.org/10.1021/acs.jcim.9b00734): Extract information from microscopy images. The code homepage is [http://www.imagedataextractor.org/](http://www.imagedataextractor.org/).

## Datasets/databases

### On synthesis

- [Machine-learned and codified synthesis parameters of oxide materials by Kim et al](https://doi.org/10.1038/sdata.2017.127): Dataset on syntheses of 30 oxide systems extracted from 76K articles.
- [Text-mined dataset of inorganic materials synthesis recipes by Kononova et al](https://doi.org/10.1038/s41597-019-0224-1): 20K balanced inorganic synthesis reactions and metadata including experimental conditions extracted from 53K articles.
- [Annotating and Extracting Synthesis Process of All-Solid-State Batteries from Scientific Literature by Kuniyoshi et al](https://arxiv.org/abs/2002.07339): NER and dependencies annotated/trained on 243 all-solid-state battery articles.
- [Auto-generated materials database of Curie and Néel temperatures via semi-supervised relationship extraction by Court et al](https://doi.org/10.1038/sdata.2018.111): 40K Curie and Néel temperatures extracted from 68K articles.
- [An open experimental database for exploring inorganic materials by Zakutayev et al](https://doi.org/10.1038/sdata.2018.53): 140K entries on high throughput experimental materials (HTEM) including synthesis conditions, chemical composition, crystal structure, optoelectronic property measurements, etc.

### NLP annotations

- [The Materials Science Procedural Text Corpus: Annotating Materials Synthesis Procedures with Shallow Semantic Structures by Mysore et al](https://arxiv.org/pdf/1905.06939.pdf): 230 annotated synthesis procedures: synthesis operations, arguments, and their relations.

## NLP pipelines

- [Pipelines for Procedural Information Extraction from Scientific Literature: Towards Recipes using Machine Learning and Data Science by Yang et al](https://doi.org/10.1109/ICDARW.2019.10037): A computational information and knowledge management (CIKM) system that extracts preconditions, material inputs, operations, and outputs from literature.

### Named Entity Recognition

- [Named Entity Recognition and Normalization Applied to Large-Scale Information Extraction from the Materials Science Literature by Weston et al](https://doi.org/10.1021/acs.jcim.9b00470): Extract from summaries inorganic material mentions, sample descriptors, phase labels, material properties, applications, and synthesis/characterization methods.
- [Automated Extraction of Chemical Synthesis Actions from Experimental Procedures by Vaucher et al](https://doi.org/10.26434/chemrxiv.11448177.v2): Use rule-based/ML(Transformer) model to extract synthesis actions from experimental procedures.
- [Automatically Extracting Action Graphs from Materials Science Synthesis Procedures by Mysore et al](https://arxiv.org/pdf/1711.06872.pdf): Extraction of synthesis action graphs by combining LSTM, dilated CNN, CRF, and rule-based heuristics.
- [Using Natural Language Processing Techniques to Extract Information on the Properties and Functionalities of Energetic Materials from Large Text Corpora by Elton et al](https://arxiv.org/abs/1903.00415): Use GloVe vectors and word2vec model to extract compounds and assign function/property words for energetic materials corpora.

### Text classification/categorization

- [Semi-supervised machine-learning classification of materials synthesis procedures by Huo et al](https://doi.org/10.1038/s41524-019-0204-1): Identify synthesis paragraphs using LDA and random forest.

## Data analysis

### Synthesis data analysis/planning

- [Materials Synthesis Insights from Scientific Literature via Text Extraction and Machine Learning by Kim et al](https://doi.org/10.1021/acs.chemmater.7b03500): Analysis of synthesis conditions for titania nanotubes extracted from literature.
- [Virtual screening of inorganic materials synthesis parameters with deep learning by Kim et al](https://doi.org/10.1038/s41524-017-0055-6): Use variational autoencoder to encode text and represent synthesis conditions especially for SrTiO3, TiO2, MnO compounds.
- [Inorganic Materials Synthesis Planning with Literature-Trained Neural Networks by Kim et al](https://doi.org/10.1021/acs.jcim.9b00995): Conditional variational autoencoder learning of synthesis actions and predictions for perovskite compounds.

### Chemical knowledge base/graph

- [Unsupervised word embeddings capture latent knowledge from materials science literature by Tshitoyan et al](https://doi.org/10.1038/s41586-019-1335-8): Discover hidden chemistry information using unsupervised word embedding methods, with emphasis on thermoelectric materials.
- [A Relation Aware Search Engine for Materials Science by Shah et al](https://doi.org/10.1007/s40192-017-0105-4): A search engine that indexes information tuples (object, property, value) from articles and allows relational search. (Their data reposited at NIST Materials Data Repository [https://materialsdata.nist.gov/handle/11256/950](https://materialsdata.nist.gov/handle/11256/950)
- [A Bayesian framework for materials knowledge systems by Kalidindi](https://www.cambridge.org/core/journals/mrs-communications/article/bayesian-framework-for-materials-knowledge-systems/8D6C0A4F120682A900A9341021C8B0BA): A Bayesian framework for recommending experimental or simulation parameters using a knowledge base database.
