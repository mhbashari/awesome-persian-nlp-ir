# Awesome Persian NLP/IR, Tools And Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list is curation of the best, not of everything. Please participate in its development.Thanks to [ACL WEB](http://aclweb.org/aclwiki/index.php?title=Resources_for_Persian).
### Contents
 - Tools
    - [Part-of-Speech Tagger](#part-of-speech-tagger)
    - [Language Detection](#language-detection)
    - [Tokenization & Segmentation](#tokenization--segmentation)
    - [Normalizer](#normalizer)
    - [Transliterator](#transliterator)
    - [Named Entity Recognition](#named-entity-recognition)
    - [Embeddings](#embeddings)
    - [Morphological Analysis](#morphological-analysis)
    - [Stemmer](#stemmer)
    - [Sentiment Analysis](#sentiment-analysis)
    
 - Data
    - [Part-of-Speech Tagger](#part-of-speech-tagger-1)
    - [Dependency Parsing](#dependency-parsing)
    - [Text Categorization and Classification](#text-categorization-and-classification)
    - [Spell Checking](#spell-checking)
    - [Machine Tanslation](#machine-tanslation)
    - [Web Collected](#web-collected)
    - [IR Ranking Evaluation](#ir-ranking-evaluation)
    - [IR Crawling And Linking Evaluation](#ir-crawling-and-linking-evaluation)
    - [MISC](#misc)
 
 - [Papers](#papers)
    
 
## Tools
### Part-of-Speech Tagger
  - [farsiNLPTools](https://github.com/wfeely/farsiNLPTools) - Open-source dependency parser, part-of-speech tagger, and text normalizer for Farsi (Persian).
  - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
  - [Persian Language Model for HunPoS](http://stp.lingfil.uu.se/~mojgan/tagper.html) - HunPoS (Halacsy et al, 2007) is an open source reimplementation of the statistical part-of-speech tagger Trigrams'n Tags, also called TnT (Brants, 2000) allowing the user to tune the tagger by using different feature settings.
  - [Maryam Tavafi POS Tagger ](http://www.cs.ubc.ca/~tavafi/projects.html) - Persian Part of Speech Tagger
  - [Perstem] (https://sourceforge.net/projects/perstem/) - Rule based POS tagger with single .pl file
  - [Persianp Toolbox](http://www.persianp.ir/toolbox.html) - Multi-purpose persian NLP toolbox

### Language Detection
  - [Google language detect (python port)](https://github.com/Mimino666/langdetect) - Light Weight language detector, its performance for persian is excellent.
  
### Tokenization & Segmentation
   - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
   - [polyglot](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models.
   - [tok-tok](https://github.com/jonsafari/tok-tok) - Tok-tok is a fast, simple, multilingual tokenizer(single .pl file).
   - [segmental](https://github.com/jonsafari/segmental) - You can train your model based on plain-text corpus for text segmentation by powerful deep learning platform.
   - [Persian Sentence Segmenter and Tokenizer: SeTPer](http://stp.lingfil.uu.se/~mojgan/setper.html) - Regex based sentence segmenter

### Normalizer
   - [HAZM](http://www.sobhe.ir/hazm/) - Python library for digesting Persian text.
   - [Persian Pre-processor: PrePer](http://stp.lingfil.uu.se/~mojgan/preper.html) - Another signle .pl tools that normals your persian text
   
### Transliterator
   - [Perstem](https://sourceforge.net/projects/perstem/) - Rule based transliterator with single .pl file
   
### Named Entity Recognition
   - [polyglot](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models.

### Embeddings
   - [polyglot](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models. 

### Morphological Analysis
   - [polyglot](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models. 

### Stemmer
   - [Perstem](https://sourceforge.net/projects/perstem/) - Rule based stemmer with single .pl file
   - [polyglot](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models.Stemming by using the morphological analysing package.

### Sentiment Analysis
   - [polyglot (polarity)](https://github.com/aboSamoor/polyglot) - Multi-lingual and Multi-purpose Python NLP library with pretrained models.
   - [NRC-Persian-Lexicon](https://github.com/mhbashari/NRC-Persian-Lexicon) - NRC Word-Emotion Association Lexicon useful for persian sentiment analysis

   
## Data
### Part-of-Speech Tagger
   - [Bijankhan Corpus](http://ece.ut.ac.ir/dbrg/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags. 

   - [Mojgan Seraji Corpus](http://stp.lingfil.uu.se/~mojgan/UPC.html) - Uppsala Persian Corpus (UPC) is a large, freely available Persian corpus. The corpus is a modified version of the Bijankhan corpus with additional sentence segmentation and consistent tokenization containing 2,704,028 tokens and annotated with 31 part-of-speech tags. The part-of-speech tags are listed with explanations in [this table](http://stp.lingfil.uu.se/~mojgan/Table_tag.pdf). 
   

### Dependency Parsing
   - [Persian Syntactic Dependency Treebank](http://dadegan.ir/catalog/perdt) - This treebank is supplied for free noncommercial use. For commercial uses feel free to contact us. The number of annotated sentences is 29,982 sentences including samples from almost all verbs of the Persian valency lexicon.   
   - [Uppsala Persian Dependency Treebank: UPDT](http://stp.lingfil.uu.se/~mojgan/UPDT.html) - Dependency-based syntactically annotated corpus.
     - [Pretrained model](http://stp.lingfil.uu.se/~mojgan/parsper-mate.html)
   - [Universal Dependencies 1.3](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1699) - Multi lingual corpus that holds IOB gold data for dependency parsing
   - [HamleDT 3.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508) - HArmonized Multi-LanguagE Dependency Treebank is a compilation of existing dependency treebanks (or dependency conversions of other treebanks), transformed so that they all conform to the same annotation style. This version uses Universal Dependencies as the common annotation style.

### Text Categorization and Classification
   - [Hamshahri](http://ece.ut.ac.ir/dbrg/hamshahri/) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.
   - [Bijankhan Corpus](http://ece.ut.ac.ir/dbrg/bijankhan/) - Bijankhan corpus is a tagged corpus that is suitable for natural language processing research on the Persian (Farsi) language. This collection is gathered form daily news and common texts. In this collection all documents are categorized into different subjects such as political, cultural and so on. Totally, there are 4300 different subjects. The Bijankhan collection contains about 2.6 millions manually tagged words with a tag set that contains 40 Persian POS tags. 

### Spell Checking
   - [FAspell](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-1547) - FASpell dataset was developed for the evaluation of spell checking algorithms. It contains a set of pairs of misspelled Persian words and their corresponding corrected forms similar to the ASpell dataset used for English.

### Machine Tanslation
   - [TEP: Tehran English-Persian Parallel Corpus](http://ece.ut.ac.ir/node/100869?destination=node%2F100869) - First free English-Persian corpus

### Web Collected
   - [W2C – Web to Corpus – Corpora](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) - A set of corpora for 120 languages automatically collected from wikipedia and the web. 
   - [dotIR Collection](http://ece.ut.ac.ir/DBRG/webir/) - dotIR is a standard Persian test collection that is suitable for evaluation of web information retrieval algorithms in Iranian web.dotIR Contains many Persian web pages including their text, links, metadata, etc that are stored in XML format. It is prepared in such a way to be a good representative of Iranian web.It is A good test bed for evaluation of link based information retrieval algorithms. It includes enough Queries and relevance judgments for a valid evaluation.It is not very large, so that it does not require high processing resources.

### IR Ranking Evaluation
   - [Hamshahri](http://ece.ut.ac.ir/dbrg/hamshahri/) - Hamshahri collection is a standard reliable Persian text collection that was used at Cross Language Evaluation Forum (CLEF) during years 2008 and 2009 for evaluation of Persian information retrieval systems.

### IR Crawling And Linking Evaluation
   - [dotIR Collection](http://ece.ut.ac.ir/DBRG/webir/) - dotIR is a standard Persian test collection that is suitable for evaluation of web information retrieval algorithms in Iranian web.dotIR Contains many Persian web pages including their text, links, metadata, etc that are stored in XML format. It is prepared in such a way to be a good representative of Iranian web.It is A good test bed for evaluation of link based information retrieval algorithms. It includes enough Queries and relevance judgments for a valid evaluation.It is not very large, so that it does not require high processing resources.

### MISC
   - [perspred](http://perspred.cnrs.fr/perspred-project) - Multiword verbs. 
   - [My stopword list](https://github.com/mhbashari/awesome-persian-nlp-ir/blob/master/stopwords.txt) - Curated List of persian stop words.

## Papers
   - [Comparative Study of Various Persian Stemmers in the Field of Information Retrieval ](http://jips.jatsxml.org/upload/pdf/jips-11-3-450.pdf)

# Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

# License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
