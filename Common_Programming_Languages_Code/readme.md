- [1. Common Programming Languages Code](#1-common-programming-languages-code)
  * [1.1 CODE-NN 2016](#11-code-nn-2016)
  * [1.2 NLP2Code 2017](#12-nlp2code-2017)
  * [1.3 Code Docstring Corpus 2017](#13-code-docstring-corpus-2017)
  * [1.4 StaQC 2018](#14-staqc-2018)
  * [1.5 CoNaLa 2018](#15-conala-2018)
  * [1.6 CONCODE 2018](#16-concode-2018)
  * [1.7 CodeCS 2018](#17-codecs-2018)
  * [1.8 CROKAGE 2018](#18-crokage-2018)
  * [1.9 JuICe 2019](#19-juice-2019)
  * [1.10 NCS 2019](#110-ncs-2019)
  * [1.11 CodeSearchNet](#111-codesearchnet)
  * [1.12 MucQC 2020](#112-mucqc-2020)
  * [1.13 CoDesc 2021](#113-codesc-2021)
  * [1.14 CodeXGLUE 2021](#114-codexglue-2021)
  * [1.15 PyTorrent 2021](#115-pytorrent-2021)
  * [1.16 CoSQA 2021](#116-cosqa-2021)

## 1. Common Programming Languages Code

This category is mostly drawn from the open source community and contains several programming languages commonly used by developers.

```
Input: natural language descriptions
Output: code snippets for common programming languages
```

------

### 1.1 CODE-NN 2016

**Description:**

The corpus was collected from Stack Overflow data dumps, and the authors first used heuristic rules to filter out low-quality data, followed by training a semi-supervised classifier to filter data whose titles were not related to the corresponding code snippets.

**Language(s):**

C# & SQL

**Contributor:**

Summarizing source code using a neural attention model [[Link](https://aclanthology.org/P16-1195.pdf)]

Using in the **Code Search** task

ACL 2016 (CCF A)

**URL:**

https://github.com/sriniiyer/codenn/tree/master/data/stackoverflow

**User(es):**

- Chen and Zhou.[[Link](https://ieeexplore.ieee.org/abstract/document/9000013)] A Neural Framework for Retrieval and Summarization of Source Code

  Using in the **Code Search** task

  ASE 2018 (CCF A)

- Zhu et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9285661)] OCoR: An Overlapping-Aware Code Retriever

  Using in the **Code Search** task

  ASE 2020 (CCF A)
  
- Li et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9240627)] Learning Code-Query Interaction for Enhancing Code Searches

  Using in the **Code Search** task

  ICSME 2020 (CCF B)

------

### 1.2 NLP2Code 2017

**Description:**

The corpus was collected from the Stack Overflow data dump, and the authors extracted 599,550 natural language tasks from 1,109,677 Stack Overflow titles tagged as "java" using the TaskNav algorithm(which conceptualises tasks in software documents as verbs associated with direct objects and/or prepositional phrases, taking into account contextual information and different grammatical ways of describing them).

**Language(s):**

Java

**Contributor:**

NLP2Code: Code Snippet Content Assist via Natural Language Tasks [[Link](https://ieeexplore.ieee.org/abstract/document/8094469)]

Using in the **Code Search** task

ICSME 2017 (CCF B)

**URL:**

https://github.com/ctreude/nlp2code/tree/master/data

**User(es):**

Not found

------

### 1.3 Code Docstring Corpus 2017

**Description:**

The corpus was collected from Github, retaining Python 2.7 code, and the authors extracted function snippets and corresponding top-level functions docstrings from project files at the function level of granularity; subsequently, they also released an extended version of the corpus, containing class definitions and class methods.

**Language(s):**

Python 2.7

**Contributor:**

A Parallel Corpus of Python Functions and Documentation Strings for Automated Code Documentation and Code Generation [[Link](https://aclanthology.org/I17-2053/)] 

Using in the **Code Generation** task

IJCNLP 2017

**URL:**

https://github.com/EdinburghNLP/code-docstring-corpus

**User(es):**

- Wang et al.[[Link](https://arxiv.org/abs/2003.03238)] TranS3 : A Transformer-based Framework for Unifying Code Summarization and Code Search 

  Using in the **Code Search** task

  Arxiv

- Zhou et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9609166/)] Assessing Generalizability of CodeBERT 

  Using in the **Code Search** task

  ICSME 2021 (CCF B)

- Zhao et al.[[Link](https://arxiv.org/abs/2201.08810)] GAP-Gen: Guided Automatic Python Code Generation 

  Using in the **Code Generation** task

  Arxiv

------

### 1.4 StaQC 2018

**Description:**

The corpus was collected from Stack Overflow and the authors used a Bi-View Hierarchical Neural Network to automatically mine approximately 148K Python question-code pairs and 120K SQL question-code pairs. Both Multi-code answer posts and Single-code answer posts are included in the corpus.  What's more, the authors hired undergraduate students to hand-tag response posts in both domains in order to construct a dataset for the Bi-View Hierarchical Neural Network model.

**Language(s):**

Python & SQL

**Contributor:**

StaQC: A Systematically Mined Question-Code Dataset from Stack Overflow [[Link](https://dl.acm.org/doi/abs/10.1145/3178876.3186081)]

Using in the **Code Search** task

WWW 2018 (CCF A)

**URL:**

https://github.com/LittleYUYU/StackOverflow-Question-Code-Dataset

**User(es):**

- Zhao and Sun[[Link](https://aclanthology.org/2020.findings-emnlp.361/)] Adversarial Training for Code Retrieval with Question-Description Relevance Regularization

  Using in the **Code Search** task

  EMNLP 2020 Findings (CCF B)

- Yao et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3308558.3313632)] CoaCor: Code Annotation for Code Retrieval with Reinforcement Learning

  Using in the **Code Search** task

  WWW 2019 (CCF A)

- Ye et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3366423.3380295)] Leveraging Code Generation to Improve Code Retrieval and Summarization via Dual Learning

  Using in the **Code Search** task

  WWW 2020 (CCF A)

- Zhu et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9285661)] OCoR: An Overlapping-Aware Code Retriever

  Using in the **Code Search** task

  ASE 2020 (CCF A)

- Heyman  and Cutsem.[[Link](https://arxiv.org/abs/2008.12193)] Neural Code Search Revisited: Enhancing Code Snippet Retrieval through Natural Language Intent

  Using in the **Code Search** task

  Arxiv

- Hu et al.[[Link](https://www.sciencedirect.com/science/article/pii/S0164121220301886)] Neural joint attention code search over structure embeddings for software Q&A sites

  Using in the **Code Search** task

  JSS (CCF B)

- Martins and Gerosa[[Link](https://dl.acm.org/doi/abs/10.1145/3422392.3422462)] CoNCRA: A Convolutional Neural Network Code Retrieval Approach

  Using in the **Code Search** task

  SBES 2020

- Wang et al.[[Link](https://arxiv.org/abs/2010.09520)] COSEA: Convolutional Code Search with Layer-wise Attention

  Using in the **Code Search** task

  Arxiv

- Li et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9207101)] Hierarchical Embedding for Code Search in Software Q&A Sites

  Using in the **Code Search** task

  IJCNN 2020 (CCF C)

- Zhou et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9609166/)] Assessing Generalizability of CodeBERT 

  Using in the **Code Search** task

  ICSME 2021 (CCF B)

------

### 1.5 CoNaLa 2018

**Description:**

The corpus was collected from Stack Overflow, automatically filtered, then curated by annotators, split into 2,379 training and 500 test examples (read more about the process [here](https://conala-corpus.github.io/mining.html)). The authors also provide a large automatically-mined dataset with 600k examples, and links to other similar datasets.

**Language(s):**

Python & Java

**Contributor:**

Learning to Mine Aligned Code and Natural Language Pairs from Stack Overflow [[Link](https://ieeexplore.ieee.org/abstract/document/8595231/)]

Using in the **Code Generation** and **Code Search** task

MSR 2018 (CCF C)

**URL:**

https://conala-corpus.github.io/#dataset-information

**User(es):**

- Yin and Neubig.[[Link](https://aclanthology.org/P19-1447/)] Reranking for Neural Semantic Parsing 

  Using in the **Code Generation** task

  ACL 2019 (CCF A)

- Ye et al.[[Link](https://aclanthology.org/P19-1201/)] Jointly Learning Semantic Parser and Natural Language Generator via Dual Information Maximization

  Using in the **Code Generation** task

  ACL 2019 (CCF A)

- Gemmell et al.[[Link](https://arxiv.org/pdf/2007.02609.pdf)] Relevance Transformer: Generating Concise Code Snippets with Relevance Feedback

  Using in the **Code Generation** task

  SIGIR 2020 (CCF A)

- Youssef et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9523647)] Text to Code Conversion Using Deep Learning for NLP

  Using in the **Code Generation** task

  ISAECT 2020

- Xu et al.[Link] Incorporating External Knowledge through Pre-training for Natural Language to Code Generation

  Using in the **Code Generation** task

  ACL 2020 (CCF A)

- Silva et al.[[Link](https://link.springer.com/article/10.1007/s10664-020-09863-2)] CROKAGE: effective solution recommendation for programming tasks by leveraging crowd knowledge

  Using in the **Code Search** task

  Empirical Software Engineering (CCF B)

- Heyman and Cutsem.[[Link](https://arxiv.org/abs/2008.12193)] Neural Code Search Revisited: Enhancing Code Snippet Retrieval through Natural Language Intent

  Using in the **Code Search** task

  Arxiv

- Norouzi et al.[Link] Code Generation from Natural Language with Less Prior and More Monolingual Data

  Using in the **Code Generation** task

  ACL 2021 (CCF A)

- Jiang et al.[[Link](https://aclanthology.org/2021.acl-long.394/)] Exploring Dynamic Selection of Branch Expansion Orders for Code Generation

  Using in the **Code Generation** task

  ACL 2021 (CCF A)

- Dahal et al.[[Link](https://aclanthology.org/2021.findings-acl.384.pdf)] Analysis of Tree-Structured Architectures for Code Generation

  Using in the **Code Generation** task

  ACL 2021 (CCF A)

- Jiang et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9664314)] An AST Structure Enhanced Decoder for Code Generation

  Using in the **Code Generation** task

  IEEE/ACM Transactions on Audio, Speech, and Language Processing (CCF B)

- Huang et al.[[Link](https://aclanthology.org/2021.spnlp-1.7/)] A Globally Normalized Neural Model for Semantic Parsing

  Using in the **Code Generation** task

  SPNLP 2021

- Drain et al.[[Link](https://arxiv.org/pdf/2104.05310.pdf)] Generating Code with the Help of Retrieved Template Functions and Stack Overflow Answers

  Using in the **Code Generation** and **Code Search** task

  Arxiv

- Papanikolaou.[[Link](https://arxiv.org/pdf/2101.07138.pdf)] Teach me how to Label: Labeling Functions from Natural Language with Text-to-text Transformers

  Using in the **Code Generation** task

  Arxiv

- Washio and Miyao.[[Link](https://arxiv.org/pdf/2202.07806.pdf)] Code Generation for Unknown Libraries via Reading API Documentations

  Using in the **Code Generation** task

  Arxiv

- Wang and Wu.[[Link](https://link.springer.com/chapter/10.1007/978-3-030-87571-8_47)] The Code Generation Method Based on Gated Attention and InterAction-LSTM

  Using in the **Code Generation** task

  WISA 2021

------

### 1.6 CONCODE 2018

**Description:**

The corpus was collected from Stack Overflow. The authors thought that source code is rarely written in isolation. It depends significantly on the programmatic context, such as the class that the code would reside in. Thus this corpus contains over 100,000 examples (<class environment, NL, code> tuples) by gathering Java files containing method documentation from public Github repositories.

**Language(s):**

Java

**Contributor:**

Mapping Language to Code in Programmatic Context[[Link](https://aclanthology.org/D18-1192/)]

Using in the **Code Generation** task

EMNLP 2018 (CCF B)

**URL:**

https://github.com/sriniiyer/concode

**User(es):**

- Guo et al.[[Link](https://arxiv.org/pdf/1906.07108.pdf)] Coupling Retrieval and Meta-Learning for Context-Dependent Semantic Parsing

  Using in the **Code Generation** and **Code Search** task

  ACL 2019(CCF A)

- Hu et al.[[Link](https://link.springer.com/chapter/10.1007/978-3-030-36808-1_42)] Code Generation from Supervised Code Embeddings

  Using in the **Code Generation** task

  ICONIP 2019(CCF C)

- Wang et al.[[Link](https://aclanthology.org/2021.emnlp-main.685/)] CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation

  Using in the **Code Generation** task

  EMNLP 2021(CCF B)

- Ahmad et al.[Link] Unified Pre-training for Program Understanding and Generation

  Using in the **Code Generation** task

  NAACL 2021(CCF C)

- Parvez et al.[[Link](https://aclanthology.org/2021.findings-emnlp.232/)] Retrieval Augmented Code Generation and Summarization

  Using in the **Code Generation** task

  EMNLP 2021(CCF B)

- Phan et al.[[Link](https://arxiv.org/pdf/2105.08645.pdf)] CoTexT: Multi-task Learning with Code-Text Transformer

  Using in the **Code Generation** task

  NLP4Prog 2021

------

- 

------

### 1.7 CodeCS 2018

**Description:**

The corpus was collected from Github. For each Java method, the authors use the method declaration as the code element and the first sentence of its documentation comment as its natural language description. To prepare the data, they download Java projects from GitHub created from August, 2008 to June, 2016. To remove toy or experimental programs, they exclude any projects without a star. Finally, they obtain a corpus comprising 18,233,872 commented Java methods.

**Language(s):**

Java

**Contributor:**

Deep Code Search[[Link](https://ieeexplore.ieee.org/abstract/document/8453172)]

Using in the **Code Search** task

ICSE 2018 (CCF A)

**URL:**

https://drive.google.com/drive/folders/1GZYLT_lzhlVczXjD6dgwVUvDDPHMB6L7

https://pan.baidu.com/s/1U_MtFXqq0C-Qh8WUFAWGvg

**User(es):**

- Cambronero et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3338906.3340458)] When Deep Learning Met Code Search

  Using in the **Code Search** task

  FSE 2019 (CCF A)

-  Fang et al.[[Link](https://www.sciencedirect.com/science/article/pii/S0950584921000288)] Self-Attention Networks for Code Search

   Using in the **Code Search** task

   IST 2021 (CCF B)

------

### 1.8 CROKAGE 2018

**Description:**

The corpus was collected from Github. The authors collect a total of 3,889,303 questions and answers related to “Java” from Stack Overflow Q&A site. They parse these questions and answers and then separate texts and code using 'pre' and 'code' tags. They remove all punctuation symbols, stop words, small words (i.e., size lower than two) and numbers from them. This corpus contain not only relevant code examples but also their succinct explanations.  

**Language(s):**

Java

**Contributor:**

Recommending Comprehensive Solutions for Programming Tasks by Mining Crowd Knowledge [[Link](https://ieeexplore.ieee.org/abstract/document/8813288/)]

Using in the **Code Search** task

ICPC 2019 (CCF B)

**URL:**

https://github.com/muldon/CROKAGE-replication-package

**User(es):**

- Silva et al.[[Link](https://link.springer.com/article/10.1007/s10664-020-09863-2)] CROKAGE: effective solution recommendation for programming tasks by leveraging crowd knowledge

  Using in the **Code Search** task

  Empirical Software Engineering 2020(CCF B)

------

### 1.9 JuICe 2019

**Description:**

The corpus was collected from Github.  The authors filter for notebooks having NL markdown in English and Python 2/3 as their kernel type. Within these notebooks, each code cell is a potential training example, and the authors define the sequence of NL and code cells above it as its context. The authors only consider code cells that have NL markdown in the immediate previous cell (henceforth, target NL), as target cells. 

**Language(s):**

Jupyter Notebook

**Contributor:**

JuICe: A Large Scale Distantly Supervised Dataset for Open Domain Context-based Code Generation[[Link](https://aclanthology.org/D19-1546/)]

Using in the **Code Generation** task

EMNLP 2019 (CCF B)

**URL:**

https://github.com/rajasagashe/JuICe

**User(es):**

- Chen et al.[[Link](https://aclanthology.org/2021.acl-long.169.pdf)] PLOTCODER: Hierarchical Decoding for Synthesizing Visualization Code in Programmatic Context

  Using in the **Code Generation** task

  ACL 2021 (CCF A)

- Chandel et al.[[Link](https://arxiv.org/pdf/2201.12901.pdf)] Training and Evaluating a Jupyter Notebook Data Science Assistant

  Using in the **Code Generation** task

  Arxiv

------

### 1.10 NCS 2019

**Description:**



**Language(s):**

Java

**Contributor:**

Neural Code Search Evaluation Dataset [[Link](https://arxiv.org/pdf/1908.09804.pdf)]

Using in the **Code Search** task

Arxiv

**URL:**

https://github.com/facebookresearch/Neural-Code-Search-Evaluation-Dataset

**User(es):**

- Ling et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3447571)] Deep Graph Matching and Searching for Semantic Code Retrieval

  Using in the **Code Search** task

  ACM Transactions on Knowledge Discovery from Data

- Bader et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9360852)] AI in Software Engineering at Facebook

  Using in the **Code Search** task

  IEEE Software

------

### 1.11 CodeSearchNet

**Description:**



**Language(s):**

Go, Java, JavaScript, PHP, Python, and Ruby

**Contributor:**

CodeSearchNet Challenge: Evaluating the State of Semantic Code Search[[Link](https://arxiv.org/abs/1909.09436)]

Using in the **Code Search** task

Arxiv

**URL:**

https://github.com/github/CodeSearchNet

**User(es):**

- Ling et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3447571)] Deep Graph Matching and Searching for Semantic Code Retrieval

  Using in the **Code Search** task

  ACM Transactions on Knowledge Discovery from Data1.10 CosBench 2020

**Description:**

The corpus was collected from Github and StackOverflow. CosBench has three component: Codebase, QASet, and Metrics.

**Language(s):**

Java

**Contributor:**

Are the Code Snippets What We Are Searching for? A Benchmark and an Empirical Study on Code Search with Natural-Language Queries[[Link](https://ieeexplore.ieee.org/abstract/document/9054840)]

Using in the **Code Search** task

SANER 2020 (CCF B)

**URL:**

https://github.com/BASE-LAB-SJTU/CosBench/wiki

**User(es):**

- Li et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9240627)] Learning Code-Query Interaction for Enhancing Code Searches

  Using in the **Code Search** task

  ICSME 2020 (CCF B)

------

### 1.12 MucQC 2020

**Description:**

The corpus was collected from Stack Overflow data dumps. The authors first built the embedded library by using regular expressions to match different tags. The authors keep only posts containing multiple candidate code snippets, while removing candidate codes with length less than 10 in the corpus to keep the number of candidate codes. Finally, the authors use the CodeMF method to eliminate noisy posts and extract high-quality software libraries from programming forums.

**Language(s):**

Python & C#

**Contributor:**

Hierarchical Embedding for Code Search in Software Q&A Sites [[Link](https://ieeexplore.ieee.org/abstract/document/9207101)]

Using in the **Code Search** task

IJCNN 2020 (CCF C)

**URL:**

https://github.com/lrt366/HECS

**User(es):**

- Hu et al.[[Link](https://www.sciencedirect.com/science/article/pii/S0164121220301886)] Neural joint attention code search over structure embeddings for software Q&A sites

  Using in the **Code Search** task

  JSS (CCF B)

------

### 1.13 CoDesc 2021

**Description:**

The corpus was collected from a number of open source datasets. The authors spent 45-50 man-hours manually examining the dataset and developing data cleaning rules to identify noise patterns in the different data sources. Through group discussions, common patterns were identified and a noise removal method was established.

**Language(s):**

Java

**Contributor:**

CoDesc: A Large Code-Description Parallel Dataset [[Link](https://arxiv.org/abs/2105.14220)]

Using in the **Code Generation**  task

ACL 2021 (CCF A)

**URL:**

https://github.com/csebuetnlp/CoDesc

**User(es):**

Not found

------

### 1.14 CodeXGLUE 2021

**Description:**

The corpus was collected from a number of open source datasets. For the code search task, CodeSearchNet AdvTest, an adversarial sample dataset for python data, and WebQueryTest, a dataset for determining whether a given code needs to be queried, are proposed by cleaning the CodeSearchNet dataset. For code generation tasks, the authors have integrated CONCODE directly into CodeXGLUE.

**Language(s):**

Python & Java

**Contributor:**

CodeXGLUE: A Machine Learning Benchmark Dataset for Code Understanding and Generation [[Link](https://arxiv.org/abs/2102.04664)]

Using in the **Code Generation**  and **Code Search** task

NeurIPS 2021 (CCF A)

**URL:**

https://github.com/microsoft/CodeXGLUE

**User(es):**

- Ahmad et al.[Link] Unified Pre-training for Program Understanding and Generation

  Using in the **Code Generation** task

  NAACL 2021(CCF C)

- Roziere et al.[Link]DOBF: A Deobfuscation Pre-Training Objective for Programming Languages

  Using in the **Code Search** task

  Arxiv

- Parvez et al.[[Link](https://aclanthology.org/2021.findings-emnlp.232/)] Retrieval Augmented Code Generation and Summarization

  Using in the **Code Generation** task

  EMNLP 2021(CCF B)

------

### 1.15 PyTorrent 2021

**Description:**

The corpus was collected from PyPI and Anaconda packages, and the authors generate three augmented datasets: i) top-level docstring, ii) added user comments, and iii) added both full-docstring and user comments.

**Language(s):**

Python

**Contributor:**

PyTorrent: A Python Library Corpus for Large-scale Language Models[[Link](https://arxiv.org/abs/2110.01710)]

Using in the **Code Search** and **Code Generation** task

Arxiv

**URL:**

https://github.com/fla-sil/PyTorrent

**User(es):**

Not found

------

### 1.16 CoSQA 2021

**Description:**



**Language(s):**



**Contributor:**

CoSQA: 20,000+ Web Queries for Code Search and Question Answering [[Link](https://arxiv.org/abs/2105.13239)]

Using in the **Code Search** task

ACL 2021 (CCF A)

**URL:**

https://github.com/microsoft/CodeXGLUE/tree/main/Text-Code/NL-code-search-WebQuery

**User(es):**

- Liang et al.[[Link](https://arxiv.org/pdf/2201.07984.pdf)] AstBERT: Enabling Language Model for Code Understanding with Abstract Syntax Tree 

  Using in the **Code Generation** task

  Arxiv

