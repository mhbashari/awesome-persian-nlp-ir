# Awesome Persian NLP/IR, Tools And Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list is curation of the best, not of everything. Please participate in its development.Thanks to [ACL WEB](http://aclweb.org/aclwiki/index.php?title=Resources_for_Persian).
### Contents
 - Tools
    - [Part-of-Speech Tagger](#part-of-speech-tagger)
    - [Language Detection](#language-detection)
    - [Tokenization & Segmentation](#tokenization--segmentation)
    - [Normalizer And Text Cleaner](#normalizer-and-text-cleaner)
    - [Transliterator](#transliterator)
    - [Named Entity Recognition](#named-entity-recognition)
    - [Embeddings](#embeddings)
    - [Morphological Analysis](#morphological-analysis)
    - [Stemmer](#stemmer)
    - [Spell Checking](#spell-checking)
    - [Information Extraction](#spell-checking)
    - [Dependency Parser](#dependency-parser)
    - [Shallow Parser (Chunker)](#shallow-parser)
    - [Text To Speech](#text-to-speech)    
    - [Summerizer](#summerizer)  
    - [Sentiment Analysis](#sentiment-analysis)    
    
 - Data
    - [Part-of-Speech Tagger](#part-of-speech-tagger-1)
    - [Named Entity Recognition](#named-entity-recognition-1)
    - [Dependency Parsing](#dependency-parsing)
    - [Text Categorization and Classification](#text-categorization-and-classification)
    - [Spell Checking](#spell-checking-1)
    - [Persian Poems And Classic Texts](#persian-poems-and-classic-texts)
    - [Machine Tanslation](#machine-tanslation)
    - [Web Collected](#web-collected)
    - [IR Ranking Evaluation](#ir-ranking-evaluation)
    - [IR Crawling And Linking Evaluation](#ir-crawling-and-linking-evaluation)
    - [Stop Word Lists](#stop-word-lists)
    - [Pretrained Models](#pretrained-models)    
    - [Sentiment Analysis](#sentiment-analysis-1)        
    - [MISC](#misc)
    
  - Tutorials
      - [Sentiment Analysis](#sentiment-analysis-2)
  
 - [Papers](#papers)

## Tools

### Part-of-Speech Tagger
 - [farsiNLPTools](https://github.com/wfeely/farsiNLPTools) - Open-source dependency parser, part-of-speech tagger, and text normalizer for Farsi (Persian).
 - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
 - [Persian Language Model for HunPoS](http://stp.lingfil.uu.se/~mojgan/tagper.html) - HunPoS (Halacsy et al, 2007) is an open source reimplementation of the statistical part-of-speech tagger Trigrams'n Tags, also called TnT (Brants, 2000) allowing the user to tune the tagger by using different feature settings.
 - [Maryam Tavafi POS Tagger ](https://sites.google.com/site/maryamtavafi/persian-pos-tagger) - This software includes implementation of a Persian part of speech tagger based on Structured Support Vector Machines.
 - [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.
 - [Persianp Toolbox](http://www.persianp.ir/toolbox.html) - Multi-purpose persian NLP toolbox.
 - [UM-wtlab pos tagger](http://wtlab.um.ac.ir/index.php?option=com_content&view=article&id=326&Itemid=224&lang=en) - This software is a C# implementation of the Viberbi and Brill part-of-speech taggers.
 - [RDRPOSTagger](https://github.com/datquocnguyen/RDRPOSTagger) provides a pre-trained part-of-speech (POS) tagging model for Persian. This POS tagging toolkit is implemented in both Python and Java.
 - [jPTDP](https://github.com/datquocnguyen/jPTDP) provides a pre-trained model for joint POS tagging and dependency parsing for Persian.
 - [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian

### Language Detection
 - [Google language detect (python port)](https://github.com/Mimino666/langdetect) - Light Weight language detector, its performance for persian is excellent.

### Tokenization & Segmentation
  - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
  - [polyglot](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).
  - [tok-tok](https://github.com/jonsafari/tok-tok) - Tok-tok is a fast, simple, multilingual tokenizer(single .pl file).
  - [segmental](https://github.com/jonsafari/segmental) - You can train your model based on plain-text corpus for text segmentation by powerful deep learning platform.
  - [Persian Sentence Segmenter and Tokenizer: SeTPer](http://stp.lingfil.uu.se/~mojgan/setper.html) - Regex based sentence segmenter.
  - [Farsi-Verb-Tokenizer](https://github.com/mehdi-manshadi/Farsi-Verb-Tokenizer) - Tokenizes Farsi Verbs.
  - [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian

### Normalizer And Text Cleaner
  - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
  - [Persian Pre-processor: PrePer](http://stp.lingfil.uu.se/~mojgan/preper.html) - Another signle .pl tools that normals your persian text.
  - [virastar](https://github.com/aziz/virastar) - Cleanning up Persian text!.replace double dash to ndash and triple dash to mdash, replace English numbers with their Persian equivalent, correct :;,.?! spacing (one space after and no space before), replace English percent sign to its Persian equivalent and many other normalization. Virastar is written by ruby and has [python port](https://github.com/JKhakpour/virastar.py).
  - [Virastyar](http://www.virastyar.ir/development) - A collection of C# libraries for Persian text processing (Spell Checking, Purification, Punctuation Correction, Persian Character Standardization, Pinglish Conversion & ...)
  - [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian (Has Half-Space Normalizer and Pinglish Conversion)

### Transliterator
  - [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.

### Named Entity Recognition
### Embeddings
### Morphological Analysis
  - [polyglot](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).


### Stemmer
  - [PersianStemmer](https://github.com/MrHTZ/PersianStemmer-Java/) - ([Java](https://github.com/MrHTZ/PersianStemmer-Java/), [Delphi](https://github.com/MrHTZ/PersianStemmer/),[C#](https://github.com/MrHTZ/PersianStemmer-CSharp/) and [Python](https://github.com/MrHTZ/PersianStemmer-Python/)) - PersianStemmer is a longest-match stemming algorithm that is based on pattern matching. It uses a knowledge base which consist of a collection of rules named "patterns". Furthermore, the exceptions and problems in the Persian morphology have been studied, and a solution is presented for each of them. So our stemmer evaluated. Its result was much better than the previous stemmers.

  - [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.
  - [polyglot](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).
  - [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian

### Sentiment Analysis
  - [polyglot (polarity)](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).


### Spell Checking
  - [async_faspell](https://github.com/eteamin/async_faspell) -Persian spellchecker. An algorithm that suggests words for misspelled words.

### Dependency Parser
  - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
  
### Shallow Parser
  - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
  - [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian

### Information Extraction
  - [baaz](https://github.com/sobhe/information-extraction) - Open information extraction from Persian web.

### Text To Speech
  - [AlisterTA TTS](https://github.com/AlisterTA/Persian-text-to-speech) - A convolutional sequence to sequence model for Persian text to speech based on Tachibana et al with a few modifications.

### Summerizer
  - [Persian-Summarization](https://github.com/minasmz/Persian-Summarization) - Statistical and semantical text summarizer in Persian language
  
## Data
### Part-of-Speech Tagger
  - [Bijankhan Corpus](http://dbrg.ut.ac.ir/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.

  - [Mojgan Seraji Corpus](http://stp.lingfil.uu.se/~mojgan/UPC.html) - Uppsala Persian Corpus (UPC) is a large, freely available Persian corpus. The corpus is a modified version of the Bijankhan corpus with additional sentence segmentation and consistent tokenization containing 2,704,028 tokens and annotated with 31 part-of-speech tags. The part-of-speech tags are listed with explanations in [this table](http://stp.lingfil.uu.se/~mojgan/Table_tag.pdf).

### Named Entity Recognition
  - [ArmanPersoNERCorpus](https://github.com/HaniehP/PersianNER) - The dataset includes 250,015 tokens and 7,682 Persian sentences in total. It is available in 3 folds to be used in turn as training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. Each sentence is separated with a newline. The NER tags are in IOB format.
  - [FarsiYar PersianNER](https://github.com/Text-Mining/Persian-NER) - The dataset includes about 25,000,000 tokens and about 1,000,000 Persian sentences in total based on [Persian Wikipedia Corpus](https://github.com/Text-Mining/Persian-Wikipedia-Corpus). The NER tags are in IOB format. More than 1000 volunteers contributed tag improvements to this dataset via web panel or android app. They release updated tags every two weeks.
 - [Workshop on NLP Solutions for Under Resourced Languages (NSURL) 2019 - Task 7 dataset](http://nsurl.org/tasks/task-7-named-entity-recognition-ner-for-farsi/) - contains a medium size NER corpus with 7 classes of named entities (person, location and organization, money, percent, dates, and time). This corpus contains more than 700 news documents. 

 
### Dependency Parsing
  - [Persian Syntactic Dependency Treebank](http://dadegan.ir/catalog/perdt) - This treebank is supplied for free noncommercial use. For commercial uses feel free to contact us. The number of annotated sentences is 29,982 sentences including samples from almost all verbs of the Persian valency lexicon.
  - [Uppsala Persian Dependency Treebank: UPDT](http://stp.lingfil.uu.se/~mojgan/UPDT.html) - Dependency-based syntactically annotated corpus.
   - [Pretrained model](http://stp.lingfil.uu.se/~mojgan/parsper-mate.html)
  - [Universal Dependencies 1.3](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1699) - Multi lingual corpus that holds IOB gold data for dependency parsing
  - [HamleDT 3.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508) - HArmonized Multi-LanguagE Dependency Treebank is a compilation of existing dependency treebanks (or dependency conversions of other treebanks), transformed so that they all conform to the same annotation style. This version uses Universal Dependencies as the common annotation style.

### Text Categorization and Classification
  - [Hamshahri](http://dbrg.ut.ac.ir/Hamshahri/download.html) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.
  - [Bijankhan Corpus](http://dbrg.ut.ac.ir/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.

### Spell Checking
- [FAspell](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-1547) - FASpell dataset was developed for the evaluation of spell checking algorithms. It contains a set of pairs of misspelled Persian words and their corresponding corrected forms similar to the ASpell dataset used for English.
- [Persian-Spell-checker](https://github.com/reza1615/Persian-Spell-checker) - We're collecting persian words' dictionary (verbs, nouns, and etc.) for Persian spell checker.

### Persian Poems And Classic Texts
- [Farsi Poem Corpus](https://github.com/amnghd/Persian_poems_corpus) - This corpus consists of text documents for 48 Persian poets. The corpus comes in three formats; original, normalized (only 32 main Farsi alphabet), and stop words removed. The corpus consists of 1,216,286 mesras of Farsi poems and 8,102,119 words from which 148,588 are unique.

### Sentiment Analysis
  - [NRC-Persian-Lexicon](https://github.com/mhbashari/NRC-Persian-Lexicon) - NRC Word-Emotion Association Lexicon useful for persian sentiment analysis.
### Machine Tanslation
#### Parallel Corpus
  - [TEP: Tehran English-Persian Parallel Corpus](http://ece.ut.ac.ir/node/100869?destination=node%2F100869) - First free English-Persian corpus.
  - [OPUS: the open parallel corpus](http://opus.lingfil.uu.se/) - OPUS is a growing collection of translated texts from the web. In the OPUS project we try to convert and align free online data, to add linguistic annotation, and to provide the community with a publicly available parallel corpus. OPUS is based on open source products and the corpus is also delivered as an open content package. We used several tools to compile the current collection. All pre-processing is done automatically. No manual corrections have been carried out.

#### Monolingual Corpus
 - [TMC: Tehran Monolingual Corpus](http://ece.ut.ac.ir/en/node/940) - The Tehran Monolingual Corpus (TMC) is a large-scale Persian monolingual corpus. TMC is suited for Language Modeling and relevant research areas in Natural Language Processing. The corpus is extracted from Hamshahri Corpus and ISNA news agency website. The quality of Hamshahri corpus is improved for language modeling purpose by a series of tokenization and spell-checking steps.
 - [VOA Persian Corpus](http://jon.dehdari.org/corpora/#persian) - A medium-sized corpus of 7.9 million words, 2003-2008.  The corpus is in the public domain, so no copyright restrictions.

#### Comparable Corpus

### Web Collected
  - [W2C – Web to Corpus – Corpora](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) - A set of corpora for 120 languages automatically collected from wikipedia and the web.
  - [dotIR Collection](http://ece.ut.ac.ir/DBRG/webir/) - dotIR is a standard Persian test collection that is suitable for evaluation of web information retrieval algorithms in Iranian web.dotIR Contains many Persian web pages including their text, links, metadata, etc that are stored in XML format. It is prepared in such a way to be a good representative of Iranian web.It is A good test bed for evaluation of link based information retrieval algorithms. It includes enough Queries and relevance judgments for a valid evaluation.It is not very large, so that it does not require high processing resources.

### IR Ranking Evaluation
  - [Hamshahri](http://dbrg.ut.ac.ir/Hamshahri/download.html) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.

### IR Crawling And Linking Evaluation
  - [dotIR Collection](http://ece.ut.ac.ir/DBRG/webir/) - dotIR is a standard Persian test collection that is suitable for evaluation of web information retrieval algorithms in Iranian web.dotIR Contains many Persian web pages including their text, links, metadata, etc that are stored in XML format. It is prepared in such a way to be a good representative of Iranian web.It is A good test bed for evaluation of link based information retrieval algorithms. It includes enough Queries and relevance judgments for a valid evaluation.It is not very large, so that it does not require high processing resources.

### Pretrained Models
  - [Farsi Poem word2vec model](https://github.com/amnghd/Word2vec-on-Farsi-Literature) - This is a word2vec model deveoped based on a corpus of 48 Persian poets. The corpus consists of 1,216,286 mesras of Farsi poems and 8,102,119 words from which 148,588 are unique.
  
### Stop Word Lists
  - [Persian stopwords collection](https://github.com/ziaa/Persian-stopwords-collection) - A collection of Persian stop words list
  - [Hazm stop words](https://github.com/sobhe/hazm/blob/master/hazm/data/stopwords.dat) - Stop words list, good for IR.
  - [mhbashari stopword list](https://github.com/mhbashari/awesome-persian-nlp-ir/blob/master/stopwords.txt) - Experimental list of stopwords that is suitable for topic modelling and word embedding.
  - [Persian, Arabic and English stopwords](http://www.mojiry.ir/text_tools/WordFrequencePage.php) - A collection of stopwords on three languages.

### MISC
  - [PersianStemmingDataset](https://github.com/MrHTZ/PersianStemmingDataset) - PersianStemmingDataset is consist of two manually stemmed persian corpora and an evalution tools in order to compute stemming evaluatin metrics.
  - [PersPred](http://perspred.cnrs.fr/perspred-project) - PersPred, is the first online multilingual syntactic and semantic database of Persian compound verbs (complex predicates), developed by the members of the research unit Mondes iranien et indien (CNRS, Sorbonne Nouvelle, Inalco, EPHE) within the ANR-DFG project PERGRAM (2008-2012) and the LR4.1 work package of the Strand 6 of the Labex Empirical Foundations of Linguistics (EFL).
  - [ACL-Wiki Resources for Persian](http://www.aclweb.org/aclwiki/index.php?title=Resources_for_Persian) - Another list of resources for Persian computing.
  - [petit](https://github.com/JKhakpour/petit) - Convert alphabet-written numbers to digit-form

## Tutorials
### Sentiment Analysis
  - [Persian Sentiment Analysis](https://github.com/ashalogic/Persian-Sentiment-Analyzer) - Persian sentiment analysis ( آناکاوی سهش های فارسی | تحلیل احساسات فارسی ) is a simple ready to use project that use Python to create the model and Also it's include a very good IPython Tutorial.
  
## Papers
  - [Sentiment Analysis Challenges in Persian Language](https://arxiv.org/pdf/1907.04407)
  - [Comparative Study of Various Persian Stemmers in the Field of Information Retrieval ](http://jips.jatsxml.org/upload/pdf/jips-11-3-450.pdf)
  - [On the Importance of Ezafe Construction in Persian Parsing](https://www.aclweb.org/anthology/P/P15/P15-2144.pdf)

  - [A New Hybrid Stemming Method for Persian Language](http://dsh.oxfordjournals.org/content/early/2015/11/06/llc.fqv053) [(link2)](http://dx.doi.org.sci-hub.cc/10.1093/llc/fqv053)
  - [Sentiment analysis using deep learning on Persian texts](http://ieeexplore.ieee.org/document/7985281/) [(PDF Link)](http://bayanbox.ir/info/1313132063660147282/roshanfekr2017) 

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
