# Persian Language Processing Datasets

## Table Of Contents
- [Part-of-Speech Tagger](#part-of-speech-tagger)
- [Named Entity Recognition](#named-entity-recognition)
- [Relation Extraction](#relation-extraction)
- [Dependency Parsing](#dependency-parsing)
- [Text Categorization and Classification](#text-categorization-and-classification)
- [Spell Checking](#spell-checking)
- [Textual Entailment](#textual-entailment)
- [Textual Thematic Similarity](#textual-thematic-similarity)
- [Persian Poems And Classic Texts](#persian-poems-and-classic-texts)
- [Sentiment Analysis](#sentiment-analysis)
- [Summarization](#summarization)
- [Question Answering](#question-answering)
- [Irony - Insult](#irony---insult)
- [Corpus](#corpus)
- [Stop Word Lists](#stop-word-lists)
- [Knowledge Bases](#knowledge-bases)
- [MISC](#misc)


## Part-of-Speech Tagger
- [Bijankhan Corpus](https://dbrg.ut.ac.ir/%D8%A8%DB%8C%DA%98%D9%86%E2%80%8C%D8%AE%D8%A7%D9%86) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.
- [Mojgan Seraji Corpus](http://stp.lingfil.uu.se/~mojgan/UPC.html) - Uppsala Persian Corpus (UPC) is a large, freely available Persian corpus. The corpus is a modified version of the Bijankhan corpus with additional sentence segmentation and consistent tokenization containing 2,704,028 tokens and annotated with 31 part-of-speech tags. The part-of-speech tags are listed with explanations in [this table](http://stp.lingfil.uu.se/~mojgan/Table_tag.pdf).
- [Large-Scale Colloquial Persian](http://hdl.handle.net/11234/1-3195) - Large Scale Colloquial Persian Dataset (LSCP) is hierarchically organized in asemantic taxonomy that focuses on multi-task informal Persian language understanding as a comprehensive problem. LSCP includes 120M sentences from 27M casual Persian tweets with its dependency relations in syntactic annotation, Part-of-speech tags, sentiment polarity and automatic translation of original Persian sentences in English (EN), German (DE), Czech (CS), Italian (IT) and Hindi (HI) spoken languages. Learn more about this project at [LSCP webpage](https://iasbs.ac.ir/~ansari/lscp/).

## Named Entity Recognition
- [ArmanPersoNERCorpus](https://github.com/HaniehP/PersianNER) - The dataset includes 250,015 tokens and 7,682 Persian sentences in total. It is available in 3 folds to be used in turn as training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. Each sentence is separated with a newline. The NER tags are in IOB format.
- [FarsiYar PersianNER](https://github.com/Text-Mining/Persian-NER) - The dataset includes about 25,000,000 tokens and about 1,000,000 Persian sentences in total based on [Persian Wikipedia Corpus](https://github.com/Text-Mining/Persian-Wikipedia-Corpus). The NER tags are in IOB format. More than 1000 volunteers contributed tag improvements to this dataset via web panel or android app. They release updated tags every two weeks.
- [Workshop on NLP Solutions for Under Resourced Languages (NSURL) 2019 - Task 7 dataset](http://nsurl.org/tasks/task-7-named-entity-recognition-ner-for-farsi/) - contains a medium size NER corpus with 7 classes of named entities (person, location and organization, money, percent, dates, and time). This corpus contains more than 700 news documents. 

## Relation Extraction 
- [PERLEX](http://farsbase.net/PERLEX.html) - The first Persian dataset for relation extraction, which is an expert translated version of the “Semeval-2010-Task-8” dataset. Link to [the relevant publication](https://arxiv.org/pdf/2005.06588.pdf). 
 
## Dependency Parsing
- [Persian Syntactic Dependency Treebank](http://dadegan.ir/catalog/perdt) - This treebank is supplied for free noncommercial use. For commercial uses feel free to contact us. The number of annotated sentences is 29,982 sentences including samples from almost all verbs of the Persian valency lexicon.
- [Uppsala Persian Dependency Treebank: UPDT](http://stp.lingfil.uu.se/~mojgan/UPDT.html) - Dependency-based syntactically annotated corpus.
- [Pretrained model](http://stp.lingfil.uu.se/~mojgan/parsper-mate.html)
- [Universal Dependencies 1.3](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1699) - Multi lingual corpus that holds IOB gold data for dependency parsing
- [HamleDT 3.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508) - HArmonized Multi-LanguagE Dependency Treebank is a compilation of existing dependency treebanks (or dependency conversions of other treebanks), transformed so that they all conform to the same annotation style. This version uses Universal Dependencies as the common annotation style.
- [Large-Scale Colloquial Persian](http://hdl.handle.net/11234/1-3195) - Large Scale Colloquial Persian Dataset (LSCP) is hierarchically organized in asemantic taxonomy that focuses on multi-task informal Persian language understanding as a comprehensive problem. LSCP includes 120M sentences from 27M casual Persian tweets with its dependency relations in syntactic annotation, Part-of-speech tags, sentiment polarity and automatic translation of original Persian sentences in English (EN), German (DE), Czech (CS), Italian (IT) and Hindi (HI) spoken languages. Learn more about this project at [LSCP webpage](https://iasbs.ac.ir/~ansari/lscp/).
- [MULTEXT-East](https://www.clarin.si/repository/xmlui/handle/11356/1042) - The MULTEXT-East morphosyntactic lexicons have a simple structure, where each line is a lexical entry with three tab-separated fields: (1) the word-form, the inflected form of the word; (2) the lemma, the base-form of the word; (3) the MSD, the morphosyntactic description of the word-form, i.e., its fine-grained PoS tag, as defined in the MULTEXT-East morphosyntactic specifications.

## Text Categorization and Classification
- [Hamshahri](http://dbrg.ut.ac.ir/Hamshahri/download.html) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.
- [Bijankhan Corpus](http://dbrg.ut.ac.ir/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags.
- [Digikala Magazine (DigiMag)](https://hooshvare.github.io/docs/datasets/tc#digikala-magazine-digimag) - A total of 8,515 articles scraped from Digikala Online Magazine. This dataset includes seven different classes `Video Games`, `Shopping Guide`, `Health Beauty`, `Science Technology`, `General`, `Art Cinema`, and `Books Literature`.
- [Persian News](https://hooshvare.github.io/docs/datasets/tc#persian-news) - A dataset of various news articles scraped from different online news agencies’ websites. The total number of articles is 16,438, spread over eight different classes, `Economic`, `International`, `Political`, `Science Technology`, `Cultural Art`, `Sport`, and `Medical`.

## Spell Checking
- [FAspell](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-1547) - FASpell dataset was developed for the evaluation of spell checking algorithms. It contains a set of pairs of misspelled Persian words and their corresponding corrected forms similar to the ASpell dataset used for English.
- [Persian-Spell-checker](https://github.com/reza1615/Persian-Spell-checker) - We're collecting persian words' dictionary (verbs, nouns, and etc.) for Persian spell checker.
- [Grammar and context sensitive spell checker](https://ece.ut.ac.ir/web/nlp/resources) - It is a real-world test set for grammatical errors and context sensitive spelling errors for Persian language. This test set contains 1100 context sensitive errors and was collected from Persian Blogs.
- [Spell Checker](https://ece.ut.ac.ir/web/nlp/resources) - Test set for spelling errors for Persian language.​
- [CPG: Corpus of Persian Grammatical Errors](https://ece.ut.ac.ir/web/nlp/resources) - It  is a fully-annotated corpus of grammatical errors collected from 700 essays written by learners of Persian language in *Dehkhoda Lexicon Institute & International Centre for Persian Studies and Imam Khomeini International University*.

## Textual Entailment 
- [FarsTail](https://github.com/dml-qom/FarsTail) -  FarsTail is a dataset of textual entailment (also known as natural language inference, NLI) and it includes 10,367 samples in the Persian language. Here is [the relevant paper](https://arxiv.org/pdf/2009.08820.pdf). 

## Textual Thematic Similarity
- [Wikipedia Section Sentences](https://github.com/m3hrdadfi/sentence-transformers) - It implements the idea from Dor et al., 2018, [Learning Thematic Similarity Metric Using Triplet Networks](https://www.aclweb.org/anthology/P18-2009/) for Persian. The dataset includes 205,768 examples that covered 21,515 articles and 34,298 sections.
- [Wiki Triplet](https://github.com/m3hrdadfi/sentence-transformers) -  A triplet-objective dataset extracted from ***Wikipedia Section Sentences*** into a triplet-form of anchor (<img src="https://render.githubusercontent.com/render/math?math=a">), positive (<img src="https://render.githubusercontent.com/render/math?math=p">) and negative (<img src="https://render.githubusercontent.com/render/math?math=n">) examples. It covers 191,929 samples.
- [Wiki D-Similar](https://github.com/m3hrdadfi/sentence-transformers) -  Wiki D-Similar is another form of thematic similarity dataset with 137,402 records that tags pairs of sentences into a form of similar or dissimilar.

## Persian Poems And Classic Texts
- [Farsi Poem Corpus](https://github.com/amnghd/Persian_poems_corpus) - This corpus consists of text documents for 48 Persian poets. The corpus comes in three formats; original, normalized (only 32 main Farsi alphabet), and stop words removed. The corpus consists of 1,216,286 mesras of Farsi poems and 8,102,119 words from which 148,588 are unique.

## Sentiment Analysis
- [NRC-Persian-Lexicon](https://github.com/mhbashari/NRC-Persian-Lexicon) - NRC Word-Emotion Association Lexicon useful for persian sentiment analysis.
- [Digikala OpenData Sentiment](https://www.digikala.com/opendata/#section-4) - data contains 100,000 samples of users' comments in favor of products labeled as `no_idea`, `not_recommended `, and `recommended `.
- [Pars-ABSA](https://github.com/Titowak/Pars-ABSA) - Manually annotated Persian dataset, verified by 3 native Persian speakers. The dataset consists of 5,114 positive, 3,061 negative and 1,827 neutral data samples from 5,602 unique reviews.  
- [PerSent](https://www.gelbukh.com/resources/persent/) - This dataset presents real-valued polarity labels, in the range from -1 to 1, for thousands of Persian words and expressions.  
- [DeepSentiPers](https://github.com/JoyeBright/DeepSentiPers) - Novel Deep Learning Models Trained Over Proposed Augmented Persian Sentiment Corpus
- [SentiPers](https://github.com/phosseini/sentipers) -  Documents in SentiPers are manually annotated at different levels. 
- [LexiPers](https://github.com/phosseini/lexipers) - An ontology based sentiment lexicon for Persian.  
- [SnappFood](https://hooshvare.github.io/docs/datasets/sa#snappfood) - Snappfood (an online food delivery company) user comments containing 70,000 comments with two labels (i.e. polarity classification), `Happy` and `Sad`.
- [MirasOpinion](https://github.com/miras-tech/MirasText/tree/master/MirasOpinion) - This repository contains information about MirasOpinion dataset, which is the largest Persian sentiment analysis dataset up to this date, alongside a demo file which contains 20 documents with their corresponding labels.

## Summarization
- [Wiki Summary](https://github.com/m3hrdadfi/wiki-summary) - Wiki Summary is a summarization dataset extracted from Persian Wikipedia into the form of articles and highlights.


## Question Answering
- [PersianQA](https://github.com/sajjjadayobi/PersianQA) - Persian Question Answering (PersianQA) Dataset is a reading comprehension dataset on Persian Wikipedia. The crowd-sourced dataset consists of more than 9,000 entries. Each entry can be either an impossible-to-answer or a question with one or more answers spanning in the passage (the context) from which the questioner proposed the question. Much like the SQuAD2.0 dataset, the impossible or unanswerable questions can be utilized to create a system which "knows that it doesn't know the answer".

## Irony - Insult
- [MirasIrony](https://github.com/miras-tech/MirasText/tree/master/MirasIrony) - The irony dataset is constructed from Persian tweets. 2942 tweets are labeled in total.

## Corpus
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

## Stop Word Lists
- [Persian stopwords collection](https://github.com/ziaa/Persian-stopwords-collection) - A collection of Persian stop words list
- [Hazm stop words](https://github.com/sobhe/hazm/blob/master/hazm/data/stopwords.dat) - Stop words list, good for IR.
- [mhbashari stopword list](https://github.com/mhbashari/awesome-persian-nlp-ir/blob/master/stopwords.txt) - Experimental list of stopwords that is suitable for topic modelling and word embedding.
- [Persian, Arabic and English stopwords](http://www.mojiry.ir/text_tools/WordFrequencePage.php) - A collection of stopwords on three languages.

## Knowledge Bases
- [FarsBase](http://farsbase.net/about) -  FarsBase the first Persian multi-source knowledge graph, which isspecifically designed for semantic search engines to support Persian knowledge. FarsBase uses a diverse set of hybrid and flexible techniques to extract and integrate knowledge from various sources, such as Wikipedia, Web tables and unstructured texts. Here is [the relevant paper](http://www.semantic-web-journal.net/system/files/swj2210.pdf). 

## MISC
- [ParsiNLU](https://github.com/persiannlp/parsinlu) - A collection natural language understanding datasets for Persian. [Here is the relevant paper.](https://arxiv.org/abs/2012.06154)
- [PersianStemmingDataset](https://github.com/MrHTZ/PersianStemmingDataset) - PersianStemmingDataset is consist of two manually stemmed persian corpora and an evalution tools in order to compute stemming evaluatin metrics.
- [PersPred](http://perspred.cnrs.fr/perspred-project) - PersPred, is the first online multilingual syntactic and semantic database of Persian compound verbs (complex predicates), developed by the members of the research unit Mondes iranien et indien (CNRS, Sorbonne Nouvelle, Inalco, EPHE) within the ANR-DFG project PERGRAM (2008-2012) and the LR4.1 work package of the Strand 6 of the Labex Empirical Foundations of Linguistics (EFL).
- [Popularity Prediction](https://ece.ut.ac.ir/web/nlp/resources) - It is Tabnak and Alef Datasets which are the most famous online news agencies in Iran. This dataset includes content, title, date, category and number of comments per each news. Besides popularity of these websites, the wide range of news categories they cover and they have the multilevel commenting structure.
- [Conversation Threads Prediction](https://ece.ut.ac.ir/web/nlp/resources) - It consists of five Datasets. These datasets have been crawled from 5 websites, including Thestandard , Alef , ENENews , Russianblog and Courantblogs Datasets (XML format). Thay are selected due to several reasons:
