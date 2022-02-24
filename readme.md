

[TOC]

- [Ⅰ Introduce](#ⅰ--introduce)
- [Ⅱ Overview](#ⅱ--overview)
- [Ⅲ Details](#ⅲ--details)
  * [1. Common Programming Languages Code](#1-common-programming-languages-code)
    + [1.1 NLP2Code](#11-nlp2code)
    + [1.2 Code Docstring Corpus](#12-code-docstring-corpus)
    + [1.3 StaQC](#13-staqc)
    + [1.4 CoNaLa](#14-conala)
    + [1.5 CONCODE](#15-concode)
    + [1.6 JuICe](#16-juice)
    + [1.7 PyTorrent](#17-pytorrent)
    + [1.8 CodeSearchNet](#18-codesearchnet)
    + [1.9 CodeSC](#19-codesc)
    + [1.10 CosBench](#110-cosbench)
    + [1.11 CROKAGE](#111-crokage)
    + [1.12 MucQC](#112-mucqc)
  * [2. Domain Specific Languages Code](#2-domain-specific-languages-code)
    + [2.1 Information Search](#21-information-search)
      - [2.1.1 ATIS](#211-atis)
      - [2.1.2 JOBS](#212-jobs)
      - [2.1.3 GEO](#213-geo)
    + [2.2 Shell Code](#22-shell-code)
      - [2.2.1 NL2BASH](#221-nl2bash)
      - [2.2.2 NLC2CMD](#222-nlc2cmd)
      - [2.2.3 Shellcode_IA32](#223-shellcode-ia32)
    + [2.3 SQL Code](#23-sql-code)
      - [2.3.1 WiKiSQL](#231-wikisql)
      - [2.3.2 Spider](#232-spider)
      - [2.3.3 SParC](#233-sparc)
      - [2.3.4 CoSQL](#234-cosql)
      - [2.3.5 Lyra](#235-lyra)
    + [2.4 Regex Expression Code](#24-regex-expression-code)
      - [2.4.1 NL-RX](#241-nl-rx)
      - [2.4.2 KB13](#242-kb13)
      - [2.4.3 StructuredRegex](#243-structuredregex)
    + [2.5 Formal Representation Code](#25-formal-representation-code)
      - [2.5.1 IFTTT](#251-ifttt)
      - [2.5.2 WebQuestions](#252-webquestions)
      - [2.5.3 Overnight](#253-overnight)
  * [3. Programming Competition Code](#3-programming-competition-code)
    + [3.1 ReCa](#31-reca)
    + [3.2 DeepCoder](#32-deepcoder)
    + [3.3 NAPS](#33-naps)
    + [3.4 Python Solutions](#34-python-solutions)
  * [4. Pseudo Code](#4-pseudo-code)
    + [4.1 Django](#41-django)
    + [4.2 SPoC](#42-spoc)
  * [5. Card Game Code](#5-card-game-code)
    + [5.1 Hearthstone](#51-hearthstone)
    + [5.2 Magic](#52-magic)
  * [6. UI Code](#6-ui-code)
    + [6.1 pix2code](#61-pix2code)
    + [6.2 Plot2API](#62-plot2api)
    + [6.3 Im2latex-100k](#63-im2latex-100k)
    + [6.4 LaTeX Graphs](#64-latex-graphs)
    + [6.5 Android UI](#65-android-ui)
  * [7. Method Name](#7-method-name)
    + [7.1 MethodName](#71-methodname)
    + [7.2 FLOSS](#72-floss)


# Ⅰ Introduce

This is a repository for various popular corpora in the field of code generation/code search.

The corpus we have collected comes from these tasks: the input is natural language descriptions/UI images and the output is code snippets.

# Ⅱ Overview

We have divided the corpora into the following categories.

1. Common Programming Languages Code 
2. Domain Specific Languages Code
3. Programming Competition Code
4. Pseudo Code
5. Card Game Code
6. UI Code
7. Method Name

# Ⅲ Details

## 1. Common Programming Languages Code 

This category is mostly drawn from the open source community and contains several programming languages commonly used by developers.

```
Input: natural language descriptions
Output: code snippets for common programming languages
```

------

### 1.1 NLP2Code

**Description:**



**Language(s):**

Java

**Contributor:**

NLP2Code: Code Snippet Content Assist via Natural Language Tasks [[Link](https://ieeexplore.ieee.org/abstract/document/8094469)]

**URL:**

https://github.com/ctreude/nlp2code/tree/master/data

**User(es):**

Not found

------

### 1.2 Code Docstring Corpus

**Description:**



**Language(s):**

Python 2.7

**Contributor:**

A Parallel Corpus of Python Functions and Documentation Strings for Automated Code Documentation and Code Generation [[Link](https://aclanthology.org/I17-2053/)]

**URL:**

https://github.com/EdinburghNLP/code-docstring-corpus

**User(es):**

- Wang et al.[[Link]()] TranS3 : A Transformer-based Framework for Unifying Code Summarization and Code Search; 
- Zhou et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9609166/)] Assessing Generalizability of CodeBERT;  
- Zhao et al.[[Link](https://arxiv.org/abs/2201.08810)] GAP-Gen: Guided Automatic Python Code Generation

------

### 1.3 StaQC

**Description:**



**Language(s):**

Python & SQL

**Contributor:**

StaQC: A Systematically Mined Question-Code Dataset from Stack Overflow [[Link](https://dl.acm.org/doi/abs/10.1145/3178876.3186081)]

**URL:**

https://github.com/LittleYUYU/StackOverflow-Question-Code-Dataset

**User(es):**

- Zhao and Sun[[Link](https://aclanthology.org/2020.findings-emnlp.361/)];    
- Yao et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3308558.3313632)]; 
- Ye et al.[[Link](https://dl.acm.org/doi/abs/10.1145/3366423.3380295)]; 
- Zhu et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9285661)]; 
- Heyman et al.[[Link](https://arxiv.org/abs/2008.12193)]; 
- Hu et al.[[Link](https://www.sciencedirect.com/science/article/pii/S0164121220301886)]; 
- Martins and Gerosa[[Link](https://dl.acm.org/doi/abs/10.1145/3422392.3422462)]; 
- Wang et al.[[Link](https://arxiv.org/abs/2010.09520)]; 
- Li et al.[[Link](https://ieeexplore.ieee.org/abstract/document/9207101)]

------

### 1.4 CoNaLa

**Description:**



**Language(s):**

Python & Java

**Contributor:**

Learning to Mine Aligned Code and Natural Language Pairs from Stack Overflow [[Link](https://ieeexplore.ieee.org/abstract/document/8595231/)]

**URL:**

https://conala-corpus.github.io/#dataset-information

**User(es):**



------

### 1.5 CONCODE

**Description:**



**Language(s):**

Java

**Contributor:**

Mapping Language to Code in Programmatic Context[[Link](https://aclanthology.org/D18-1192/)]

**URL:**

https://github.com/sriniiyer/concode

**User(es):**



------

### 1.6 JuICe

**Description:**



**Language(s):**

Jupyter Notebook

**Contributor:**

JuICe: A Large Scale Distantly Supervised Dataset for Open Domain Context-based Code Generation[[Link](https://aclanthology.org/D19-1546/)]

**URL:**

https://github.com/rajasagashe/JuICe

**User(es):**



------

### 1.7 PyTorrent

**Description:**



**Language(s):**

Python

**Contributor:**

PyTorrent: A Python Library Corpus for Large-scale Language Models[[Link](https://arxiv.org/abs/2110.01710)]

**URL:**

https://github.com/fla-sil/PyTorrent

**User(es):**



------

### 1.8 CodeSearchNet

**Description:**



**Language(s):**

Go, Java, JavaScript, PHP, Python, and Ruby

**Contributor:**

CodeSearchNet Challenge: Evaluating the State of Semantic Code Search[[Link](https://arxiv.org/abs/1909.09436)]

**URL:**

https://github.com/github/CodeSearchNet

**User(es):**



------

### 1.9 CodeSC

**Description:**



**Language(s):**

Java

**Contributor:**

Deep Code Search[[Link](https://ieeexplore.ieee.org/abstract/document/8453172)]

**URL:**

https://drive.google.com/drive/folders/1GZYLT_lzhlVczXjD6dgwVUvDDPHMB6L7

https://pan.baidu.com/s/1U_MtFXqq0C-Qh8WUFAWGvg

**User(es):**



------

### 1.10 CosBench

**Description:**



**Language(s):**

Java

**Contributor:**

Are the Code Snippets What We Are Searching for? A Benchmark and an Empirical Study on Code Search with Natural-Language Queries[[Link](https://ieeexplore.ieee.org/abstract/document/9054840)]

**URL:**

https://github.com/BASE-LAB-SJTU/CosBench/wiki

**User(es):**



------

### 1.11 CROKAGE

**Description:**



**Language(s):**

Java

**Contributor:**

Recommending Comprehensive Solutions for Programming Tasks by Mining Crowd Knowledge [[Link](https://ieeexplore.ieee.org/abstract/document/8813288/)]

**URL:**

https://github.com/muldon/CROKAGE-replication-package

**User(es):**



------

### 1.12 MucQC

**Description:**



**Language(s):**

Python & C#

**Contributor:**

Hierarchical Embedding for Code Search in Software Q&A Sites [[Link](https://ieeexplore.ieee.org/abstract/document/9207101)]

**URL:**

https://github.com/lrt366/HECS

**User(es):**



------

## 2. Domain Specific Languages Code

This category is mostly drawn from open source communities, specific websites, and synthesis, and contains several domain-specific programming languages such as regular expressions, bash code, and SQL code.

```
Input: natural language descriptions
Output: code snippets for domain specific languages
```

------

### 2.1 Information Search

#### 2.1.1 ATIS

**Description:**



**Language(s):**



**Contributor:**

Expanding the scope of the ATIS task: The ATIS-3 corpus [[Link](https://aclanthology.org/H94-1010.pdf)]

**URL:**



**User(es):**



------

#### 2.1.2 JOBS

**Description:**



**Language(s):**



**Contributor:**

Using multiple clause constructors in inductive logic programming for semantic parsing [[Link](https://link.springer.com/chapter/10.1007/3-540-44795-4_40)]

**URL:**



**User(es):**



------

#### 2.1.3 GEO

**Description:**



**Language(s):**



**Contributor:**

Using multiple clause constructors in inductive logic programming for semantic parsing [[Link](https://link.springer.com/chapter/10.1007/3-540-44795-4_40)]

**URL:**



**User(es):**



------

### 2.2 Shell Code

#### 2.2.1 NL2BASH

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.2.2 NLC2CMD

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.2.3 Shellcode_IA32

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 2.3 SQL Code

#### 2.3.1 WiKiSQL

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.3.2 Spider

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.3.3 SParC

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.3.4 CoSQL

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.3.5 Lyra

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 2.4 Regex Expression Code

#### 2.4.1 NL-RX

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.4.2 KB13

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.4.3 StructuredRegex

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 2.5 Formal Representation Code

#### 2.5.1 IFTTT

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.5.2 WebQuestions

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

#### 2.5.3 Overnight

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

## 3. Programming Competition Code

This category, mostly from programming websites, comes with test cases to check the correctness of the code generated, in addition to the description of the code and the code itself.

```
Input: natural language descriptions
Output: code snippets with input/output test cases
```

------

### 3.1 ReCa

**Description:**



**Language(s):**

C/C++/Java/Python

**Contributor:**

Deep Learning Based Code Generation from Requirements Text: Are We There Yet? [[Link](https://ieeexplore.ieee.org/abstract/document/9173704/)]

**URL:**

https://github.com/ds4an/CoDas4CG/blob/master/Dataset/Dataset.zip

**User(es):**



------

### 3.2 DeepCoder

**Description:**



**Language(s):**

Custom DSL

**Contributor:**

DeepCoder: Learning to Write Programs [[Link](https://openreview.net/forum?id=ByldLrqlx)]

**URL:**

https://storage.googleapis.com/deepcoder/dataset.tar.gz

**User(es):**



------

### 3.3 NAPS

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 3.4 Python Solutions

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

## 4. Pseudo Code

This category mostly comes from hand-writing by developers and is based on the granularity of lines of code.

```
Input: pseudo code
Output: code (line-bu-line)
```

------

### 4.1 Django

**Description:**



**Language(s):**

Python

**Contributor:**



**URL:**



**User(es):**



------

### 4.2 SPoC

**Description:**



**Language(s):**

C++

**Contributor:**



**URL:**



**User(es):**



------

## 5. Card Game Code

Most of this category comes from the open source community and is based on code generation for card games.

```
Input: natural language descriptions for card
Output: card game code
```

------

### 5.1 Hearthstone

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 5.2 Magic

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

## 6. UI Code

This category mostly comes from hand-writing by developers and and is based on code generation for UI.

```
Input: UI images
Output: code
```

------

### 6.1 pix2code

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 6.2 Plot2API

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 6.3 Im2latex-100k

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 6.4 LaTeX Graphs

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 6.5 Android UI

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

## 7. Method Name

Most of this category comes from the open source community and is based on code generation for method name.

```
Input: natural language descriptions
Output: method name
```

------

### 7.1 MethodName

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 7.2 FLOSS

**Description:**



**Language(s):**



**Contributor:**



**URL:**



**User(es):**



------

### 
