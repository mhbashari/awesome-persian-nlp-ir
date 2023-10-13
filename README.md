# Awesome Persian NLP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list of tools and research related to Persian NLP.

## Contents
- [Tools](#tools)
- [Datasets](#datasets)
- [Models](#models)
- [Repositories](#repositories)
- [Papers and Books](#papers-and-books)

## Tools

### Part-of-Speech Tagger
- [farsiNLPTools](https://github.com/wfeely/farsiNLPTools) - Open-source dependency parser, part-of-speech tagger, and text normalizer for Farsi (Persian).
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.
- [Persian Language Model for HunPoS](http://stp.lingfil.uu.se/~mojgan/tagper.html) - HunPoS (Halacsy et al, 2007) is an open source reimplementation of the statistical part-of-speech tagger Trigrams'n Tags, also called TnT (Brants, 2000) allowing the user to tune the tagger by using different feature settings.
- [Maryam Tavafi POS Tagger ](https://sites.google.com/site/maryamtavafi/persian-pos-tagger) - This software includes implementation of a Persian part of speech tagger based on Structured Support Vector Machines.
- [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.
- [Persianp Toolbox](http://www.persianp.ir/toolbox.html) - Multi-purpose persian NLP toolbox.
- [UM-wtlab pos tagger](http://wtlab.um.ac.ir/index.php?option=com_content&view=article&id=326&Itemid=224&lang=en) - This software is a C# implementation of the Viberbi and Brill part-of-speech taggers.
- [RDRPOSTagger](https://github.com/datquocnguyen/RDRPOSTagger) - Provides a pre-trained part-of-speech (POS) tagging model for Persian. This POS tagging toolkit is implemented in both Python and Java.
- [jPTDP](https://github.com/datquocnguyen/jPTDP) - Provides a pre-trained model for joint POS tagging and dependency parsing for Persian.
- [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian.

### Language Detection
- [Google language detect (python port)](https://github.com/Mimino666/langdetect) - Light Weight language detector, its performance for persian is excellent.

### Tokenization & Segmentation
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.
- [polyglot](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).
- [tok-tok](https://github.com/jonsafari/tok-tok) - Tok-tok is a fast, simple, multilingual tokenizer(single .pl file).
- [segmental](https://github.com/jonsafari/segmental) - You can train your model based on plain-text corpus for text segmentation by powerful deep learning platform.
- [Persian Sentence Segmenter and Tokenizer: SeTPer](http://stp.lingfil.uu.se/~mojgan/setper.html) - Regex based sentence segmenter.
- [Farsi-Verb-Tokenizer](https://github.com/mehdi-manshadi/Farsi-Verb-Tokenizer) - Tokenizes Farsi Verbs.
- [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian.
- [ParsiAnalyzer](https://github.com/NarimanN2/ParsiAnalyzer) -  Persian Analyzer For Elasticsearch.
- [ParsiNorm](https://github.com/haraai/ParsiNorm) - Persain Text Pre-Proceesing Tool.
- [Persian Tools](https://github.com/persian-tools/py-persian-tools) - An anthology of a variety of tools for the Persian language in Python.

### Normalizer And Text Cleaner
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.
- [Persian Pre-processor: PrePer](http://stp.lingfil.uu.se/~mojgan/preper.html) - Another signle .pl tools that normals your persian text.
- [virastar](https://github.com/aziz/virastar) - Cleaning up Persian text!.replace double dash to ndash and triple dash to mdash, replace English numbers with their Persian equivalent, correct :;,.?! spacing (one space after and no space before), replace English percent sign to its Persian equivalent and many other normalization. Virastar is written by ruby and has [python port](https://github.com/JKhakpour/virastar.py).
- [Virastyar](http://www.virastyar.ir/development) - A collection of C# libraries for Persian text processing (Spell Checking, Purification, Punctuation Correction, Persian Character Standardization, Pinglish Conversion & ...).
- [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian (Has Half-Space Normalizer and Pinglish Conversion).
- [ParsiAnalyzer](https://github.com/NarimanN2/ParsiAnalyzer) -  Persian Analyzer For Elasticsearch.
- [ParsiNorm](https://github.com/haraai/ParsiNorm) - Persain Text Pre-Proceesing Tool.
- [Persian Tools](https://github.com/persian-tools/py-persian-tools) - An anthology of a variety of tools for the Persian language in Python.

### Translator
- [SPL](https://github.com/stanford-oval/SPL) - Semantic Parser Localizer toolkit can be used to translate text between any language pairs for which an NMT model exists. We currently support [Marian](https://github.com/marian-nmt/marian) models and Google Translate. In general, for translations to or from Persian, Google Translate has higher quality.

### Transliterator
- [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.

### Morphological Analysis
- [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).

### Stemmer
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.
- [PersianStemmer](https://github.com/MrHTZ/PersianStemmer-Java/) - ([Java](https://github.com/MrHTZ/PersianStemmer-Java/), [Delphi](https://github.com/MrHTZ/PersianStemmer/),[C#](https://github.com/MrHTZ/PersianStemmer-CSharp/) and [Python](https://github.com/MrHTZ/PersianStemmer-Python/)) - PersianStemmer is a longest-match stemming algorithm that is based on pattern matching. It uses a knowledge base which consist of a collection of rules named "patterns". Furthermore, the exceptions and problems in the Persian morphology have been studied, and a solution is presented for each of them. So our stemmer evaluated. Its result was much better than the previous stemmers.
- [Perstem](https://github.com/jonsafari/perstem) - Perstem is a Persian (Farsi) stemmer, morphological analyzer, transliterator, and partial part-of-speech tagger. Inflexional morphemes are separated or removed from their stems. Perstem can also tokenize and transliterate between various character set encodings and romanizations.
- [polyglot](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).
- [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian.
- [ParsiAnalyzer](https://github.com/NarimanN2/ParsiAnalyzer) -  Persian Analyzer For Elasticsearch.

### Sentiment Analysis
- [polyglot (polarity)](https://github.com/aboSamoor/polyglot) -  Natural language pipeline that supports massive multilingual applications (like lokenization (165 languages), language detection (196 languages), named entity recognition (40 languages), part of speech tagging (16 languages), sentiment analysis (136 languages), word embeddings (137 languages), morphological analysis (135 languages), transliteration (69 Languages)).

### Spell Checking
- [async_faspell](https://github.com/eteamin/async_faspell) - Persian spellchecker. An algorithm that suggests words for misspelled words.

### Dependency Parser
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.

### Shallow Parser
- [Hazm](https://github.com/roshan-research/hazm) - Persian NLP Toolkit.
- [Parsivar](https://github.com/ICTRC/Parsivar) - A Language Processing Toolkit for Persian.

### Information Extraction
- [Baaz](https://github.com/sobhe/information-extraction) - Open information extraction from Persian web.

### Text To Speech Preprocessing
- [ParsiNorm](https://github.com/haraai/ParsiNorm) - Persain Text Pre-Proceesing Tool.
- [Persian Tools](https://github.com/persian-tools/py-persian-tools) - An anthology of a variety of tools for the Persian language in Python.

### Text To Speech
- [AlisterTA TTS](https://github.com/AlisterTA/Persian-text-to-speech) - A convolutional sequence to sequence model for Persian text to speech based on Tachibana et al with a few modifications.

### Persian Phonemizer
- [persian_phonemizer](https://github.com/de-mh/persian_phonemizer) - A tool for translating Persian text to IPA (International Phonetic Alphabet).

### MISC
- [petit](https://github.com/JKhakpour/petit) - Convert alphabet-written numbers to digit-form.

### Keyphrase Extractor
- [Perke](https://github.com/AlirezaTheH/perke) - Perke is a Python keyphrase extraction package for Persian language. It provides an end-to-end keyphrase extraction pipeline in which each component can be easily modified or extended to develop new models.

### Speech Recognition
- [Vosk](https://github.com/alphacep/vosk-api) - Vosk is an offline open source speech recognition toolkit. It enables speech recognition for 20+ languages and dialects. Supports Persian.
- [m3hrdadfi/wav2vec](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3) - Persian speech recognition model based on XLS-R.

### Metrics
- [Rouge](https://pypi.org/project/rouge/) - Full Python ROUGE Score Implementation (not a wrapper).

## Datasets

### Part-of-Speech Tagger
- [Bijankhan Corpus](https://dbrg.ut.ac.ir/%D8%A8%DB%8C%DA%98%D9%86%E2%80%8C%D8%AE%D8%A7%D9%86) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.
- [Mojgan Seraji Corpus](http://stp.lingfil.uu.se/~mojgan/UPC.html) - Uppsala Persian Corpus (UPC) is a large, freely available Persian corpus. The corpus is a modified version of the Bijankhan corpus with additional sentence segmentation and consistent tokenization containing 2,704,028 tokens and annotated with 31 part-of-speech tags. The part-of-speech tags are listed with explanations in [this table](http://stp.lingfil.uu.se/~mojgan/Table_tag.pdf).
- [Large-Scale Colloquial Persian](http://hdl.handle.net/11234/1-3195) - Large Scale Colloquial Persian Dataset (LSCP) is hierarchically organized in asemantic taxonomy that focuses on multi-task informal Persian language understanding as a comprehensive problem. LSCP includes 120M sentences from 27M casual Persian tweets with its dependency relations in syntactic annotation, Part-of-speech tags, sentiment polarity and automatic translation of original Persian sentences in English (EN), German (DE), Czech (CS), Italian (IT) and Hindi (HI) spoken languages. Learn more about this project at [LSCP webpage](https://iasbs.ac.ir/~ansari/lscp/).

### Named Entity Recognition
- [ArmanPersoNERCorpus](https://github.com/HaniehP/PersianNER) - The dataset includes 250,015 tokens and 7,682 Persian sentences in total. It is available in 3 folds to be used in turn as training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. Each sentence is separated with a newline. The NER tags are in IOB format.
- [FarsiYar PersianNER](https://github.com/Text-Mining/Persian-NER) - The dataset includes about 25,000,000 tokens and about 1,000,000 Persian sentences in total based on [Persian Wikipedia Corpus](https://github.com/Text-Mining/Persian-Wikipedia-Corpus). The NER tags are in IOB format. More than 1000 volunteers contributed tag improvements to this dataset via web panel or android app. They release updated tags every two weeks.
- [Workshop on NLP Solutions for Under Resourced Languages (NSURL) 2019 - Task 7 dataset](http://nsurl.org/tasks/task-7-named-entity-recognition-ner-for-farsi/) - contains a medium size NER corpus with 7 classes of named entities (person, location and organization, money, percent, dates, and time). This corpus contains more than 700 news documents.

### Relation Extraction
- [PERLEX](http://farsbase.net/PERLEX.html) - The first Persian dataset for relation extraction, which is an expert translated version of the “Semeval-2010-Task-8” dataset. Link to [the relevant publication](https://arxiv.org/pdf/2005.06588.pdf).

### Dependency Parsing
- [Persian Syntactic Dependency Treebank](http://dadegan.ir/catalog/perdt) - This treebank is supplied for free noncommercial use. For commercial uses feel free to contact us. The number of annotated sentences is 29,982 sentences including samples from almost all verbs of the Persian valency lexicon.
- [Uppsala Persian Dependency Treebank: UPDT](http://stp.lingfil.uu.se/~mojgan/UPDT.html) - Dependency-based syntactically annotated corpus.
- [Pretrained model](http://stp.lingfil.uu.se/~mojgan/parsper-mate.html).
- [Universal Dependencies 1.3](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1699) - Multi lingual corpus that holds IOB gold data for dependency parsing
- [HamleDT 3.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508) - HArmonized Multi-LanguagE Dependency Treebank is a compilation of existing dependency treebanks (or dependency conversions of other treebanks), transformed so that they all conform to the same annotation style. This version uses Universal Dependencies as the common annotation style.
- [Large-Scale Colloquial Persian](http://hdl.handle.net/11234/1-3195) - Large Scale Colloquial Persian Dataset (LSCP) is hierarchically organized in asemantic taxonomy that focuses on multi-task informal Persian language understanding as a comprehensive problem. LSCP includes 120M sentences from 27M casual Persian tweets with its dependency relations in syntactic annotation, Part-of-speech tags, sentiment polarity and automatic translation of original Persian sentences in English (EN), German (DE), Czech (CS), Italian (IT) and Hindi (HI) spoken languages. Learn more about this project at [LSCP webpage](https://iasbs.ac.ir/~ansari/lscp/).
- [MULTEXT-East](https://www.clarin.si/repository/xmlui/handle/11356/1042) - The MULTEXT-East morphosyntactic lexicons have a simple structure, where each line is a lexical entry with three tab-separated fields: (1) the word-form, the inflected form of the word; (2) the lemma, the base-form of the word; (3) the MSD, the morphosyntactic description of the word-form, i.e., its fine-grained PoS tag, as defined in the MULTEXT-East morphosyntactic specifications.

### Text Categorization and Classification
- [Hamshahri](http://dbrg.ut.ac.ir/Hamshahri/download.html) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.
- [Bijankhan Corpus](http://dbrg.ut.ac.ir/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.
- [Digikala Magazine (DigiMag)](https://hooshvare.github.io/docs/datasets/tc#digikala-magazine-digimag) - A total of 8,515 articles scraped from Digikala Online Magazine. This dataset includes seven different classes `Video Games`, `Shopping Guide`, `Health Beauty`, `Science Technology`, `General`, `Art Cinema`, and `Books Literature`.
- [Persian News](https://hooshvare.github.io/docs/datasets/tc#persian-news) - A dataset of various news articles scraped from different online news agencies’ websites. The total number of articles is 16,438, spread over eight different classes, `Economic`, `International`, `Political`, `Science Technology`, `Cultural Art`, `Sport`, and `Medical`.

### Spell Checking
- [FAspell](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-1547) - FASpell dataset was developed for the evaluation of spell checking algorithms. It contains a set of pairs of misspelled Persian words and their corresponding corrected forms similar to the ASpell dataset used for English.
- [Persian-Spell-checker](https://github.com/reza1615/Persian-Spell-checker) - We're collecting persian words' dictionary (verbs, nouns, and etc.) for Persian spell checker.
- [Grammar and context sensitive spell checker](https://ece.ut.ac.ir/web/nlp/resources) - It is a real-world test set for grammatical errors and context sensitive spelling errors for Persian language. This test set contains 1100 context sensitive errors and was collected from Persian Blogs.
- [Spell Checker](https://ece.ut.ac.ir/web/nlp/resources) - Test set for spelling errors for Persian language.​
- [CPG: Corpus of Persian Grammatical Errors](https://ece.ut.ac.ir/web/nlp/resources) - It  is a fully-annotated corpus of grammatical errors collected from 700 essays written by learners of Persian language in *Dehkhoda Lexicon Institute & International Centre for Persian Studies and Imam Khomeini International University*.
- [PerSpellData](https://github.com/rominaoji/PerSpellData) - Comprehensive parallel dataset for persian non-word and real-word errors.
- [HeKasre](https://github.com/AUT-Data-Group/HeKasre) - Detect and correct misspelled "e" sound in Persian (aka Farsi) writing (especially in an informal setting).
- [Lilak](https://github.com/b00f/lilak) - Persian Spell Checking Dictionary.

### Textual Entailment
- [FarsTail](https://github.com/dml-qom/FarsTail) -  FarsTail is a dataset of textual entailment (also known as natural language inference, NLI) and it includes 10,367 samples in the Persian language. Here is [the relevant paper](https://arxiv.org/pdf/2009.08820.pdf).

### Textual Thematic Similarity
- [Wikipedia Section Sentences](https://github.com/m3hrdadfi/sentence-transformers) - It implements the idea from Dor et al., 2018, [Learning Thematic Similarity Metric Using Triplet Networks](https://www.aclweb.org/anthology/P18-2009/) for Persian. The dataset includes 205,768 examples that covered 21,515 articles and 34,298 sections.
- [Wiki Triplet](https://github.com/m3hrdadfi/sentence-transformers) -  A triplet-objective dataset extracted from ***Wikipedia Section Sentences*** into a triplet-form of anchor (<img src="https://render.githubusercontent.com/render/math?math=a">), positive (<img src="https://render.githubusercontent.com/render/math?math=p">) and negative (<img src="https://render.githubusercontent.com/render/math?math=n">) examples. It covers 191,929 samples.
- [Wiki D-Similar](https://github.com/m3hrdadfi/sentence-transformers) -  Wiki D-Similar is another form of thematic similarity dataset with 137,402 records that tags pairs of sentences into a form of similar or dissimilar.

### Persian Poems And Classic Texts
- [Farsi Poem Corpus](https://github.com/amnghd/Persian_poems_corpus) - This corpus consists of text documents for 48 Persian poets. The corpus comes in three formats; original, normalized (only 32 main Farsi alphabet), and stop words removed. The corpus consists of 1,216,286 mesras of Farsi poems and 8,102,119 words from which 148,588 are unique.

### Sentiment Analysis
- [NRC-Persian-Lexicon](https://github.com/mhbashari/NRC-Persian-Lexicon) - NRC Word-Emotion Association Lexicon useful for persian sentiment analysis.
- [Digikala OpenData Sentiment](https://www.digikala.com/opendata/#section-4) - data contains 100,000 samples of users' comments in favor of products labeled as `no_idea`, `not_recommended `, and `recommended `.
- [Pars-ABSA](https://github.com/Titowak/Pars-ABSA) - Manually annotated Persian dataset, verified by 3 native Persian speakers. The dataset consists of 5,114 positive, 3,061 negative and 1,827 neutral data samples from 5,602 unique reviews.
- [PerSent](https://www.gelbukh.com/resources/persent/) - This dataset presents real-valued polarity labels, in the range from -1 to 1, for thousands of Persian words and expressions.
- [DeepSentiPers](https://github.com/JoyeBright/DeepSentiPers) - Novel Deep Learning Models Trained Over Proposed Augmented Persian Sentiment Corpus
- [SentiPers](https://github.com/phosseini/sentipers) -  Documents in SentiPers are manually annotated at different levels.
- [LexiPers](https://github.com/phosseini/lexipers) - An ontology based sentiment lexicon for Persian.
- [SnappFood](https://hooshvare.github.io/docs/datasets/sa#snappfood) - Snappfood (an online food delivery company) user comments containing 70,000 comments with two labels (i.e. polarity classification), `Happy` and `Sad`.
- [MirasOpinion](https://github.com/miras-tech/MirasText/tree/master/MirasOpinion) - This repository contains information about MirasOpinion dataset, which is the largest Persian sentiment analysis dataset up to this date, alongside a demo file which contains 20 documents with their corresponding labels.
- [EmoPars](https://github.com/nazaninsbr/Persian-Emotion-Detection) - A Collection of 30K Emotion-Annotated Persian Social MediaTexts.
- [ArmanEmo](https://github.com/Arman-Rayan-Sharif/arman-text-emotion) - A non-commercial version of ArmanEMO,A high quality human-labeled emotion dataset of more than 7000 Persian sentences labeled for seven categories, Labels are based on Ekman's six basic emotions (Anger, Fear, Happiness, Hatred, Sadness, Wonder) and another category (Other).
- [Persian tweets emotional dataset](https://www.kaggle.com/datasets/behdadkarimi/persian-tweets-emotional-dataset).

### Summarization
- [Wiki Summary](https://github.com/m3hrdadfi/wiki-summary) - Wiki Summary is a summarization dataset extracted from Persian Wikipedia into the form of articles and highlights.


### Question Answering
- [PersianQA](https://github.com/sajjjadayobi/PersianQA) - Persian Question Answering (PersianQA) Dataset is a reading comprehension dataset on Persian Wikipedia. The crowd-sourced dataset consists of more than 9,000 entries. Each entry can be either an impossible-to-answer or a question with one or more answers spanning in the passage (the context) from which the questioner proposed the question. Much like the SQuAD2.0 dataset, the impossible or unanswerable questions can be utilized to create a system which "knows that it doesn't know the answer".
- [ParsVQA-Caps](https://www.kaggle.com/datasets/af4f893668e3aef3610b813604b366eeecd26177aa105581c85fd4dd7ac5aa51) - A Benchmark for Visual Question Answering and Image Captioning in Persian.
- [MeDiaPQA](https://data.mendeley.com/datasets/k7tzmrhr6n/1) - A Question-Answering Dataset on Persian Medical Dialogues
- [Persian QA Wikipedia](https://www.kaggle.com/datasets/amirpourmand/persian-qa-wikipedia) - A Question Anwering Dataset on wikipedia paragraphs.

### Irony - Insult
- [MirasIrony](https://github.com/miras-tech/MirasText/tree/master/MirasIrony) - The irony dataset is constructed from Persian tweets. 2942 tweets are labeled in total.

### Corpus
- [TEP: Tehran English-Persian Parallel Corpus](https://ece.ut.ac.ir/web/nlp/resources) - First free English-Persian corpus.
- [OPUS: the open parallel corpus](http://opus.lingfil.uu.se/) - OPUS is a growing collection of translated texts from the web. In the OPUS project we try to convert and align free online data, to add linguistic annotation, and to provide the community with a publicly available parallel corpus. OPUS is based on open source products and the corpus is also delivered as an open content package. We used several tools to compile the current collection. All pre-processing is done automatically. No manual corrections have been carried out.
- [Tanzil project](http://opus.nlpl.eu/Tanzil.php) - Tanzil project is a collection of Quran translations to many languages, including Persian.
- [Large-Scale Colloquial Persian](http://hdl.handle.net/11234/1-3195) - Large Scale Colloquial Persian Dataset (LSCP) is hierarchically organized in asemantic taxonomy that focuses on multi-task informal Persian language understanding as a comprehensive problem. LSCP includes 120M sentences from 27M casual Persian tweets with its dependency relations in syntactic annotation, Part-of-speech tags, sentiment polarity and automatic translation of original Persian sentences in English (EN), German (DE), Czech (CS), Italian (IT) and Hindi (HI) spoken languages. Learn more about this project at [LSCP webpage](https://iasbs.ac.ir/~ansari/lscp/).
- [MIZAN](https://github.com/omidkashefi/Mizan) -  a Persian-English parallel corpus with about 1 million sentence pairs collected from masterpieces of literature. [Here](https://arxiv.org/pdf/1801.02107.pdf) is the relevant paper.
- [PEPC: Parallel English-Persian Corpus Extracted from Wikipedia](https://iasbs.ac.ir/~ansari/nlp/pepc.html) - a collection of parallel sentences in English and Persian languages extracted from Wikipedia documents using a bidirectional translation method.
- [Bible corpus](https://github.com/christos-c/bible-corpus) - A multilingual parallel corpus created from translations of the Bible. The corpus also contains a Persian Bibble.
- [Transliteration](https://ece.ut.ac.ir/web/nlp/resources) - Transliteration extracted from a Persian novel book which written in both Arabic and Dabire. According to the first and last words of each sentence, we manually aligned the sentences of this book. Then for checking and eliminating the errors, the length of the sentences in both sides was compared. Finally, our parallel corpus with 13933 sentence pairs, 155623 words in Persian text and 170702 Dabire words was created.
- [TMC: Tehran Monolingual Corpus](https://ece.ut.ac.ir/web/nlp/resources) - The Tehran Monolingual Corpus (TMC) is a large-scale Persian monolingual corpus. TMC is suited for Language Modeling and relevant research areas in Natural Language Processing. The corpus is extracted from Hamshahri Corpus and ISNA news agency website. The quality of Hamshahri corpus is improved for language modeling purpose by a series of tokenization and spell-checking steps.
- [VOA Persian Corpus](http://jon.dehdari.org/corpora/#persian) - A medium-sized corpus of 7.9 million words, 2003-2008.  The corpus is in the public domain, so no copyright restrictions.
- [MirasText](https://github.com/miras-tech/MirasText): Automatically Extracted Text Persian Corpus (about 12GB).
- [A large collection of Persian raw text](https://github.com/persiannlp/persian-raw-text) - About **80GB** Persian raw text, collected from a variety of sources, particularly CommonCrawl.
- [W2C – Web to Corpus – Corpora](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) - A set of corpora for 120 languages automatically collected from wikipedia and the web.
- [dotIR Collection](http://ece.ut.ac.ir/DBRG/webir/) - dotIR is a standard Persian test collection that is suitable for evaluation of web information retrieval algorithms in Iranian web.dotIR Contains many Persian web pages including their text, links, metadata, etc that are stored in XML format. It is prepared in such a way to be a good representative of Iranian web.It is A good test bed for evaluation of link based information retrieval algorithms. It includes enough Queries and relevance judgments for a valid evaluation.It is not very large, so that it does not require high processing resources.
- [Hamshahri](http://dbrg.ut.ac.ir/Hamshahri/download.html) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.
- [Prallel Gold Data from Wikipedia](https://ece.ut.ac.ir/web/nlp/resources) - This dataset contains parallel sentences, which are tagged from 33 wikipedia pages.
- [PREDICT](https://github.com/AUT-Data-Group/PREDICT-Persian-Reverse-Dictionary) - Persian REverse DICTionary.
- [Iranian politicians twitter dataset persian](https://github.com/miladfa7/Iranian-politicians-twitter-dataset-persian).
- [iPerUDT](https://github.com/royakabiri/iPerUDT) - Informal Persian Universal Dependency Treebank.
- [Tasnim News](https://www.kaggle.com/datasets/amirpourmand/tasnimdataset) - Tasnim news dataset.
- [Asriran News](https://www.kaggle.com/datasets/amirpourmand/asriran-news) - Asriran news dataset.
- [Isna News Agency](https://www.kaggle.com/datasets/amirpourmand/isna-news) - Isna news agency dataset.
- [Ensani.ir Abstrats](https://www.kaggle.com/datasets/amirpourmand/ensani-abstracts) - Abstracts extracted from ensani.ir.
- [Tarjoman Articles](https://www.kaggle.com/datasets/amirpourmand/tarjoman-persian-text) - Extracted Tarjoman Articles.

### Stop Word Lists
- [Persian stopwords collection](https://github.com/ziaa/Persian-stopwords-collection) - A collection of Persian stop words list.
- [Hazm stop words](https://github.com/sobhe/hazm/blob/master/hazm/data/stopwords.dat) - Stop words list, good for IR.
- [mhbashari stopword list](https://github.com/mhbashari/awesome-persian-nlp-ir/blob/master/stopwords.txt) - Experimental list of stopwords that is suitable for topic modelling and word embedding.
- [Persian, Arabic and English stopwords](http://www.mojiry.ir/text_tools/WordFrequencePage.php) - A collection of stopwords on three languages.
- [Pers_Word](https://github.com/mohamad-dehghani/Semi-automatic-Detection-of-Persian-Stopwords-using-FastText-Library-/blob/main/pers_word.txt) - Persian stopwords generated with fastText.
- [Persian Swear Words](https://github.com/amirshnll/Persian-Swear-Words) -  This is a to-be-complete list of Persian Swears you can use in your production to filter unwanted content. Wordlist is available in JSON format.

### Knowledge Bases
- [FarsBase](http://farsbase.net/about) -  FarsBase the first Persian multi-source knowledge graph, which isspecifically designed for semantic search engines to support Persian knowledge. FarsBase uses a diverse set of hybrid and flexible techniques to extract and integrate knowledge from various sources, such as Wikipedia, Web tables and unstructured texts. Here is [the relevant paper](http://www.semantic-web-journal.net/system/files/swj2210.pdf).

### Intent Detection & Slot filling
- [Persian-ATIS](https://github.com/Makbari1997/Persian-Atis) - A Persian Benchmark for Joint Intent Detection and Slot Filling.

### Paraphrasing
- [ExaPPC](https://github.com/exaco/exappc) - A Large-Scale Persian Paraphrase Detection Corpus.

### Text-to-Speech(TTS)
- [A farsi to finglish dataset](https://github.com/rowshanattar/persian-text-to-speech/blob/main/sub-test.csv).

### MISC
- [ParsiNLU](https://github.com/persiannlp/parsinlu) - A collection natural language understanding datasets for Persian. [Here is the relevant paper.](https://arxiv.org/abs/2012.06154).
- [PersianStemmingDataset](https://github.com/MrHTZ/PersianStemmingDataset) - PersianStemmingDataset is consist of two manually stemmed persian corpora and an evalution tools in order to compute stemming evaluatin metrics.
- [PersPred](http://perspred.cnrs.fr/perspred-project) - PersPred, is the first online multilingual syntactic and semantic database of Persian compound verbs (complex predicates), developed by the members of the research unit Mondes iranien et indien (CNRS, Sorbonne Nouvelle, Inalco, EPHE) within the ANR-DFG project PERGRAM (2008-2012) and the LR4.1 work package of the Strand 6 of the Labex Empirical Foundations of Linguistics (EFL).
- [Popularity Prediction](https://ece.ut.ac.ir/web/nlp/resources) - It is Tabnak and Alef Datasets which are the most famous online news agencies in Iran. This dataset includes content, title, date, category and number of comments per each news. Besides popularity of these websites, the wide range of news categories they cover and they have the multilevel commenting structure.
- [Conversation Threads Prediction](https://ece.ut.ac.ir/web/nlp/resources) - It consists of five Datasets. These datasets have been crawled from 5 websites, including Thestandard , Alef , ENENews , Russianblog and Courantblogs Datasets (XML format). Thay are selected due to several reasons:
- [Iran and COVID-19 on Social Media](https://github.com/phosseini/COVID19-fa) - Content analysis of Persian Tweets during COVID-19 pandemic in Iran using NLP
- [SBU-WSD-Corpus](https://github.com/hrouhizadeh/SBU-WSD-Corpus) - A Sense Annotated Corpus for Persian All-Words Word Sense Disambiguation.

## Models

### Named Entity Recognition
- [ParsBERT-NER](https://github.com/hooshvare/parsbert-ner) - It is a fine-tuned model based on ParsBERT (a monolingual Persian language model) on a vast range of dataset PEYMA, ARMAN, and PEYMA+ARMAN.
- [ALBERT-NER](https://github.com/m3hrdadfi/albert-persian) - It is a fine-tuned on PEYMA and ARMAN dataset based on ALBERT Language Model.

### Text Classification
- [ParsBERT DigiMag](https://github.com/hooshvare/parsbert).
- [ParsBERT Persian News](https://github.com/hooshvare/parsbert).
- [ALBERT DigiMag](https://github.com/m3hrdadfi/albert-persian).
- [ALBERT Persian News](https://github.com/m3hrdadfi/albert-persian).

### Sentiment Analysis
- [DeepSentiPers](https://github.com/JoyeBright/DeepSentiPers).
- [ParsBERT Digikala OpenData](https://github.com/hooshvare/parsbert).
- [ParsBERT SnappFood](https://github.com/hooshvare/parsbert).
- [ParsBERT DeepSentiPers Multi](https://github.com/hooshvare/parsbert).
- [ParsBERT DeepSentiPers Binary](https://github.com/hooshvare/parsbert).
- [ALBERT Digikala OpenData](https://github.com/m3hrdadfi/albert-persian).
- [ALBERT SnappFood](https://github.com/m3hrdadfi/albert-persian).
- [ALBERT DeepSentiPers Multi](https://github.com/m3hrdadfi/albert-persian).
- [ALBERT DeepSentiPers Binary](https://github.com/m3hrdadfi/albert-persian).
- [mT5 trained on ParsiNLU-ABSA](https://huggingface.co/persiannlp/mt5-base-parsinlu-sentiment-analysis?text=%DB%8C%DA%A9+%D9%81%DB%8C%D9%84%D9%85+%D8%B6%D8%B9%DB%8C%D9%81+%D8%A8%DB%8C+%D9%85%D8%AD%D8%AA%D9%88%D8%A7+%D8%A8%D8%AF%D9%88%D9%86+%D9%81%DB%8C%D9%84%D9%85%D9%86%D8%A7%D9%85%D9%87+.+%D8%B4%D9%88%D8%AE%DB%8C+%D9%87%D8%A7%DB%8C+%D8%B3%D8%AE%DB%8C%D9%81+.+%3Csep%3E+%D9%86%D8%B8%D8%B1+%D8%B4%D9%85%D8%A7+%D8%AF%D8%B1+%D9%85%D9%88%D8%B1%D8%AF+%D8%AF%D8%A7%D8%B3%D8%AA%D8%A7%D9%86%D8%8C+%D9%81%DB%8C%D9%84%D9%85%D9%86%D8%A7%D9%85%D9%87%D8%8C+%D8%AF%DB%8C%D8%A7%D9%84%D9%88%DA%AF+%D9%87%D8%A7+%D9%88+%D9%85%D9%88%D8%B6%D9%88%D8%B9+%D9%81%DB%8C%D9%84%D9%85++%D9%84%D9%88%D9%86%D9%87+%D8%B2%D9%86%D8%A8%D9%88%D8%B1+%DA%86%DB%8C%D8%B3%D8%AA%D8%9F+).


### Summarization
- [BERT2BERT](https://github.com/m3hrdadfi/wiki-summary) - BERT2BERT is the first pre-trained summarization model trained on Wiki Summary based on ParsBERT.

### Question Answering
- [bert-base-fa-qa on PersianQA](https://huggingface.co/SajjadAyoubi/bert-base-fa-qa).
- [xlm-roberta-large-fa-qa on PersianQA](https://huggingface.co/SajjadAyoubi/xlm-roberta-large-fa-qa).

### Multiple-Choice QA
- [mT5 trained on ParsiNLU-MCQA](https://huggingface.co/persiannlp/mt5-base-parsinlu-arc-comqa-obqa-multiple-choice?text=%D9%BE%D8%A7%DB%8C%D8%AA%D8%AE%D8%AA+%DA%A9%D8%B4%D9%88%D8%B1+%D8%A7%D8%B3%D8%AA%D8%B1%D8%A7%D9%84%DB%8C%D8%A7+%DA%A9%D8%AF%D8%A7%D9%85+%D8%A7%D8%B3%D8%AA%D8%9F+%3Csep%3E+%D9%85%D9%84%D8%A8%D9%88%D8%B1%D9%86+%3Csep%3E+%D8%B3%DB%8C%D8%AF%D9%86%DB%8C+%3Csep%3E+%DA%A9%D9%86%D8%A8%D8%B1%D8%A7+&fullscreen=true).

### Reading Comprehension
- [mT5 trained on ParsiNLU-RC](https://huggingface.co/persiannlp/mt5-base-parsinlu-squad-reading-comprehension?text=%D9%82%D8%A7%D8%B1%D9%87+%D8%A2%D9%85%D8%B1%DB%8C%DA%A9%D8%A7+%D8%AF%D8%B1+%DA%86%D9%87+%D8%B3%D8%A7%D9%84%DB%8C+%DA%A9%D8%B4%D9%81+%D8%B4%D8%AF%D8%9F+%5Cn+%DB%8C%D8%B4+%D8%A7%D8%B2+%D8%AF%D9%87+%D9%87%D8%B2%D8%A7%D8%B1+%D8%B3%D8%A7%D9%84+%D8%A7%D8%B3%D8%AA+%DA%A9%D9%87+%D8%A7%D9%86%D8%B3%D8%A7%D9%86%E2%80%8C%D9%87%D8%A7+%D8%AF%D8%B1+%D9%82%D8%A7%D8%B1%D9%87%D9%94+%D8%A2%D9%85%D8%B1%DB%8C%DA%A9%D8%A7+%D8%B2%D9%86%D8%AF%DA%AF%DB%8C+%D9%85%DB%8C%E2%80%8C%DA%A9%D9%86%D9%86%D8%AF.+%D9%82%D8%A7%D8%B1%D9%87+%D8%A2%D9%85%D8%B1%DB%8C%DA%A9%D8%A7+%D8%AA%D9%88%D8%B3%D8%B7+%DA%A9%D8%B1%DB%8C%D8%B3%D8%AA%D9%81+%DA%A9%D9%84%D9%85%D8%A8+%D9%88+%D8%AF%D8%B1+%D8%B3%D8%A7%D9%84+%DB%B1%DB%B4%DB%B9%DB%B2+%DA%A9%D8%B4%D9%81+%D8%B4%D8%AF+%D8%A7%D9%85%D8%A7+%D8%A7%D9%88+%D8%A8%D9%87+%D8%A7%D8%B4%D8%AA%D8%A8%D8%A7%D9%87+%D9%81%DA%A9%D8%B1+%DA%A9%D8%B1%D8%AF+%DA%A9%D9%87+%D8%A2%D9%86%D8%AC%D8%A7+%D9%87%D9%86%D8%AF%D9%88%D8%B3%D8%AA%D8%A7%D9%86+%D8%A7%D8%B3%D8%AA+%D8%A7%D9%85%D8%A7+%D9%85%D8%AF%D8%AA%E2%80%8C%D9%87%D8%A7+%D8%A8%D8%B9%D8%AF+%D8%A2%D9%85%D8%B1%DB%8C%DA%AF%D9%88+%D9%88%D8%B3%D9%BE%D9%88%DA%86%DB%8C+%D8%A7%D8%B9%D9%84%D8%A7%D9%85+%DA%A9%D8%B1%D8%AF+%DA%A9%D9%87+%D8%A7%DB%8C%D9%86+%D9%82%D8%A7%D8%B1%D9%87+%D8%AC%D8%AF%DB%8C%D8%AF%DB%8C+%D8%A7%D8%B3%D8%AA.+%D8%A7%D9%85%D8%A7+%D8%AA%D8%A7%D8%B1%DB%8C%D8%AE+%D8%A2%D9%85%D8%B1%DB%8C%DA%A9%D8%A7+%D8%A8%D9%87+%D8%B9%D9%86%D9%88%D8%A7%D9%86+%DB%8C%DA%A9+%DA%A9%D8%B4%D9%88%D8%B1+%D9%85%D8%B3%D8%AA%D9%82%D9%84+%D8%A8%D9%87+%D8%B3%D8%A7%D9%84+%DB%B1%DB%B7%DB%B8%DB%B3+%D9%85%DB%8C%D9%84%D8%A7%D8%AF%DB%8C+%D8%A8%D8%A7%D8%B2%D9%85%DB%8C%E2%80%8C%DA%AF%D8%B1%D8%AF%D8%AF+%DA%A9%D9%87+%D8%AF%D8%B1+%D8%A2%D9%86+%D8%A2%D9%85%D8%B1%DB%8C%DA%A9%D8%A7+%D8%A8%D8%B1+%D8%B7%D8%A8%D9%82+%D9%85%D8%B9%D8%A7%D9%87%D8%AF%D9%87%D9%94+%D9%BE%D8%A7%D8%B1%DB%8C%D8%B3+%D8%A8%D9%87+%D8%B1%D8%B3%D9%85%DB%8C%D8%AA+%D8%B4%D9%86%D8%A7%D8%AE%D8%AA%D9%87+%DA%AF%D8%B1%D8%AF%DB%8C%D8%AF.&fullscreen=true) - .

### Translation
- [mT5 trained on ParsiNLU-MT](https://huggingface.co/persiannlp/mt5-base-parsinlu-opus-translation_fa_en).

### Textual Entailment
- [mT5 trained on ParsiNLU-TE](https://huggingface.co/persiannlp/mt5-base-parsinlu-snli-entailment?text=%D8%A2%DB%8C%D8%A7+%DA%A9%D9%88%D8%AF%DA%A9%D8%A7%D9%86%DB%8C+%D9%88%D8%AC%D9%88%D8%AF+%D8%AF%D8%A7%D8%B1%D9%86%D8%AF+%DA%A9%D9%87+%D9%86%DB%8C%D8%A7%D8%B2+%D8%A8%D9%87+%D8%B3%D8%B1%DA%AF%D8%B1%D9%85%DB%8C+%D8%AF%D8%A7%D8%B1%D9%86%D8%AF%D8%9F+%3Csep%3E+%D9%87%DB%8C%DA%86+%DA%A9%D9%88%D8%AF%DA%A9%DB%8C+%D9%87%D8%B1%DA%AF%D8%B2+%D9%86%D9%85%DB%8C+%D8%AE%D9%88%D8%A7%D9%87%D8%AF+%D8%B3%D8%B1%DA%AF%D8%B1%D9%85+%D8%B4%D9%88%D8%AF.&fullscreen=true).

### Query Paraphrasing
- [mT5 trained on ParsiNLU-QP](https://huggingface.co/persiannlp/mt5-base-parsinlu-qqp-query-paraphrasing?text=%D8%A2%DB%8C%D8%A7+%D9%84%DB%8C%D8%B2%D8%B1+%D9%85%D9%88%D9%87%D8%A7%DB%8C+%D8%B2%D8%A7%D8%A6%D8%AF+%D8%AF%D8%A7%D8%A6%D9%85%DB%8C+%D8%A7%D8%B3%D8%AA%D8%9F+%3Csep%3E+%D8%A2%DB%8C%D8%A7+%D9%84%DB%8C%D8%B2%D8%B1+%D9%85%D9%88%D9%87%D8%A7%DB%8C+%D8%B2%D8%A7%D8%A6%D8%AF+%D8%A8%D8%A7%D8%B9%D8%AB+%D9%81%D8%B1%D8%A7%D8%B1+%D8%AF%D8%A7%D8%A6%D9%85%DB%8C+%D8%A7%D8%B2+%D9%85%D9%88%D9%87%D8%A7%DB%8C+%D9%86%D8%A7%D8%AE%D9%88%D8%A7%D8%B3%D8%AA%D9%87+%D9%85%DB%8C+%D8%B4%D9%88%D8%AF%D8%9F&fullscreen=true).

### Embeddings
- [Farsi Poem word2vec model](https://github.com/amnghd/Word2vec-on-Farsi-Literature) - This is a word2vec model deveoped based on a corpus of 48 Persian poets. The corpus consists of 1,216,286 mesras of Farsi poems and 8,102,119 words from which 148,588 are unique.
- [Sentence Transformers](https://github.com/m3hrdadfi/sentence-transformers) - ST is a collection of vector representations for sentences and paragraphs (also known as sentence embeddings). ST models are based on transformer networks like ParsBERT, ALBERT (soon). They are tuned based on Textual Thematic Similarity datasets such that sentences with similar meanings are close in vector space.

### Language Model
- [ParsBERT: Transformer-based Model for Persian Language Understanding)](https://github.com/hooshvare/parsbert) - It is a monolingual language model based on Google’s BERT architecture for the Persian Language only! This model is pre-trained on a large Persian corpus with various writing styles from numerous subjects (e.g., scientific, novels, news) with more than 2M documents. A large subset of this corpus was crawled manually.
- [ALBERT: A Lite BERT for Self-supervised Learning of Language Representations for the Persian Language](https://github.com/m3hrdadfi/albert-persian) - ALBERT is the first attempt on ALBERT for the Persian Language. The model was trained based on Google's ALBERT BASE Version 2.0 over various writing styles from numerous subjects (e.g., scientific, novels, news) with more than 3.9M documents, 73M sentences, and 1.3B words, like the way we did for ParsBERT.

### Grapheme to Phoneme
- [g2p_fa](https://github.com/de-mh/g2p_fa) - A Persian Grapheme to Phoneme model using LSTM implemented in pytorch.
- [Persian_g2p](https://github.com/AzamRabiee/Persian_G2P) - A seq-to-seq model for Persian (Farsi) Grapheme To Phoneme mapping.
- [G2P](https://github.com/hajix/G2P) - Attention Based Grapheme To Phoneme.

## Repositories

### Summarization
- [Persian-Summarization](https://github.com/minasmz/Persian-Summarization) - Statistical and semantical text summarizer in Persian language.

### Sentiment
- [Persian Sentiment Analysis](https://github.com/ashalogic/Persian-Sentiment-Analyzer) - Persian sentiment analysis ( آناکاوی سهش های فارسی | تحلیل احساسات فارسی ) is a simple ready to use project that use Python to create the model and Also it's include a very good IPython Tutorial.

## Papers and Books

### Sentiment
- [Presenting A Sentiment Analysis System Using Deep Learning Models On Persian Texts (In Persian)](https://zenodo.org/record/3551273).
- [DeepSentiPers: Novel Deep Learning Models Trained Over Proposed Augmented Persian Sentiment Corpus](https://arxiv.org/abs/2004.05328).
- [Sentiment Analysis Challenges in Persian Language](https://arxiv.org/pdf/1907.04407).
- [Sentiment analysis using deep learning on Persian texts](http://ieeexplore.ieee.org/document/7985281/) [(PDF Link)](http://bayanbox.ir/info/1313132063660147282/roshanfekr2017).
- [Deep Learning-based Sentiment Analysis in Persian Language](https://ieeexplore.ieee.org/abstract/document/9443152).
- [The Impact of Active Learning Algorithm on a Cross-lingual model in a Persian Sentiment Task](https://ieeexplore.ieee.org/abstract/document/9443156).
- [Sentiment Analysis of Persian Instagram Post: a Multimodal Deep Learning Approach](https://ieeexplore.ieee.org/abstract/document/9443026).

### Opinion Mining
- [Persian Opinion Mining:A Networked Analysis Approach](https://ieeexplore.ieee.org/abstract/document/9443158).

### Text Classification
- [Using ParsBert on Augmented Data for Persian News Classification](https://ieeexplore.ieee.org/abstract/document/9443119).

### Semantic Similarity
- [Designing a Deep Neural Network Model for Finding Semantic Similarity Between Short Persian Texts Using a Parallel Corpus](https://ieeexplore.ieee.org/abstract/document/9443108).
- [A method Based on an Attention Mechanism to Measure the Similarity of two Sentences](https://ieeexplore.ieee.org/abstract/document/9443135).

### Question Answering
- [ParSQuAD: Machine Translated SQuAD dataset for Persian Question Answering](https://ieeexplore.ieee.org/abstract/document/9443126).

### MISC
- [Comparative Study of Various Persian Stemmers in the Field of Information Retrieval ](http://jips.jatsxml.org/upload/pdf/jips-11-3-450.pdf).
- [On the Importance of Ezafe Construction in Persian Parsing](https://www.aclweb.org/anthology/P/P15/P15-2144.pdf).
- [A New Hybrid Stemming Method for Persian Language](http://dsh.oxfordjournals.org/content/early/2015/11/06/llc.fqv053) [(link2)](http://dx.doi.org.sci-hub.cc/10.1093/llc/fqv053).
- [LSCP: Enhanced Large Scale Colloquial Persian Language Understanding](https://www.aclweb.org/anthology/2020.lrec-1.776/).
- [COPER: a Query-Adaptable Semantics-based Search Engine for Persian COVID-19 Articles](https://ieeexplore.ieee.org/abstract/document/9443151).
- [Semi Automatic Detection of Persian Stopwords using FastText Library](https://ieeexplore.ieee.org/document/9721519).
- [Abusive Words Detection in Persian Tweets using Machine Learning and Deep Learning Techniques](https://ieeexplore.ieee.org/document/9729390).

### Spell Checker
[PerSpellData: An Exhaustive Parallel Spell Dataset For Persian](https://aclanthology.org/2021.nsurl-1.2.pdf).

### Books
[Persian Computational Linguistics and NLP](https://www.degruyter.com/document/isbn/9783110619225/html?).

## Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first.