# Datasets for Natural Language Processing
This is a list of datasets/corpora for NLP tasks, in reverse chronological order.
Suggestions and pull requests are welcome. The goal is to make this a collaborative effort to maintain an updated list of quality datasets.

# Areas
  * [Question Answering](#question-answering)
  * [Dialogue Systems](#dialogue-systems)
  * [Goal-Oriented Dialogue Systems](#goal-oriented-dialogue-systems)
  * [Language Modeling](#language-modeling)
  * [Visual Question Answering](#visual-qa)

## Question Answering
  * **(NLVR)** A Corpus of Natural Language for Visual Reasoning, 2017 [[paper]](http://yoavartzi.com/pub/slya-acl.2017.pdf) [[data]](http://lic.nlp.cornell.edu/nlvr)
  * **(MS MARCO)** MS MARCO: A Human Generated MAchine Reading COmprehension Dataset, 2016 [[paper]](https://arxiv.org/abs/1611.09268) [[data]](http://www.msmarco.org/)
  * **(NewsQA)** NewsQA: A Machine Comprehension Dataset, 2016 [[paper]](https://arxiv.org/abs/1611.09830) [[data]](https://github.com/Maluuba/newsqa)
  * **(SQuAD)** SQuAD: 100,000+ Questions for Machine Comprehension of Text, 2016 [[paper]](http://arxiv.org/abs/1606.05250) [[data]](http://stanford-qa.com)
  * **(GraphQuestions)** On Generating Characteristic-rich Question Sets for QA Evaluation, 2016 [[paper]](http://cs.ucsb.edu/~ysu/papers/emnlp16_graphquestions.pdf) [[data]](https://github.com/ysu1989/GraphQuestions)
  * **(Story Cloze)** A Corpus and Cloze Evaluation for Deeper Understanding of
Commonsense Stories, 2016 [[paper]](http://arxiv.org/abs/1604.01696) [[data]](http://cs.rochester.edu/nlp/rocstories)
  * **(Children's Book Test)** The Goldilocks Principle: Reading Children's Books with Explicit Memory Representations, 2015 [[paper]](http://arxiv.org/abs/1511.02301) [[data]](http://www.thespermwhale.com/jaseweston/babi/CBTest.tgz)
  * **(SimpleQuestions)** Large-scale Simple Question Answering with Memory Networks, 2015 [[paper]](http://arxiv.org/pdf/1506.02075v1.pdf) [[data]](https://www.dropbox.com/s/tohrsllcfy7rch4/SimpleQuestions_v2.tgz)
  * **(WikiQA)** WikiQA: A Challenge Dataset for Open-Domain Question Answering, 2015 [[paper]](http://research.microsoft.com/pubs/252176/YangYihMeek_EMNLP-15_WikiQA.pdf) [[data]](http://research.microsoft.com/en-US/downloads/4495da01-db8c-4041-a7f6-7984a4f6a905/default.aspx)
  * **(CNN-DailyMail)** Teaching Machines to Read and Comprehend, 2015 [[paper]](http://arxiv.org/abs/1506.03340) [[code to generate]](https://github.com/deepmind/rc-data)  [[data]](http://cs.nyu.edu/~kcho/DMQA/)
  * **(QuizBowl)** A Neural Network for Factoid Question Answering over Paragraphs, 2014 [[paper]](https://www.cs.umd.edu/~miyyer/pubs/2014_qb_rnn.pdf) [[data]](https://www.cs.umd.edu/~miyyer/qblearn/index.html)
  * **(MCTest)** MCTest: A Challenge Dataset for the Open-Domain Machine Comprehension of Text, 2013 [[paper]](http://research.microsoft.com/en-us/um/redmond/projects/mctest/MCTest_EMNLP2013.pdf) [[data]](http://research.microsoft.com/en-us/um/redmond/projects/mctest/data.html) [[alternate data link]](https://github.com/mcobzarenco/mctest/tree/master/data/MCTest)  
  * **(QASent)** What is the Jeopardy model? A quasisynchronous grammar for QA, 2007 [[paper]](http://homes.cs.washington.edu/~nasmith/papers/wang+smith+mitamura.emnlp07.pdf) [[data]](http://cs.stanford.edu/people/mengqiu/data/qg-emnlp07-data.tgz)
  * **(Google Natural Questions)** a Benchmark for Question Answering Research [[paper]](https://research.google/pubs/pub47761/) [[download]](https://ai.google.com/research/NaturalQuestions)
  * **(DeepMind Question Answering Corpus)** Question answering dataset featured in "Teaching Machines to Read and Comprehend [[repo]](https://github.com/deepmind/rc-data)
  * **(Amazon Question Answering Corpus)** This dataset contains Question and Answer data from Amazon, totaling around 1.4 million answered questions. [[download]] (http://jmcauley.ucsd.edu/data/amazon/qa/)

## Dialogue Systems
  * **(Ubuntu Dialogue Corpus)** The Ubuntu Dialogue Corpus : A Large Dataset for Research in Unstructured Multi-Turn Dialogue Systems, 2015 [[paper]](http://arxiv.org/abs/1506.08909) [[data]](https://github.com/rkadlec/ubuntu-ranking-dataset-creator)

## Goal-Oriented Dialogue Systems
  * **(Frames)** Frames: A Corpus for Adding Memory to Goal-Oriented Dialogue Systems, 2016 [[paper]](https://arxiv.org/abs/1704.00057) [[data]](http://datasets.maluuba.com/Frames)
  * **(DSTC 2 & 3)** Dialog State Tracking Challenge 2 & 3, 2013 [[paper]](http://camdial.org/~mh521/dstc/downloads/handbook.pdf) [[data]](http://camdial.org/~mh521/dstc/)

## Language Modeling
* **(Google 1 Billion Word Corpus)** A freely available corpus of relatively large size for building and testing language models accompanied by baseline N-gram models [[download]](https://opensource.google/projects/lm-benchmark)
* **(WikiText-103)** WikiText-103 corpus contains 267,735 unique words and each word occurs at least three times in the training set. [[download]](https://www.salesforce.com/products/einstein/ai-research/the-wikitext-dependency-language-modeling-dataset/)
* **(Project Gutenberg)** A large collection of free books that can be retrieved in plain text for a variety of languages [[download]](https://www.gutenberg.org/)

## Visual Question Answering
* **(VQA)** VQA is a new dataset containing open-ended questions about images. These questions require an understanding of vision, language and commonsense knowledge to answer. [[download]] (https://visualqa.org/download.html)
* **(DAQUAR)** DAtaset for QUestion Answering on Real-world images (https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/visual-turing-challenge/)
* **(Visual7W)** Visual7W is a large-scale visual question answering (QA) dataset, with object-level groundings and multimodal answers. Each question starts with one of the seven Ws, what, where, when, who, why, how and which. [[paper]](https://arxiv.org/abs/1511.03416) [[download]](https://github.com/yukezhu/visual7w-toolkit)
* **(Visual Madlibs)** Fill in the blanks Question Answering dataset [[paper]](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Yu_Visual_Madlibs_Fill_ICCV_2015_paper.pdf) [[download]](http://tamaraberg.com/visualmadlibs/)
* **(COCO-QA)** The COCO-QA dataset is another dataset based on MS-COCO. Both questions and answers are generated automatically using image captions from MS-COCO and broadly belong to four categories: Object, Number, Color and Location[[download]](http://www.cs.toronto.edu/~mren/research/imageqa/data/cocoqa/)
* **(Visual Genome)** Visual Genome is a dataset, a knowledge base, an ongoing effort to connect structured image concepts to language. It has 1.7 million Visual Question Answers [[download]](https://visualgenome.org/)
* **(SHAPES)** consists of shapes of varying arrangements, types, and colors. Questions are about the attributes, relationships, and positions of the shapes [[paper]](https://pdfs.semanticscholar.org/0ac8/f1a3c679b90d22c1f840cdc8d61ffef750ac.pdf)