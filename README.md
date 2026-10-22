# 📖 Language AI Handbook: From Foundations to Frontier Models

> **An interactive, code-first book and companion curriculum bridging classical Natural Language Processing (NLP) to modern Large Language Models (LLMs), Agentic workflows, and Compound AI Systems.**  
> *Companion interactive implementation guide based on Michael Brenndoerfer's renowned 20-volume work, [The Language AI Handbook](https://mbrenndoerfer.com/books/language-ai-handbook).*

<p align="center">
  <a href="https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/text-normalization.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="24">
  </a>
  &nbsp;
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white" alt="Python 3.10+">
  &nbsp;
  <img src="https://img.shields.io/badge/Jupyter-Interactive_Notebooks-orange.svg?logo=jupyter&logoColor=white" alt="Jupyter Notebooks">
  &nbsp;
  <img src="https://img.shields.io/badge/Curriculum-20_Volumes-purple.svg" alt="Curriculum: 20 Volumes">
</p>

---

## 🧭 About This Handbook

Welcome to the **Language AI Handbook** interactive laboratory. This repository is structured as a **comprehensive digital book**, providing executable companion notebooks for the complete foundational arc of language artificial intelligence—from the lowest-level character encodings and Unicode mechanics up through self-attention, scalable transformer training, reasoning models, and agent architectures.

Each chapter in this handbook is crafted with an uncompromising standard of depth:
- 🔬 **First-Principles Derivations & Code:** Algorithms are implemented from raw Python/NumPy before using abstractions, giving you complete mechanical transparency.
- ⚡ **Interactive Experiments & Visualizations:** Inspect byte layouts, visualize normalization matrices, observe token splits, and track gradient flow directly in code.
- 🛡️ **Production Realities & Security:** Learn the real-world pitfalls that break models in the wild—homograph spoofing, invisible Unicode control codes, zero-width spaces, tokenization collision hazards, and cross-lingual boundary failures.
- 📝 **Automated Self-Assessment Quizzes:** Interactive question widgets at the conclusion of notebooks with automated scoring and in-depth explanations.
- ☁️ **One-Click Google Colab Execution:** Every chapter notebook can be opened and run instantly in Google Colab without installing any local dependencies.

---

## 🗺️ Master Curriculum Overview (20 Volumes)

The handbook is divided into **20 specialized volumes** mirroring the natural trajectory from classical linguistics to frontier foundation models:

| Vol | Title | Focus Area | Status |
| :---: | :--- | :--- | :---: |
| **01** | **[Language Data and Classical NLP](#volume-1-language-data-and-classical-nlp)** | Encodings, normalization, tokenization, n-grams, TF-IDF, PMI, SVD | 🟢 **Active / In Progress** |
| **02** | **[Embeddings, Tokenization & Sequence Labeling](#volume-2-embeddings-tokenization-and-sequence-labeling)** | Word2Vec, FastText, GloVe, BPE, WordPiece, POS Tagging, NER, CRFs | 🟡 *Scaffolded* |
| **03** | **[Linguistic Structure and Meaning](#volume-3-linguistic-structure-and-meaning)** | Morphology, inflection, derivation, syntax & parsing | ⚪ *Planned* |
| **04** | **[Neural NLP and Sequence Models](#volume-4-neural-nlp-and-sequence-models)** | Linear classifiers, MLPs, backprop, RNNs, LSTMs, GRUs, Seq2Seq | ⚪ *Planned* |
| **05** | **[Transformers from First Principles](#volume-5-transformers-from-first-principles)** | Self-attention, QKV math, Multi-head attention, Positional encodings | ⚪ *Planned* |
| **06** | **[Efficient, Long-Context & Alternative Architectures](#volume-6-efficient-long-context-and-alternative-architectures)** | FlashAttention, Linear Attention, State Space Models (Mamba, RWKV) | ⚪ *Planned* |
| **07** | **[Pre-training Data and Scaling](#volume-7-pre-training-data-and-scaling)** | Web curation, filtering, synthetic data, Kaplan/Chinchilla scaling laws | ⚪ *Planned* |
| **08** | **[Encoder, Multilingual & Translation Models](#volume-8-encoder-multilingual-and-translation-models)** | BERT, RoBERTa, DeBERTa, Multilingual representations, Machine Translation | ⚪ *Planned* |
| **09** | **[Decoder Language Models and Capabilities](#volume-9-decoder-language-models-and-capabilities)** | Autoregressive generation, Prompting, In-context learning, Reasoning | ⚪ *Planned* |
| **10** | **[Large-Scale Training and Sparse Models](#volume-10-large-scale-training-and-sparse-models)** | Distributed training (FSDP, Megatron-LM), Mixture of Experts (MoE) | ⚪ *Planned* |
| **11** | **[Fine-tuning and Efficient Adaptation](#volume-11-fine-tuning-and-efficient-adaptation)** | Full fine-tuning, PEFT, LoRA, QLoRA, Prefix Tuning, Instruction tuning | ⚪ *Planned* |
| **12** | **[Alignment, Preferences, and Oversight](#volume-12-alignment-preferences-and-oversight)** | RLHF, PPO, DPO, KTO, Constitutional AI, RLAIF | ⚪ *Planned* |
| **13** | **[Reasoning and Verifiable Learning](#volume-13-reasoning-and-verifiable-learning)** | CoT, Tree of Thoughts, Self-consistency, Process Reward Models (PRMs) | ⚪ *Planned* |
| **14** | **[Efficient Inference and On-Device Models](#volume-14-efficient-inference-and-on-device-models)** | Quantization (AWQ/GPTQ), KV-cache, Speculative decoding, vLLM | ⚪ *Planned* |
| **15** | **[Retrieval, Knowledge, and Memory](#volume-15-retrieval-knowledge-and-memory)** | Dense retrieval, Bi-encoders, RAG, Hybrid search, Vector databases | ⚪ *Planned* |
| **16** | **[Agents and AI Coding Systems](#volume-16-agents-and-ai-coding-systems)** | Tool calling, ReAct, Agentic loops, MCP, Code generation & execution | ⚪ *Planned* |
| **17** | **[Speech, Multimodal, and Embodied Language](#volume-17-speech-multimodal-and-embodied-language)** | Whisper, Audio LLMs, Vision-Language Models (CLIP, LLaVA) | ⚪ *Planned* |
| **18** | **[Evaluation, Factuality, and Reliability](#volume-18-evaluation-factuality-and-reliability)** | Benchmarking (MMLU, GSM8K), LLM-as-a-judge, Hallucination detection | ⚪ *Planned* |
| **19** | **[Responsible, Secure, and Interpretable Language AI](#volume-19-responsible-secure-and-interpretable-language-ai)** | Jailbreak defenses, Prompt injection, Guardrails, Mechanistic interpretability | ⚪ *Planned* |
| **20** | **[Applications, Production, and Compound AI Systems](#volume-20-applications-production-and-compound-ai-systems)** | Production architecture, Caching, Observability, Staged releases | ⚪ *Planned* |
| **Appx** | **[State of Language AI 2025](#appendix-state-of-language-ai-2025)** | Frontier capabilities, open challenges, hardware & system landscape | ⚪ *Planned* |

---

## 📖 Book Table of Contents & Interactive Notebooks

### Volume 1: Language Data and Classical NLP
> *Language Data and Classical NLP covers foundational text representations, character encodings, text normalization forms, lexical counting, smoothing, statistical language models, and distributional vector spaces.*

#### Part I: Text as Data *(Active Notebooks)*

| Ch | Chapter Title & Core Topics | Interactive Notebook | Run in Colab | Reading Reference | Status |
| :---: | :--- | :---: | :---: | :---: | :---: |
| **01** | **Character Encoding**<br>_ASCII origins & 7-bit limits, Unicode code points & planes, UTF-8 variable-width encoding, Byte Order Marks (BOM), Endianness, Mojibake detection & repair in Python._ | [`character-encoding.ipynb`](Text%20as%20Data/character-encoding.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/character-encoding.ipynb) | [📖 Read Chapter](https://mbrenndoerfer.com/writing/character-encoding-ascii-unicode-utf8-nlp) | 🟡 Scaffolded |
| **02** | **Text Normalization**<br>_Unicode normalization forms (NFC, NFD, NFKC, NFKD), Case Folding vs Lowercasing, Accent & Diacritic stripping, Whitespace & Zero-Width spaces, Ligatures, Full/Half-width conversion, End-to-end normalization pipelines, Homograph spoofing security, Interactive 10-Question Quiz._ | [`text-normalization.ipynb`](Text%20as%20Data/text-normalization.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/text-normalization.ipynb) | [📖 Read Chapter](https://mbrenndoerfer.com/writing/text-normalization-unicode-nlp) | 🟢 Complete |
| **03** | **Regular Expressions**<br>_Regex syntax & metacharacters, character classes, quantifiers, grouping & backreferences, lookaround assertions, greedy vs lazy matching, common NLP extraction patterns (emails, dates, URLs), regex engine performance & ReDoS._ | [`regular-expressions.ipynb`](Text%20as%20Data/regular-expressions.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/regular-expressions.ipynb) | [📖 Read Chapter](https://mbrenndoerfer.com/writing/regular-expressions-pattern-matching-nlp-python) | ⚪ Planned |
| **04** | **Sentence Segmentation**<br>_Period disambiguation challenges, abbreviation handling, rule-based boundary detection, the Punkt sentence tokenizer algorithm, evaluation metrics, multilingual segmentation challenges._ | [`sentence-segmentation.ipynb`](Text%20as%20Data/sentence-segmentation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/sentence-segmentation.ipynb) | [📖 Read Chapter](https://mbrenndoerfer.com/writing/sentence-segmentation-punkt-algorithm-nlp) | ⚪ Planned |
| **05** | **Word Tokenization**<br>_Whitespace tokenization limitations, punctuation handling rules, contractions & clitics, language-specific challenges (Chinese, Japanese, German compounds), Penn Treebank tokenization standard, custom rule tokenizer design._ | [`word-tokenization.ipynb`](Text%20as%20Data/word-tokenization.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlstudy1010-engineer/Language-AI-Handbook/blob/main/Text%20as%20Data/word-tokenization.ipynb) | [📖 Read Chapter](https://mbrenndoerfer.com/writing/word-tokenization-nlp-guide) | ⚪ Planned |

#### Part II: Classical Text Representations

| Ch | Chapter Title & Core Topics | Planned Notebook | Reading Reference | Status |
| :---: | :--- | :---: | :---: | :---: |
| **06** | **Bag of Words**<br>_document-term matrix construction, vocabulary building from corpus, word counting and frequency vectors, sparse matrix representation (CSR/CSC formats), vocabulary pruning (min_df, max_df), binary vs count representations, limitations of word order loss._ | `bag-of-words-text-representation.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/bag-of-words-text-representation) | ⚪ Planned |
| **07** | **N-grams**<br>_bigram and trigram extraction, n-gram vocabulary explosion, n-gram frequency distributions, Zipf's law in n-grams, character n-grams for robustness, skip-grams and flexible windows, n-gram indexing for search._ | `n-grams-bigrams-trigrams-text-representation-nlp.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/n-grams-bigrams-trigrams-text-representation-nlp) | ⚪ Planned |
| **08** | **N-gram Language Models**<br>_Markov assumption and chain rule, maximum likelihood estimation, probability calculation for sequences, handling unseen n-grams, start and end tokens, generating text from n-gram models, model storage and lookup efficiency._ | `n-gram-language-models-probability-text-generation.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/n-gram-language-models-probability-text-generation) | ⚪ Planned |
| **09** | **Smoothing Techniques**<br>_add-one (Laplace) smoothing, add-k smoothing and tuning, Good-Turing smoothing derivation, Kneser-Ney smoothing intuition and formula, interpolation vs backoff, modified Kneser-Ney, comparing smoothing methods empirically._ | `smoothing-techniques-ngram-language-models-laplace-kneser-ney.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/smoothing-techniques-ngram-language-models-laplace-kneser-ney) | ⚪ Planned |
| **10** | **Perplexity**<br>_cross-entropy definition and derivation, perplexity as branching factor, relationship to bits-per-character, held-out evaluation methodology, perplexity vs downstream performance, comparing models with perplexity, perplexity limitations and caveats._ | `perplexity-language-model-evaluation-metric.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/perplexity-language-model-evaluation-metric) | ⚪ Planned |
| **11** | **Term Frequency**<br>_raw term frequency, log-scaled term frequency, boolean term frequency, augmented term frequency, L2-normalized frequency vectors, term frequency sparsity patterns, efficient term frequency computation._ | `term-frequency-weighting-schemes-text-analysis.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/term-frequency-weighting-schemes-text-analysis) | ⚪ Planned |
| **12** | **Inverse Document Frequency**<br>_document frequency calculation, IDF formula derivation, IDF intuition (rare words matter more), smoothed IDF variants, IDF across corpus splits, relationship to information theory, implementing IDF efficiently._ | `inverse-document-frequency-idf-text-weighting.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/inverse-document-frequency-idf-text-weighting) | ⚪ Planned |
| **13** | **TF-IDF**<br>_TF-IDF formula and variants, TF-IDF vector computation, TF-IDF normalization options, BM25 as TF-IDF extension, document similarity with TF-IDF, TF-IDF for feature extraction, sklearn TfidfVectorizer deep dive._ | `tf-idf-term-frequency-inverse-document-frequency-text-representation.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/tf-idf-term-frequency-inverse-document-frequency-text-representation) | ⚪ Planned |
| **14** | **BM25**<br>_BM25 derivation from probabilistic IR, saturation parameter k1, length normalization parameter b, BM25+ and BM25L variants, field-weighted BM25, implementing BM25 scoring, BM25 vs TF-IDF empirically._ | `bm25-search-algorithm-elasticsearch-implementation.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/bm25-search-algorithm-elasticsearch-implementation) | ⚪ Planned |

#### Part III: Distributional Semantics

| Ch | Chapter Title & Core Topics | Planned Notebook | Reading Reference | Status |
| :---: | :--- | :---: | :---: | :---: |
| **15** | **The Distributional Hypothesis**<br>_Firth's "you shall know a word by the company it keeps," distributional similarity intuition, context window definitions, paradigmatic vs syntagmatic relations, word similarity from distributions, limitations of distributional semantics._ | `distributional-hypothesis-word-meaning-context.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/distributional-hypothesis-word-meaning-context) | ⚪ Planned |
| **16** | **Co-occurrence Matrices**<br>_word-word co-occurrence matrices, word-document matrices, context window size effects, weighting by distance, symmetric vs directional contexts, matrix sparsity patterns, efficient construction algorithms._ | `co-occurrence-matrices-distributional-semantics-nlp.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/co-occurrence-matrices-distributional-semantics-nlp) | ⚪ Planned |
| **17** | **Pointwise Mutual Information**<br>_PMI formula derivation, PMI interpretation as association, positive PMI (PPMI), shifted PPMI variants, PMI matrix properties, PMI vs raw counts comparison, PMI for collocation extraction._ | `pointwise-mutual-information-word-associations-nlp.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/pointwise-mutual-information-word-associations-nlp) | ⚪ Planned |
| **18** | **Singular Value Decomposition**<br>_SVD mathematical formulation, truncated SVD for dimensionality reduction, LSA (Latent Semantic Analysis), choosing embedding dimensions, SVD computational complexity, randomized SVD for scale, interpreting SVD dimensions._ | `singular-value-decomposition-lsa-word-embeddings.ipynb` | [📖 Read Chapter](https://mbrenndoerfer.com/writing/singular-value-decomposition-lsa-word-embeddings) | ⚪ Planned |

---

### 📚 Full Curriculum: Volumes 2 through 20

Click on any volume below to expand its syllabus, learning objectives, and online reading references:

<details id="volume-2-embeddings-tokenization-and-sequence-labeling-3-parts-25-chapters">
<summary><b>📖 Volume 2 Embeddings, Tokenization, and Sequence Labeling 3 parts · 25 chapters (25 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **19** | **Skip-gram Model**<br>_skip-gram architecture diagram, input/output representations, softmax over vocabulary, skip-gram objective function, training data generation, window size hyperparameter, skip-gram vs CBOW intuition._ | [📖 Read Online](https://mbrenndoerfer.com/writing/skip-gram-model-word2vec-word-embeddings) | ⚪ Planned |
| **20** | **CBOW Model**<br>_CBOW architecture, context word averaging, CBOW objective function, CBOW vs skip-gram training speed, CBOW for frequent words, implementing CBOW forward pass, CBOW gradient derivation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/cbow-model-word2vec-word-embeddings) | ⚪ Planned |
| **21** | **Negative Sampling**<br>_softmax computational bottleneck, negative sampling objective derivation, sampling distribution (unigram^0.75), number of negatives hyperparameter, negative sampling gradient computation, NCE vs negative sampling, implementing efficient sampling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/negative-sampling-word-embeddings) | ⚪ Planned |
| **22** | **Hierarchical Softmax**<br>_binary tree construction (Huffman coding), path probability computation, hierarchical softmax objective, gradient computation along paths, tree structure impact on learning, hierarchical softmax vs negative sampling, when to use each approach._ | [📖 Read Online](https://mbrenndoerfer.com/writing/hierarchical-softmax-word-embeddings) | ⚪ Planned |
| **23** | **Word2Vec Training**<br>_data preprocessing pipeline, subsampling frequent words, learning rate scheduling, minibatch vs online training, convergence monitoring, gensim Word2Vec usage, training from scratch in PyTorch._ | [📖 Read Online](https://mbrenndoerfer.com/writing/training-word2vec-pipeline-gensim-pytorch-implementation) | ⚪ Planned |
| **24** | **Word Analogy**<br>_vector arithmetic for analogies, parallelogram model, analogy evaluation datasets, 3CosAdd vs 3CosMul methods, analogy accuracy metrics, limitations of analogy evaluation, what analogies reveal about embeddings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/word-analogy-vector-arithmetic-semantic-relationships) | ⚪ Planned |
| **25** | **GloVe**<br>_GloVe objective function derivation, weighted least squares formulation, relationship to matrix factorization, weighting function design, bias terms in GloVe, GloVe vs Word2Vec comparison, training GloVe efficiently._ | [📖 Read Online](https://mbrenndoerfer.com/writing/glove-word-embeddings-co-occurrence-matrix-factorization) | ⚪ Planned |
| **26** | **FastText**<br>_character n-gram representation, word vector as n-gram sum, FastText architecture, handling OOV words, morphological awareness, FastText for morphologically rich languages, training FastText models._ | [📖 Read Online](https://mbrenndoerfer.com/writing/fasttext-subword-embeddings-character-ngrams) | ⚪ Planned |
| **27** | **Embedding Evaluation**<br>_intrinsic vs extrinsic evaluation, word similarity datasets (SimLex, WordSim), analogy accuracy, embedding visualization (t-SNE, UMAP), downstream task evaluation, embedding bias detection, evaluation pitfalls._ | [📖 Read Online](https://mbrenndoerfer.com/writing/word-embedding-evaluation-intrinsic-extrinsic-methods) | ⚪ Planned |
| **28** | **The Vocabulary Problem**<br>_OOV word problem, vocabulary size explosion, rare word representation, morphological productivity, compound words, code and technical text, the case for subword units._ | [📖 Read Online](https://mbrenndoerfer.com/writing/vocabulary-problem-subword-tokenization-challenges) | ⚪ Planned |
| **29** | **Byte Pair Encoding**<br>_BPE algorithm step-by-step, merge rules learning, vocabulary size control, BPE encoding procedure, BPE decoding procedure, BPE implementation from scratch, BPE hyperparameters._ | [📖 Read Online](https://mbrenndoerfer.com/writing/byte-pair-encoding-subword-tokenization-guide) | ⚪ Planned |
| **30** | **WordPiece**<br>_WordPiece vs BPE differences, likelihood objective for merges, greedy tokenization algorithm, ## prefix notation, WordPiece in BERT, training WordPiece tokenizers, handling unknown characters._ | [📖 Read Online](https://mbrenndoerfer.com/writing/wordpiece-tokenization-bert-subword-algorithm) | ⚪ Planned |
| **31** | **Unigram Language Model Tokenization**<br>_unigram LM formulation, EM algorithm for training, Viterbi decoding for tokenization, sampling multiple segmentations, subword regularization, unigram vs BPE comparison, SentencePiece unigram mode._ | [📖 Read Online](https://mbrenndoerfer.com/writing/unigram-language-model-tokenization) | ⚪ Planned |
| **32** | **SentencePiece**<br>_treating text as raw bytes, whitespace handling (▁ prefix), BPE and unigram modes, training from raw text, pretokenization elimination, SentencePiece in production, multilingual tokenization._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sentencepiece-subword-tokenization-bpe-unigram) | ⚪ Planned |
| **33** | **Tokenizer Training**<br>_corpus preparation, vocabulary size selection, special tokens configuration, training with HuggingFace tokenizers, saving and loading tokenizers, tokenizer versioning, domain-specific tokenizers._ | [📖 Read Online](https://mbrenndoerfer.com/writing/tokenizer-training-guide-huggingface-custom-nlp) | ⚪ Planned |
| **34** | **Special Tokens**<br>_[CLS], [SEP], [PAD], [MASK], [UNK] tokens, beginning/end of sequence tokens, custom special tokens, special token embeddings, token type IDs, handling special tokens in generation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/special-tokens-transformers-cls-sep-pad-mask) | ⚪ Planned |
| **35** | **Tokenization Challenges**<br>_number tokenization issues, code tokenization, multilingual text mixing, emoji and Unicode edge cases, tokenization artifacts, adversarial tokenization, measuring tokenization quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/tokenization-challenges-numbers-code-multilingual-unicode) | ⚪ Planned |
| **36** | **Part-of-Speech Tagging**<br>_POS tag sets (Penn Treebank, Universal), POS tagging as classification, contextual disambiguation, POS tagging accuracy metrics, POS tagging for downstream tasks, rule-based vs statistical taggers._ | [📖 Read Online](https://mbrenndoerfer.com/writing/part-of-speech-tagging-nlp-guide) | ⚪ Planned |
| **37** | **Named Entity Recognition**<br>_entity types (PER, ORG, LOC, etc.), NER as sequence labeling, nested entity challenges, entity boundary detection, NER evaluation (exact vs partial match), NER datasets and benchmarks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/named-entity-recognition-ner-tutorial) | ⚪ Planned |
| **38** | **BIO Tagging**<br>_BIO scheme explanation, BIOES/BILOU variants, converting spans to BIO tags, BIO decoding to spans, handling tagging inconsistencies, BIO for multi-label scenarios, implementing BIO utilities._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bio-tagging-sequence-labeling-ner) | ⚪ Planned |
| **39** | **Chunking**<br>_noun phrase chunking, chunk types (NP, VP, PP), IOB tagging for chunks, chunking vs full parsing, chunking evaluation, chunking as preprocessing, regex chunking with NLTK._ | [📖 Read Online](https://mbrenndoerfer.com/writing/chunking-shallow-parsing-nlp) | ⚪ Planned |
| **40** | **Hidden Markov Models**<br>_HMM components (states, observations, transitions), emission and transition probabilities, HMM assumptions (Markov, independence), HMM for POS tagging, HMM parameter estimation, HMM limitations for NLP._ | [📖 Read Online](https://mbrenndoerfer.com/writing/hidden-markov-models-sequence-labeling-nlp) | ⚪ Planned |
| **41** | **Viterbi Algorithm**<br>_optimal path problem formulation, Viterbi recursion derivation, backpointer tracking, Viterbi complexity analysis, log-space computation, implementing Viterbi efficiently, Viterbi for beam search foundation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/viterbi-algorithm-sequence-labeling) | ⚪ Planned |
| **42** | **Conditional Random Fields**<br>_CRF vs HMM comparison, CRF feature functions, log-linear formulation, partition function computation, CRF for NER, CRF inference complexity, neural CRF layers._ | [📖 Read Online](https://mbrenndoerfer.com/writing/conditional-random-fields-sequence-labeling-nlp) | ⚪ Planned |
| **43** | **CRF Training**<br>_CRF log-likelihood objective, forward-backward algorithm, gradient computation, L-BFGS optimization, feature template design, CRF regularization, CRF training convergence._ | [📖 Read Online](https://mbrenndoerfer.com/writing/crf-training-forward-backward-lbfgs-optimization) | ⚪ Planned |

</details>

<details id="volume-3-linguistic-structure-and-meaning-1-part-2-chapters">
<summary><b>📖 Volume 3 Linguistic Structure and Meaning 1 part · 2 chapters (2 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **44** | **Morphology and Word Formation Morphemes, inflection, derivation, compounding, and why word structure matters for language models.** | [📖 Read Online](https://mbrenndoerfer.com/writing/morphology-word-formation-language-models) | ⚪ Planned |
| **45** | **Morphological Analysis and Generation Finite-state and neural approaches to analyzing and generating morphologically rich language.** | [📖 Read Online](https://mbrenndoerfer.com/writing/morphological-analysis-generation-nlp) | ⚪ Planned |

</details>

<details id="volume-4-neural-nlp-and-sequence-models-3-parts-29-chapters">
<summary><b>📖 Volume 4 Neural NLP and Sequence Models 3 parts · 29 chapters (29 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **61** | **Linear Classifiers**<br>_linear decision boundaries, weight vectors and bias, dot product interpretation, multiclass classification (softmax), linear classifier limitations, training with gradient descent._ | [📖 Read Online](https://mbrenndoerfer.com/writing/linear-classifiers-neural-network-foundations) | ⚪ Planned |
| **62** | **Activation Functions**<br>_sigmoid function and saturation, tanh properties, ReLU and dying ReLU, Leaky ReLU and PReLU, ELU and SELU, GELU derivation and properties, Swish and Mish, choosing activation functions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/activation-functions-neural-networks-complete-guide) | ⚪ Planned |
| **63** | **Multilayer Perceptrons**<br>_hidden layers and depth, weight matrices between layers, forward pass computation, representational capacity, MLP for classification, MLP for regression, MLP architecture design._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multilayer-perceptrons-neural-networks) | ⚪ Planned |
| **64** | **Loss Functions**<br>_cross-entropy loss derivation, MSE for regression, binary vs multiclass cross-entropy, label smoothing, focal loss for imbalance, loss function numerical stability, custom loss functions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/neural-network-loss-functions-guide) | ⚪ Planned |
| **65** | **Backpropagation**<br>_computational graphs, chain rule review, forward and backward pass, gradient accumulation, backprop complexity analysis, automatic differentiation, implementing backprop from scratch._ | [📖 Read Online](https://mbrenndoerfer.com/writing/backpropagation-algorithm-deep-learning-neural-networks) | ⚪ Planned |
| **66** | **Stochastic Gradient Descent**<br>_batch vs stochastic gradient descent, minibatch gradient descent, learning rate selection, SGD convergence properties, SGD noise as regularization, learning rate schedules basics, SGD implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/stochastic-gradient-descent-neural-network-optimization) | ⚪ Planned |
| **67** | **Momentum**<br>_momentum intuition (ball rolling), momentum update equations, momentum coefficient selection, dampening oscillations, momentum vs vanilla SGD, Nesterov momentum derivation, implementing momentum._ | [📖 Read Online](https://mbrenndoerfer.com/writing/momentum-neural-network-optimization) | ⚪ Planned |
| **68** | **Adam Optimizer**<br>_exponential moving averages, first moment (mean) estimation, second moment (variance) estimation, bias correction derivation, Adam update rule, Adam hyperparameters, Adam convergence properties._ | [📖 Read Online](https://mbrenndoerfer.com/writing/adam-optimizer-deep-learning) | ⚪ Planned |
| **69** | **AdamW**<br>_L2 regularization vs weight decay, why they differ with Adam, AdamW formulation, weight decay coefficient selection, AdamW as default optimizer, AdamW vs Adam empirically._ | [📖 Read Online](https://mbrenndoerfer.com/writing/adamw-optimizer-decoupled-weight-decay) | ⚪ Planned |
| **70** | **Weight Initialization**<br>_random initialization importance, Xavier/Glorot initialization derivation, He initialization for ReLU, initialization for different activations, layer-wise initialization, initialization debugging, modern initialization practices._ | [📖 Read Online](https://mbrenndoerfer.com/writing/weight-initialization-neural-networks-xavier-he) | ⚪ Planned |
| **71** | **Batch Normalization**<br>_internal covariate shift, batch statistics computation, learnable scale and shift, training vs inference mode, batch norm gradient flow, batch norm placement debates, batch norm limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/batch-normalization-deep-learning) | ⚪ Planned |
| **72** | **Dropout**<br>_dropout as ensemble, dropout mask sampling, inverted dropout scaling, dropout rate selection, dropout at inference, spatial dropout for sequences, dropout in modern architectures._ | [📖 Read Online](https://mbrenndoerfer.com/writing/dropout-neural-network-regularization) | ⚪ Planned |
| **73** | **Gradient Clipping**<br>_gradient explosion detection, clip by value, clip by global norm, gradient clipping implementation, when to use gradient clipping, clipping threshold selection, monitoring gradient norms._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gradient-clipping-deep-learning) | ⚪ Planned |
| **74** | **RNN Architecture**<br>_recurrent connection intuition, hidden state as memory, unrolled computation graph, parameter sharing across time, RNN for sequence classification, RNN for sequence generation, RNN equations and dimensions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rnn-architecture-recurrent-neural-networks-guide) | ⚪ Planned |
| **75** | **Backpropagation Through Time**<br>_BPTT derivation, gradient flow through time, truncated BPTT, BPTT memory requirements, BPTT implementation, gradient accumulation across timesteps._ | [📖 Read Online](https://mbrenndoerfer.com/writing/backpropagation-through-time-rnn-training-algorithm) | ⚪ Planned |
| **76** | **Vanishing Gradients**<br>_gradient product across timesteps, vanishing gradient analysis, long-range dependency failure, gradient visualization, vanishing vs exploding trade-off, architectural solutions overview._ | [📖 Read Online](https://mbrenndoerfer.com/writing/vanishing-gradients-rnn-long-range-dependencies) | ⚪ Planned |
| **77** | **LSTM Architecture**<br>_cell state as information highway, gate mechanism intuition, LSTM diagram walkthrough, information flow in LSTMs, LSTM for long sequences, LSTM memory capacity._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lstm-architecture-recurrent-neural-networks-guide) | ⚪ Planned |
| **78** | **LSTM Gate Equations**<br>_forget gate equations, input gate equations, cell state update, output gate equations, hidden state computation, LSTM parameter count, implementing LSTM from scratch._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lstm-gate-equations-mathematical-guide-implementation) | ⚪ Planned |
| **79** | **LSTM Gradient Flow**<br>_constant error carousel, forget gate gradient highway, gradient flow analysis, LSTM vs vanilla RNN gradients, peephole connections, LSTM gradient clipping needs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lstm-gradient-flow-constant-error-carousel) | ⚪ Planned |
| **80** | **GRU Architecture**<br>_GRU vs LSTM comparison, reset gate function, update gate function, candidate hidden state, GRU equations, GRU parameter efficiency, when to choose GRU vs LSTM._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gru-architecture-gated-recurrent-units) | ⚪ Planned |
| **81** | **Bidirectional RNNs**<br>_forward and backward passes, hidden state concatenation, bidirectional architectures, bidirectionality for classification, limitations for generation, implementing bidirectional RNNs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bidirectional-rnns-full-sequence-context-nlp) | ⚪ Planned |
| **82** | **Stacked RNNs**<br>_multiple RNN layers, residual connections for depth, layer normalization in RNNs, depth vs width trade-offs, gradient flow in deep RNNs, practical depth limits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/stacked-rnns-deep-recurrent-networks-hierarchical-modeling) | ⚪ Planned |
| **83** | **Encoder-Decoder Framework**<br>_encoder role and design, decoder role and design, context vector as bottleneck, seq2seq for machine translation, seq2seq for summarization, seq2seq training setup._ | [📖 Read Online](https://mbrenndoerfer.com/writing/encoder-decoder-framework-seq2seq-architecture-machine-translation) | ⚪ Planned |
| **84** | **Teacher Forcing**<br>_teacher forcing procedure, exposure bias problem, teacher forcing efficiency, scheduled sampling, curriculum learning, teacher forcing vs autoregressive training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/teacher-forcing-seq2seq-training-exposure-bias-scheduled-sampling) | ⚪ Planned |
| **85** | **Beam Search**<br>_greedy decoding limitations, beam search algorithm, beam width selection, length normalization, diverse beam search, beam search implementation, beam search vs sampling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/beam-search-decoding-sequence-generation) | ⚪ Planned |
| **86** | **Attention Intuition**<br>_attention as soft lookup, attention weight interpretation, attention for variable-length inputs, attention visualization, attention vs pooling, attention computation overview._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-mechanism-intuition-soft-lookup-weights-context-vectors) | ⚪ Planned |
| **87** | **Bahdanau Attention**<br>_alignment model formulation, score function (additive), attention weight computation, context vector as weighted sum, attention in decoder, Bahdanau attention implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bahdanau-attention-neural-machine-translation) | ⚪ Planned |
| **88** | **Luong Attention**<br>_dot product attention, general (bilinear) attention, concat attention variant, global vs local attention, Luong vs Bahdanau comparison, attention placement (input vs output)._ | [📖 Read Online](https://mbrenndoerfer.com/writing/luong-attention-mechanisms-dot-product-general-local) | ⚪ Planned |
| **89** | **Copy Mechanism**<br>_pointer network motivation, copy probability computation, mixing generation and copying, pointer-generator networks, copy mechanism for summarization, OOV handling with copy._ | [📖 Read Online](https://mbrenndoerfer.com/writing/copy-mechanism-pointer-networks-text-generation) | ⚪ Planned |

</details>

<details id="volume-5-transformers-from-first-principles-4-parts-27-chapters">
<summary><b>📖 Volume 5 Transformers from First Principles 4 parts · 27 chapters (27 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **90** | **Self-Attention Concept**<br>_cross-attention vs self-attention, self-attention motivation, all-pairs interaction, self-attention for representation learning, self-attention computational pattern._ | [📖 Read Online](https://mbrenndoerfer.com/writing/self-attention-concept) | ⚪ Planned |
| **91** | **Query, Key, Value**<br>_QKV intuition (database lookup), projection matrices Wq, Wk, Wv, query-key matching, value retrieval, QKV dimensions and shapes, QKV as learned transformations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/query-key-value-attention-mechanism) | ⚪ Planned |
| **92** | **Scaled Dot-Product Attention**<br>_dot product for similarity, softmax for normalization, scaling factor derivation (1/√dk), attention output computation, attention in matrix form, attention implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/scaled-dot-product-attention-transformer-mechanism) | ⚪ Planned |
| **93** | **Attention Masking**<br>_padding masks, causal (look-ahead) masks, combining multiple masks, mask shapes and broadcasting, efficient masking implementation, custom attention patterns._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-masking-transformers) | ⚪ Planned |
| **94** | **Multi-Head Attention**<br>_multiple attention heads motivation, head dimension splitting, parallel attention computation, output concatenation and projection, head specialization, multi-head vs single head._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multi-head-attention-transformers) | ⚪ Planned |
| **95** | **Attention Complexity**<br>_O(n²) attention complexity, memory requirements, attention bottleneck in long sequences, FLOPs computation, attention vs RNN complexity, practical scaling limits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-complexity-quadratic-scaling-memory-efficient-transformers) | ⚪ Planned |
| **96** | **Position Problem**<br>_transformer position blindness, why position matters for language, position information requirements, position encoding vs position embedding, absolute vs relative position._ | [📖 Read Online](https://mbrenndoerfer.com/writing/position-problem-self-attention-word-order) | ⚪ Planned |
| **97** | **Sinusoidal Position Encoding**<br>_sinusoidal formula derivation, wavelength intuition, position encoding visualization, extrapolation properties, sinusoidal encoding implementation, learned vs sinusoidal trade-offs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sinusoidal-position-encoding-transformers-word-order) | ⚪ Planned |
| **98** | **Learned Position Embeddings**<br>_position embedding table, position embedding training, maximum sequence length, learned embedding extrapolation, position embedding analysis, GPT-style position embeddings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/learned-position-embeddings) | ⚪ Planned |
| **99** | **Relative Position Encoding**<br>_relative position motivation, relative attention formulation, clipping relative positions, relative position in self-attention, Shaw et al. relative positions, relative bias implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/relative-position-encoding-transformers) | ⚪ Planned |
| **100** | **Rotary Position Embedding (RoPE)**<br>_RoPE intuition, rotation matrix formulation, RoPE in complex numbers, relative position through rotation, RoPE implementation, RoPE frequency patterns._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rotary-position-embedding-rope-transformers) | ⚪ Planned |
| **101** | **ALiBi**<br>_ALiBi motivation, linear bias by distance, head-specific slopes, ALiBi extrapolation properties, ALiBi simplicity advantages, ALiBi vs RoPE comparison._ | [📖 Read Online](https://mbrenndoerfer.com/writing/alibi-attention-linear-biases-position-encoding) | ⚪ Planned |
| **102** | **Position Encoding Comparison**<br>_extrapolation benchmarks, training efficiency comparison, implementation complexity, position encoding for long context, hybrid approaches, current best practices._ | [📖 Read Online](https://mbrenndoerfer.com/writing/position-encoding-comparison-transformers) | ⚪ Planned |
| **103** | **Residual Connections**<br>_residual connection formulation, gradient highway interpretation, residual scaling, residual connections in transformers, pre-norm vs post-norm residuals._ | [📖 Read Online](https://mbrenndoerfer.com/writing/residual-connections-gradient-highways-deep-transformers) | ⚪ Planned |
| **104** | **Layer Normalization**<br>_layer norm vs batch norm, layer norm formula, learnable affine parameters, layer norm placement, layer norm gradient flow, layer norm implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/layer-normalization-transformers-implementation) | ⚪ Planned |
| **105** | **RMSNorm**<br>_RMSNorm derivation, removing mean centering, RMSNorm efficiency, RMSNorm vs LayerNorm performance, RMSNorm in modern architectures._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rmsnorm-efficient-normalization-modern-llms) | ⚪ Planned |
| **106** | **Pre-Norm vs Post-Norm**<br>_original transformer (post-norm), pre-norm formulation, training stability comparison, gradient flow differences, when to use each, modern consensus._ | [📖 Read Online](https://mbrenndoerfer.com/writing/pre-norm-vs-post-norm) | ⚪ Planned |
| **107** | **Feed-Forward Networks**<br>_FFN architecture, hidden dimension expansion, FFN as two linear layers, position independence, FFN parameter count, FFN computational cost._ | [📖 Read Online](https://mbrenndoerfer.com/writing/transformer-feed-forward-networks) | ⚪ Planned |
| **108** | **FFN Activation Functions**<br>_ReLU in original transformer, GELU adoption, GELU approximations, SiLU/Swish in modern models, activation function comparison._ | [📖 Read Online](https://mbrenndoerfer.com/writing/ffn-activation-functions) | ⚪ Planned |
| **109** | **Gated Linear Units**<br>_GLU formulation, gating mechanism, SwiGLU derivation, GeGLU variant, GLU parameter efficiency, GLU in modern architectures._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gated-linear-units-swiglu-transformer-ffn) | ⚪ Planned |
| **110** | **Transformer Block Assembly**<br>_standard block structure, component ordering, block implementation, block initialization, forward pass walkthrough, block hyperparameters._ | [📖 Read Online](https://mbrenndoerfer.com/writing/transformer-block-assembly) | ⚪ Planned |
| **111** | **Encoder Architecture**<br>_encoder-only design, bidirectional self-attention, encoder for understanding tasks, encoder output usage, BERT-style encoder, encoder layer stacking._ | [📖 Read Online](https://mbrenndoerfer.com/writing/encoder-architecture-bidirectional-transformers-understanding) | ⚪ Planned |
| **112** | **Decoder Architecture**<br>_decoder-only design, causal masking requirement, autoregressive generation, decoder for generation tasks, GPT-style decoder, decoder layer stacking._ | [📖 Read Online](https://mbrenndoerfer.com/writing/decoder-architecture-causal-masking-autoregressive-transformers) | ⚪ Planned |
| **113** | **Encoder-Decoder Architecture**<br>_encoder-decoder interaction, cross-attention mechanism, encoder-decoder for seq2seq, T5-style architecture, information flow, when to use encoder-decoder._ | [📖 Read Online](https://mbrenndoerfer.com/writing/encoder-decoder-architecture-cross-attention-transformers) | ⚪ Planned |
| **114** | **Cross-Attention**<br>_cross-attention formulation, KV from encoder, Q from decoder, cross-attention masking, cross-attention placement, cross-attention implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/cross-attention-encoder-decoder-transformers) | ⚪ Planned |
| **115** | **Weight Tying**<br>_input-output embedding tying, encoder-decoder tying, parameter reduction, weight tying effects on training, when to tie weights._ | [📖 Read Online](https://mbrenndoerfer.com/writing/weight-tying-shared-embeddings-transformers) | ⚪ Planned |
| **116** | **Architecture Hyperparameters**<br>_depth vs width trade-offs, number of heads selection, hidden dimension ratios, FFN expansion ratio, total parameter calculation, architecture search._ | [📖 Read Online](https://mbrenndoerfer.com/writing/transformer-architecture-hyperparameters-design-guide) | ⚪ Planned |

</details>

<details id="volume-6-efficient-long-context-and-alternative-architectures-2-parts-16-chapters">
<summary><b>📖 Volume 6 Efficient, Long-Context, and Alternative Architectures 2 parts · 16 chapters (16 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **117** | **Quadratic Attention Bottleneck**<br>_O(n²) memory analysis, O(n²) compute analysis, attention matrix size, practical sequence limits, bottleneck visualization, motivation for efficiency._ | [📖 Read Online](https://mbrenndoerfer.com/writing/quadratic-attention-bottleneck-transformers-long-sequences) | ⚪ Planned |
| **118** | **Sparse Attention Patterns**<br>_local attention windows, strided attention patterns, block-sparse attention, combining sparse patterns, sparse attention implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sparse-attention-patterns-efficient-transformers) | ⚪ Planned |
| **119** | **Sliding Window Attention**<br>_sliding window formulation, window size selection, dilated sliding windows, sliding window for long sequences, Mistral-style windowed attention._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sliding-window-attention) | ⚪ Planned |
| **120** | **Global Tokens**<br>_CLS token global attention, learned global tokens, global-local attention mixing, global token count, implementation strategies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/global-tokens-efficient-transformers-long-range-attention) | ⚪ Planned |
| **121** | **Longformer**<br>_Longformer attention pattern, global attention configuration, Longformer complexity, Longformer for documents, Longformer implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/longformer-efficient-attention-long-documents) | ⚪ Planned |
| **122** | **BigBird**<br>_BigBird attention pattern, random attention benefits, BigBird theoretical guarantees, BigBird vs Longformer, BigBird applications._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bigbird-sparse-attention-random-connections-long-documents) | ⚪ Planned |
| **123** | **Linear Attention**<br>_softmax attention reformulation, kernel feature maps, linear complexity attention, linear attention limitations, Performer and variants._ | [📖 Read Online](https://mbrenndoerfer.com/writing/linear-attention-kernel-feature-maps-efficient-transformers) | ⚪ Planned |
| **124** | **FlashAttention Algorithm**<br>_GPU memory hierarchy, tiling for SRAM, online softmax computation, recomputation strategy, FlashAttention complexity, FlashAttention benefits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/flashattention-algorithm-memory-efficient-gpu-tiling) | ⚪ Planned |
| **125** | **FlashAttention Implementation**<br>_CUDA kernel basics, memory access patterns, FlashAttention-2 improvements, using FlashAttention in PyTorch, FlashAttention limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/flashattention-implementation-gpu-memory-optimization) | ⚪ Planned |
| **126** | **Context Length Challenges**<br>_training sequence length limits, attention memory scaling, position encoding extrapolation, long-range dependency learning, evaluation challenges._ | [📖 Read Online](https://mbrenndoerfer.com/writing/context-length-challenges-transformers) | ⚪ Planned |
| **127** | **Position Interpolation**<br>_linear position scaling, interpolation vs extrapolation, position interpolation implementation, fine-tuning for longer context, interpolation limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/position-interpolation-rope-context-extension) | ⚪ Planned |
| **128** | **NTK-aware Scaling**<br>_RoPE frequency analysis, high-frequency preservation, NTK-aware formula, dynamic NTK scaling, NTK vs linear interpolation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/ntk-aware-scaling-context-extension) | ⚪ Planned |
| **129** | **YaRN**<br>_YaRN motivation, attention scaling factor, YaRN formula, YaRN training requirements, YaRN vs alternatives._ | [📖 Read Online](https://mbrenndoerfer.com/writing/yarn-rope-context-extension-llm) | ⚪ Planned |
| **130** | **Attention Sinks**<br>_attention sink phenomenon, StreamingLLM approach, sink token design, streaming inference, infinite context generation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-sinks-streamingllm-infinite-generation) | ⚪ Planned |
| **131** | **Memory Augmentation**<br>_memory network concepts, memory retrieval mechanisms, memory writing and updating, memory-augmented transformers, Memorizing Transformers._ | [📖 Read Online](https://mbrenndoerfer.com/writing/memory-augmentation-transformers-long-context) | ⚪ Planned |
| **132** | **Recurrent Memory**<br>_Transformer-XL approach, segment-level processing, recurrent state passing, relative position in recurrence, recurrent memory limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/recurrent-memory-transformer-xl-segment-recurrence) | ⚪ Planned |

</details>

<details id="volume-7-pre-training-data-and-scaling-3-parts-24-chapters">
<summary><b>📖 Volume 7 Pre-training Data and Scaling 3 parts · 24 chapters (24 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **139** | **Web Crawling**<br>_Common Crawl, crawling strategies, robots.txt respect, crawl freshness._ | [📖 Read Online](https://mbrenndoerfer.com/writing/web-crawling-common-crawl-strategies-robots-txt) | ⚪ Planned |
| **140** | **Document Extraction**<br>_HTML parsing, boilerplate removal, content extraction, trafilatura and similar tools._ | [📖 Read Online](https://mbrenndoerfer.com/writing/document-extraction-html-parsing-boilerplate-removal-trafilatura) | ⚪ Planned |
| **141** | **Language Identification**<br>_language ID models, multilingual document handling, code-switching, language filtering._ | [📖 Read Online](https://mbrenndoerfer.com/writing/language-identification-models-multilingual-code-switching) | ⚪ Planned |
| **142** | **Deduplication**<br>_exact deduplication, near-duplicate detection, document vs substring dedup, dedup at scale._ | [📖 Read Online](https://mbrenndoerfer.com/writing/deduplication-exact-near-duplicate-jaccard-similarity-suffix-arrays) | ⚪ Planned |
| **143** | **MinHash**<br>_MinHash algorithm, Jaccard similarity estimation, MinHash LSH, MinHash implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/minhash-algorithm-jaccard-similarity-lsh-deduplication) | ⚪ Planned |
| **144** | **Quality Filtering**<br>_heuristic filters, perplexity filtering, classifier-based filtering, filter thresholds._ | [📖 Read Online](https://mbrenndoerfer.com/writing/quality-filtering-heuristic-perplexity-classifier-thresholds) | ⚪ Planned |
| **145** | **Toxicity Filtering**<br>_toxicity classifiers, toxicity thresholds, over-filtering risks, toxicity filter evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/toxicity-filtering-classifiers-thresholds-over-filtering-risks) | ⚪ Planned |
| **146** | **PII Removal**<br>_PII detection methods, PII removal strategies, PII removal evaluation, privacy preservation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/pii-removal-detection-strategies-privacy-preservation-llm) | ⚪ Planned |
| **147** | **Data Mixing**<br>_domain proportions, quality weighting, data mixing experiments, optimal mixing._ | [📖 Read Online](https://mbrenndoerfer.com/writing/data-mixing-domain-proportions-quality-weighting-optimal) | ⚪ Planned |
| **148** | **Synthetic Data**<br>_synthetic data generation, quality verification, synthetic data diversity, distillation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/synthetic-data-generation-quality-diversity-distillation-llm) | ⚪ Planned |
| **155** | **Causal Language Modeling**<br>_CLM objective formulation, autoregressive factorization, CLM loss computation, CLM for generation, CLM training data, CLM scaling properties._ | [📖 Read Online](https://mbrenndoerfer.com/writing/causal-language-modeling-foundation-generative-ai) | ⚪ Planned |
| **156** | **Masked Language Modeling**<br>_MLM objective formulation, masking strategies (15% rule), [MASK] token usage, MLM for understanding, MLM training dynamics._ | [📖 Read Online](https://mbrenndoerfer.com/writing/masked-language-modeling-bidirectional-understanding-bert) | ⚪ Planned |
| **157** | **Whole Word Masking**<br>_subword masking problems, whole word masking procedure, WWM implementation, WWM vs random masking, WWM for different tokenizers._ | [📖 Read Online](https://mbrenndoerfer.com/writing/whole-word-masking-bert-pretraining) | ⚪ Planned |
| **158** | **Span Corruption**<br>_span selection strategies, span length distribution, sentinel tokens, T5-style corruption, span corruption benefits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/span-corruption-t5-pretraining-objective) | ⚪ Planned |
| **159** | **Prefix Language Modeling**<br>_prefix LM formulation, prefix LM attention pattern, prefix LM for generation, prefix LM training, UniLM-style objectives._ | [📖 Read Online](https://mbrenndoerfer.com/writing/prefix-language-modeling-bidirectional-causal-generation) | ⚪ Planned |
| **160** | **Replaced Token Detection**<br>_generator-discriminator setup, replaced vs original detection, RTD efficiency advantages, ELECTRA training procedure, RTD vs MLM comparison._ | [📖 Read Online](https://mbrenndoerfer.com/writing/replaced-token-detection-electra-pretraining) | ⚪ Planned |
| **161** | **Denoising Objectives**<br>_token deletion, token shuffling, sentence permutation, document rotation, BART-style denoising, combining denoising tasks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/denoising-objectives-bart-corruption-strategies) | ⚪ Planned |
| **162** | **Power Laws in Deep Learning**<br>_power law definition, log-log linear relationships, power law fitting, power law universality, power law intuition._ | [📖 Read Online](https://mbrenndoerfer.com/writing/power-laws-deep-learning-neural-network-scaling) | ⚪ Planned |
| **163** | **Kaplan Scaling Laws**<br>_loss vs parameters, loss vs data, loss vs compute, Kaplan optimal allocation, Kaplan predictions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/kaplan-scaling-laws-language-model-performance) | ⚪ Planned |
| **164** | **Chinchilla Scaling Laws**<br>_Chinchilla experiments, revised scaling coefficients, optimal tokens per parameter, Chinchilla vs Kaplan, Chinchilla implications._ | [📖 Read Online](https://mbrenndoerfer.com/writing/chinchilla-scaling-laws-compute-optimal-llm-training) | ⚪ Planned |
| **165** | **Compute-Optimal Training**<br>_compute budget allocation, tokens vs parameters ratio, training efficiency, compute-optimal recipes, practical guidelines._ | [📖 Read Online](https://mbrenndoerfer.com/writing/compute-optimal-training-chinchilla-scaling-llm) | ⚪ Planned |
| **166** | **Data-Constrained Scaling**<br>_data repetition effects, optimal repetition strategies, data augmentation scaling, synthetic data scaling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/data-constrained-scaling-llm-training-data-limits) | ⚪ Planned |
| **167** | **Inference Scaling**<br>_training vs inference compute, inference-optimal models, over-training for efficiency, deployment cost modeling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/inference-scaling-llm-deployment-optimization) | ⚪ Planned |
| **168** | **Predicting Model Performance**<br>_loss extrapolation, capability prediction, scaling law uncertainty, prediction reliability, practical forecasting._ | [📖 Read Online](https://mbrenndoerfer.com/writing/predicting-model-performance-scaling-laws) | ⚪ Planned |

</details>

<details id="volume-8-encoder-multilingual-and-translation-models-2-parts-14-chapters">
<summary><b>📖 Volume 8 Encoder, Multilingual, and Translation Models 2 parts · 14 chapters (14 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **169** | **BERT Architecture**<br>_BERT model sizes, BERT layer configuration, BERT embedding layers, BERT attention patterns, BERT output representations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bert-architecture-model-structure-components) | ⚪ Planned |
| **170** | **BERT Pre-training**<br>_pre-training data preparation, MLM implementation, NSP task design, pre-training hyperparameters, pre-training duration._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bert-pretraining-mlm-nsp-training-guide) | ⚪ Planned |
| **171** | **BERT Fine-tuning**<br>_classification fine-tuning, sequence labeling fine-tuning, question answering fine-tuning, fine-tuning hyperparameters, catastrophic forgetting._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bert-finetuning-classification-ner-qa) | ⚪ Planned |
| **172** | **BERT Representations**<br>_[CLS] token usage, layer selection strategies, pooling strategies, BERT as feature extractor, frozen vs fine-tuned representations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bert-representations-extracting-contextual-embeddings) | ⚪ Planned |
| **173** | **RoBERTa**<br>_dynamic masking, NSP removal, larger batches, more data, RoBERTa training recipe, RoBERTa vs BERT performance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/roberta-robustly-optimized-bert-pretraining) | ⚪ Planned |
| **174** | **ALBERT**<br>_factorized embeddings, cross-layer parameter sharing, sentence order prediction, ALBERT efficiency, ALBERT performance trade-offs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/albert-parameter-efficient-bert-factorized-embeddings) | ⚪ Planned |
| **175** | **ELECTRA**<br>_generator training, discriminator training, RTD objective, ELECTRA sample efficiency, ELECTRA scaling, ELECTRA fine-tuning._ | [📖 Read Online](https://mbrenndoerfer.com/writing/electra-efficient-pretraining-replaced-token-detection) | ⚪ Planned |
| **176** | **DeBERTa**<br>_disentangled attention formulation, enhanced mask decoder, DeBERTa position encoding, DeBERTa improvements, DeBERTa-v3 advances._ | [📖 Read Online](https://mbrenndoerfer.com/writing/deberta-disentangled-attention-enhanced-mask-decoder) | ⚪ Planned |
| **177** | **T5 Architecture**<br>_T5 encoder-decoder design, T5 attention patterns, T5 model sizes, T5 relative positions, T5 implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/t5-architecture-text-to-text-transformer) | ⚪ Planned |
| **178** | **T5 Pre-training**<br>_span corruption procedure, sentinel tokens, corruption rate, T5 pre-training data, T5 training scale._ | [📖 Read Online](https://mbrenndoerfer.com/writing/t5-pretraining-span-corruption-denoising-objectives) | ⚪ Planned |
| **179** | **T5 Task Formatting**<br>_task prefixes, classification as generation, NER as generation, QA as generation, task formatting examples._ | [📖 Read Online](https://mbrenndoerfer.com/writing/t5-task-formatting-text-to-text-nlp) | ⚪ Planned |
| **180** | **BART Architecture**<br>_BART encoder-decoder, BART attention configuration, BART vs T5 comparison, BART model sizes._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bart-architecture-encoder-decoder-transformers) | ⚪ Planned |
| **181** | **BART Pre-training**<br>_token masking, token deletion, text infilling, sentence permutation, document rotation, objective combinations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bart-pretraining-denoising-text-infilling-strategies) | ⚪ Planned |
| **182** | **mT5**<br>_mT5 training data, language sampling, cross-lingual transfer, mT5 vs T5 performance, multilingual tokenization._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mt5-multilingual-t5-cross-lingual-transfer) | ⚪ Planned |

</details>

<details id="volume-9-decoder-language-models-and-capabilities-3-parts-23-chapters">
<summary><b>📖 Volume 9 Decoder Language Models and Capabilities 3 parts · 23 chapters (23 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **197** | **GPT-1**<br>_GPT-1 architecture, GPT-1 pre-training, GPT-1 fine-tuning approach, GPT-1 transfer learning, GPT-1 historical significance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gpt-1-generative-pretraining-language-understanding) | ⚪ Planned |
| **198** | **GPT-2**<br>_GPT-2 model sizes, GPT-2 architectural changes, zero-shot task performance, GPT-2 training data (WebText), GPT-2 generation quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gpt-2-scaling-language-models-zero-shot-learning) | ⚪ Planned |
| **199** | **GPT-3**<br>_GPT-3 scale (175B), few-shot prompting discovery, in-context learning analysis, GPT-3 capabilities, GPT-3 limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gpt-3-scale-few-shot-in-context-learning) | ⚪ Planned |
| **200** | **In-Context Learning**<br>_ICL phenomenon, ICL vs fine-tuning, example selection strategies, ICL scaling behavior, ICL theoretical understanding._ | [📖 Read Online](https://mbrenndoerfer.com/writing/in-context-learning-llm-examples) | ⚪ Planned |
| **201** | **Autoregressive Generation**<br>_generation procedure, KV caching for efficiency, generation stopping criteria, generation speed optimization, generation code implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/autoregressive-generation-gpt-text-generation) | ⚪ Planned |
| **202** | **Decoding Temperature**<br>_temperature scaling, temperature effects on distribution, temperature selection guidelines, temperature vs quality trade-off._ | [📖 Read Online](https://mbrenndoerfer.com/writing/decoding-temperature-language-model-generation) | ⚪ Planned |
| **203** | **Top-k Sampling**<br>_top-k truncation, k selection strategies, top-k limitations, top-k implementation, combining with temperature._ | [📖 Read Online](https://mbrenndoerfer.com/writing/top-k-sampling-language-model-text-generation) | ⚪ Planned |
| **204** | **Nucleus Sampling**<br>_top-p formulation, cumulative probability threshold, nucleus sampling benefits, p selection guidelines, nucleus vs top-k._ | [📖 Read Online](https://mbrenndoerfer.com/writing/nucleus-sampling-top-p-text-generation) | ⚪ Planned |
| **205** | **Repetition Penalties**<br>_repetition in generation, repetition penalty formulation, frequency penalty, presence penalty, n-gram blocking._ | [📖 Read Online](https://mbrenndoerfer.com/writing/repetition-penalties-language-model-generation) | ⚪ Planned |
| **206** | **Constrained Decoding**<br>_grammar-guided generation, JSON schema constraints, regex constraints, constrained beam search, constrained sampling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/constrained-decoding-structured-llm-output) | ⚪ Planned |
| **207** | **LLaMA Architecture**<br>_LLaMA design philosophy, LLaMA architectural choices, LLaMA training data, LLaMA efficiency, LLaMA significance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/llama-architecture-design-training-efficiency) | ⚪ Planned |
| **208** | **LLaMA Components**<br>_pre-norm with RMSNorm, SwiGLU FFN, RoPE implementation, component interactions, implementation details._ | [📖 Read Online](https://mbrenndoerfer.com/writing/llama-components-rmsnorm-swiglu-rope) | ⚪ Planned |
| **209** | **Grouped Query Attention**<br>_GQA motivation, GQA formulation, KV head grouping, GQA memory savings, GQA vs MHA performance, GQA implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/grouped-query-attention-gqa-efficient-llm-inference) | ⚪ Planned |
| **210** | **Multi-Query Attention**<br>_MQA extreme sharing, MQA memory benefits, MQA quality trade-offs, MQA for inference, MQA vs GQA._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multi-query-attention-memory-efficient-inference) | ⚪ Planned |
| **211** | **Mistral Architecture**<br>_Mistral design choices, sliding window attention, Mistral efficiency, Mistral performance, Mistral vs LLaMA._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mistral-architecture-sliding-window-attention) | ⚪ Planned |
| **212** | **Qwen Architecture**<br>_Qwen architectural choices, Qwen training approach, Qwen multilingual capabilities, Qwen variants._ | [📖 Read Online](https://mbrenndoerfer.com/writing/qwen-architecture-multilingual-llm) | ⚪ Planned |
| **213** | **Phi Models**<br>_Phi design philosophy, textbook-quality data, Phi training approach, Phi efficiency, small model capabilities._ | [📖 Read Online](https://mbrenndoerfer.com/writing/phi-models-textbook-quality-data) | ⚪ Planned |
| **214** | **Emergence in Neural Networks**<br>_emergence definition, phase transitions, emergence examples, emergence mechanisms, emergence debate._ | [📖 Read Online](https://mbrenndoerfer.com/writing/emergence-neural-networks-phase-transitions-scaling) | ⚪ Planned |
| **215** | **In-Context Learning Emergence**<br>_ICL emergence curves, ICL vs fine-tuning scaling, ICL mechanism hypotheses, ICL as meta-learning._ | [📖 Read Online](https://mbrenndoerfer.com/writing/in-context-learning-emergence-scale-mechanisms) | ⚪ Planned |
| **216** | **Chain-of-Thought Emergence**<br>_CoT emergence observations, CoT elicitation, CoT scaling behavior, CoT mechanism theories._ | [📖 Read Online](https://mbrenndoerfer.com/writing/chain-of-thought-emergence-how-llms-learn-to-reason) | ⚪ Planned |
| **217** | **Emergence vs Metrics**<br>_discontinuous metrics, accuracy threshold effects, smooth underlying capabilities, re-examining emergence claims._ | [📖 Read Online](https://mbrenndoerfer.com/writing/llm-emergence-metrics-measurement-artifacts) | ⚪ Planned |
| **218** | **Inverse Scaling**<br>_inverse scaling phenomena, distractor tasks, sycophancy scaling, inverse scaling prize findings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/inverse-scaling-larger-language-models-perform-worse) | ⚪ Planned |
| **219** | **Grokking**<br>_grokking phenomenon, grokking in arithmetic, grokking mechanism theories, grokking phase transitions, practical implications._ | [📖 Read Online](https://mbrenndoerfer.com/writing/grokking-neural-network-generalization-training) | ⚪ Planned |

</details>

<details id="volume-10-large-scale-training-and-sparse-models-3-parts-29-chapters">
<summary><b>📖 Volume 10 Large-Scale Training and Sparse Models 3 parts · 29 chapters (29 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **220** | **GPU Architecture**<br>_GPU memory hierarchy, CUDA cores, tensor cores, GPU specifications._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gpu-architecture-memory-hierarchy-cuda-tensor-cores) | ⚪ Planned |
| **221** | **Memory Management**<br>_memory breakdown (activations, parameters, gradients, optimizer states), memory estimation, OOM debugging._ | [📖 Read Online](https://mbrenndoerfer.com/writing/memory-management-activations-gradients-optimizer-states-oom) | ⚪ Planned |
| **222** | **Data Parallelism**<br>_DDP algorithm, gradient synchronization, all-reduce operations, DDP scaling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/data-parallelism-ddp-gradient-synchronization-all-reduce) | ⚪ Planned |
| **223** | **Tensor Parallelism**<br>_column parallelism, row parallelism, communication patterns, Megatron-style parallelism._ | [📖 Read Online](https://mbrenndoerfer.com/writing/tensor-parallelism-column-row-megatron-communication-patterns) | ⚪ Planned |
| **224** | **Pipeline Parallelism**<br>_pipeline stages, micro-batching, pipeline bubbles, pipeline schedules (GPipe, 1F1B)._ | [📖 Read Online](https://mbrenndoerfer.com/writing/pipeline-parallelism-stages-micro-batching-gpipe-1f1b) | ⚪ Planned |
| **225** | **ZeRO Optimization**<br>_ZeRO stage 1 (optimizer state partitioning), ZeRO stage 2 (gradient partitioning), ZeRO stage 3 (parameter partitioning), ZeRO memory savings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/zero-optimization-stages-optimizer-gradient-parameter-partitioning) | ⚪ Planned |
| **226** | **FSDP**<br>_FSDP concepts, FSDP vs ZeRO, FSDP sharding strategies, FSDP usage._ | [📖 Read Online](https://mbrenndoerfer.com/writing/fsdp-fully-sharded-data-parallel-sharding-strategies-zero) | ⚪ Planned |
| **227** | **Activation Checkpointing**<br>_checkpointing concept, checkpoint selection, checkpointing overhead, selective checkpointing._ | [📖 Read Online](https://mbrenndoerfer.com/writing/activation-checkpointing-gradient-memory-selective-recomputation) | ⚪ Planned |
| **228** | **Mixed Precision Training**<br>_floating point formats, loss scaling, BF16 advantages, mixed precision implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mixed-precision-training-fp16-bf16-loss-scaling) | ⚪ Planned |
| **229** | **Communication Optimization**<br>_gradient compression, communication overlap, topology-aware communication, NCCL optimization._ | [📖 Read Online](https://mbrenndoerfer.com/writing/communication-optimization-gradient-compression-nccl-overlap) | ⚪ Planned |
| **230** | **Checkpointing and Recovery**<br>_checkpoint contents, checkpoint frequency, async checkpointing, fault recovery._ | [📖 Read Online](https://mbrenndoerfer.com/writing/checkpointing-recovery-async-fault-tolerance-training) | ⚪ Planned |
| **231** | **Learning Rate Warmup**<br>_warmup motivation, linear warmup, warmup duration, warmup for large batches._ | [📖 Read Online](https://mbrenndoerfer.com/writing/learning-rate-warmup-linear-duration-large-batch-training) | ⚪ Planned |
| **232** | **Learning Rate Decay**<br>_step decay, exponential decay, inverse square root decay, decay scheduling._ | [📖 Read Online](https://mbrenndoerfer.com/writing/learning-rate-decay-step-exponential-inverse-sqrt-scheduling) | ⚪ Planned |
| **233** | **Cosine Learning Rate Schedule**<br>_cosine decay formula, cosine with restarts, cosine schedule parameters, cosine vs linear._ | [📖 Read Online](https://mbrenndoerfer.com/writing/cosine-learning-rate-schedule-decay-restarts-warmup) | ⚪ Planned |
| **234** | **Large Batch Training**<br>_batch size effects, learning rate scaling, batch size limits, LAMB optimizer._ | [📖 Read Online](https://mbrenndoerfer.com/writing/large-batch-training-learning-rate-scaling-lamb-optimizer) | ⚪ Planned |
| **235** | **Weight Decay**<br>_weight decay formula, decoupled weight decay, weight decay selection, weight decay interaction with Adam._ | [📖 Read Online](https://mbrenndoerfer.com/writing/weight-decay-decoupled-adamw-regularization-l2) | ⚪ Planned |
| **236** | **Gradient Accumulation**<br>_accumulation procedure, accumulation steps, accumulation for memory, accumulation correctness._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gradient-accumulation-memory-effective-batch-size-training) | ⚪ Planned |
| **237** | **Training Stability**<br>_loss spikes, gradient norm monitoring, stability techniques, training stability debugging._ | [📖 Read Online](https://mbrenndoerfer.com/writing/training-stability-loss-spikes-gradient-norm-debugging) | ⚪ Planned |
| **238** | **Hyperparameter Selection**<br>_hyperparameter search, hyperparameter transfer, critical vs robust hyperparameters, default recipes._ | [📖 Read Online](https://mbrenndoerfer.com/writing/hyperparameter-selection-search-transfer-recipes-llm-training) | ⚪ Planned |
| **239** | **Sparse Models**<br>_dense vs sparse trade-offs, conditional computation motivation, sparse model efficiency, sparse model challenges._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sparse-models-conditional-computation-efficiency) | ⚪ Planned |
| **240** | **Expert Networks**<br>_expert architecture, expert as FFN, expert capacity, expert count selection, expert placement in transformer._ | [📖 Read Online](https://mbrenndoerfer.com/writing/expert-networks-moe-architecture-ffn-implementation) | ⚪ Planned |
| **241** | **Gating Networks**<br>_router architecture, routing score computation, router training, router learned behavior._ | [📖 Read Online](https://mbrenndoerfer.com/writing/moe-gating-networks-router-architecture-design) | ⚪ Planned |
| **242** | **Top-K Routing**<br>_top-1 routing, top-2 routing, k selection trade-offs, routing implementation, combining expert outputs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/top-k-routing-mixture-of-experts-expert-selection) | ⚪ Planned |
| **243** | **Load Balancing**<br>_expert utilization imbalance, collapse failure mode, load metrics, balanced routing importance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/moe-load-balancing-expert-collapse-token-distribution) | ⚪ Planned |
| **244** | **Auxiliary Balancing Loss**<br>_load balancing loss formulation, loss coefficient tuning, balancing vs task loss, auxiliary loss implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/auxiliary-balancing-loss-mixture-of-experts-moe) | ⚪ Planned |
| **245** | **Router Z-Loss**<br>_router instability, z-loss formulation, z-loss benefits, z-loss coefficient, combined auxiliary losses._ | [📖 Read Online](https://mbrenndoerfer.com/writing/router-z-loss-moe-training-stability) | ⚪ Planned |
| **246** | **Expert Parallelism**<br>_expert placement strategies, all-to-all communication, communication overhead, expert parallelism implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/expert-parallelism-distributed-moe-training) | ⚪ Planned |
| **247** | **Switch Transformer**<br>_Switch Transformer design, top-1 routing choice, capacity factor, Switch scaling results._ | [📖 Read Online](https://mbrenndoerfer.com/writing/switch-transformer-top-1-routing-trillion-parameter-scaling) | ⚪ Planned |
| **248** | **Mixtral**<br>_Mixtral architecture, Mixtral expert design, Mixtral performance, Mixtral efficiency, Mixtral vs dense models._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mixtral-8x7b-sparse-mixture-of-experts-architecture) | ⚪ Planned |

</details>

<details id="volume-11-fine-tuning-and-efficient-adaptation-3-parts-23-chapters">
<summary><b>📖 Volume 11 Fine-tuning and Efficient Adaptation 3 parts · 23 chapters (23 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **249** | **Transfer Learning**<br>_transfer learning paradigm, pre-training/fine-tuning split, what transfers, transfer learning efficiency._ | [📖 Read Online](https://mbrenndoerfer.com/writing/transfer-learning-nlp-pre-training-fine-tuning) | ⚪ Planned |
| **250** | **Full Fine-tuning**<br>_full fine-tuning procedure, fine-tuning hyperparameters, learning rate selection, batch size effects._ | [📖 Read Online](https://mbrenndoerfer.com/writing/full-fine-tuning-hyperparameters-learning-rate-schedules) | ⚪ Planned |
| **251** | **Catastrophic Forgetting**<br>_forgetting phenomenon, forgetting measurement, forgetting mitigation, pre-trained capability preservation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/catastrophic-forgetting-fine-tuning-mitigation) | ⚪ Planned |
| **252** | **Fine-tuning Learning Rates**<br>_discriminative fine-tuning, layer-wise learning rates, warmup for fine-tuning, learning rate decay._ | [📖 Read Online](https://mbrenndoerfer.com/writing/fine-tuning-learning-rates-llrd-warmup-decay-transformers) | ⚪ Planned |
| **253** | **Fine-tuning Data Efficiency**<br>_few-shot fine-tuning, data augmentation, sample efficiency patterns, small data strategies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/fine-tuning-data-efficiency-few-shot-learning-augmentation) | ⚪ Planned |
| **254** | **PEFT Motivation**<br>_parameter storage costs, multi-task deployment, PEFT efficiency, PEFT quality trade-offs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/peft-motivation-parameter-efficient-fine-tuning-llms) | ⚪ Planned |
| **255** | **LoRA Concept**<br>_weight update decomposition, low-rank assumption, LoRA efficiency gains, LoRA flexibility._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lora-concept-low-rank-adaptation-efficient-llm-fine-tuning) | ⚪ Planned |
| **256** | **LoRA Mathematics**<br>_LoRA formulation W + BA, rank selection, initialization scheme, LoRA gradient computation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lora-mathematics-low-rank-adaptation-formulas) | ⚪ Planned |
| **257** | **LoRA Implementation**<br>_LoRA module design, merging weights, LoRA training loop, LoRA in PyTorch, HuggingFace PEFT usage._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lora-implementation-pytorch-peft-guide) | ⚪ Planned |
| **258** | **LoRA Hyperparameters**<br>_rank selection guidelines, alpha/rank ratio, which layers to adapt, LoRA dropout._ | [📖 Read Online](https://mbrenndoerfer.com/writing/lora-hyperparameters-rank-alpha-target-modules) | ⚪ Planned |
| **259** | **QLoRA**<br>_4-bit quantization for base model, NF4 data type, double quantization, QLoRA memory savings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/qlora-quantized-lora-memory-efficient-fine-tuning) | ⚪ Planned |
| **260** | **AdaLoRA**<br>_importance-based pruning, SVD-based adaptation, dynamic rank, AdaLoRA training procedure._ | [📖 Read Online](https://mbrenndoerfer.com/writing/adalora-adaptive-rank-allocation-fine-tuning) | ⚪ Planned |
| **261** | **IA3**<br>_IA3 formulation, learned rescaling vectors, IA3 parameter efficiency, IA3 vs LoRA._ | [📖 Read Online](https://mbrenndoerfer.com/writing/ia3-parameter-efficient-fine-tuning-activation-rescaling) | ⚪ Planned |
| **262** | **Prefix Tuning**<br>_prefix tuning formulation, prefix length selection, prefix tuning for generation, prefix vs LoRA._ | [📖 Read Online](https://mbrenndoerfer.com/writing/prefix-tuning-virtual-tokens-efficient-fine-tuning) | ⚪ Planned |
| **263** | **Prompt Tuning**<br>_prompt tuning formulation, prompt initialization, prompt tuning scaling, prompt length effects._ | [📖 Read Online](https://mbrenndoerfer.com/writing/prompt-tuning-parameter-efficient-soft-prompts-llm) | ⚪ Planned |
| **264** | **Adapter Layers**<br>_adapter architecture, adapter placement, adapter dimensionality, adapter fusion._ | [📖 Read Online](https://mbrenndoerfer.com/writing/adapter-layers-bottleneck-modules-transformer-fine-tuning) | ⚪ Planned |
| **265** | **PEFT Comparison**<br>_performance comparison, parameter efficiency comparison, task suitability, practical recommendations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/peft-comparison-lora-qlora-adapters-selection-guide) | ⚪ Planned |
| **266** | **Instruction Following**<br>_instruction tuning motivation, instruction format design, instruction diversity, instruction quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/instruction-following-llm-tuning-fundamentals) | ⚪ Planned |
| **267** | **Instruction Data Creation**<br>_human annotation, template-based generation, seed task expansion, quality filtering._ | [📖 Read Online](https://mbrenndoerfer.com/writing/instruction-data-creation-building-training-datasets) | ⚪ Planned |
| **268** | **Self-Instruct**<br>_self-instruct procedure, instruction generation, response generation, filtering strategies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/self-instruct-bootstrap-instruction-tuning-datasets) | ⚪ Planned |
| **269** | **Instruction Format**<br>_prompt templates, system messages, multi-turn format, chat templates, role definitions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/instruction-format-chat-templates-role-definitions-llm) | ⚪ Planned |
| **270** | **Instruction Tuning Training**<br>_instruction tuning data mixing, training hyperparameters, loss masking, multi-task learning._ | [📖 Read Online](https://mbrenndoerfer.com/writing/instruction-tuning-training-data-mixing-loss-masking) | ⚪ Planned |
| **271** | **Instruction Following Evaluation**<br>_instruction following benchmarks, human evaluation, automatic evaluation, instruction difficulty._ | [📖 Read Online](https://mbrenndoerfer.com/writing/instruction-following-evaluation-benchmarks-llm-judge) | ⚪ Planned |

</details>

<details id="volume-12-alignment-preferences-and-oversight-1-part-16-chapters">
<summary><b>📖 Volume 12 Alignment, Preferences, and Oversight 1 part · 16 chapters (16 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **272** | **Alignment Problem**<br>_alignment definition, helpfulness vs harmlessness, alignment challenges, alignment approaches overview._ | [📖 Read Online](https://mbrenndoerfer.com/writing/alignment-problem-hhh-framework-language-models) | ⚪ Planned |
| **273** | **Human Preference Data**<br>_preference collection UI, comparison design, annotator guidelines, preference data quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/human-preference-data-collection-rlhf-alignment) | ⚪ Planned |
| **274** | **Bradley-Terry Model**<br>_pairwise comparison model, preference probability, Bradley-Terry likelihood, preference strength._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bradley-terry-model-pairwise-preferences-rankings) | ⚪ Planned |
| **275** | **Reward Modeling**<br>_reward model architecture, preference loss function, reward model training, reward model evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reward-modeling-rlhf-architecture-training) | ⚪ Planned |
| **276** | **Reward Hacking**<br>_reward hacking examples, distribution shift, over-optimization, reward hacking mitigation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reward-hacking-rlhf-optimization-language-models) | ⚪ Planned |
| **277** | **Policy Gradient Methods**<br>_policy definition, REINFORCE algorithm, policy gradient derivation, variance reduction._ | [📖 Read Online](https://mbrenndoerfer.com/writing/policy-gradient-methods-reinforce-algorithm) | ⚪ Planned |
| **278** | **PPO Algorithm**<br>_clipped objective, PPO derivation, trust region intuition, PPO implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/ppo-algorithm-proximal-policy-optimization-reinforcement-learning) | ⚪ Planned |
| **279** | **PPO for Language Models**<br>_LLM as policy, action space (tokens), reward assignment, KL penalty importance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/ppo-for-language-models-rlhf-policy-optimization) | ⚪ Planned |
| **280** | **RLHF Pipeline**<br>_SFT stage, reward model training, PPO fine-tuning, RLHF hyperparameters, RLHF debugging._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rlhf-pipeline-sft-reward-model-ppo-training) | ⚪ Planned |
| **281** | **KL Divergence Penalty**<br>_KL penalty motivation, KL coefficient selection, adaptive KL, KL effects on training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/kl-divergence-penalty-rlhf-training) | ⚪ Planned |
| **282** | **DPO Concept**<br>_DPO motivation, removing reward model, DPO intuition, DPO benefits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/dpo-direct-preference-optimization-concept-llm-alignment) | ⚪ Planned |
| **283** | **DPO Derivation**<br>_DPO from RLHF objective, optimal policy derivation, DPO loss function, DPO as classification._ | [📖 Read Online](https://mbrenndoerfer.com/writing/dpo-derivation-rlhf-optimal-policy-reward-reparameterization) | ⚪ Planned |
| **284** | **DPO Implementation**<br>_DPO data format, DPO loss computation, DPO training procedure, DPO hyperparameters._ | [📖 Read Online](https://mbrenndoerfer.com/writing/dpo-implementation-pytorch-preference-optimization-training) | ⚪ Planned |
| **285** | **DPO Variants**<br>_IPO formulation, KTO for unpaired feedback, ORPO, cDPO, comparing alignment methods._ | [📖 Read Online](https://mbrenndoerfer.com/writing/dpo-variants-ipo-kto-orpo-cdpo-llm-alignment) | ⚪ Planned |
| **286** | **RLAIF**<br>_AI as annotator, constitutional AI principles, AI preference generation, RLAIF scalability._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rlaif-constitutional-ai-scalable-alignment) | ⚪ Planned |
| **287** | **Iterative Alignment**<br>_iterative DPO, online preference learning, self-improvement loops, alignment stability._ | [📖 Read Online](https://mbrenndoerfer.com/writing/iterative-alignment-online-dpo-self-improvement) | ⚪ Planned |

</details>

<details id="volume-13-reasoning-and-verifiable-learning-1-part-7-chapters">
<summary><b>📖 Volume 13 Reasoning and Verifiable Learning 1 part · 7 chapters (7 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **293** | **Reasoning Foundations**<br>_reasoning types, reasoning in LLMs, reasoning failure modes, reasoning evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reasoning-foundations-types-llm-failure-modes-evaluation) | ⚪ Planned |
| **294** | **Chain-of-Thought**<br>_CoT prompting, zero-shot CoT, CoT fine-tuning, CoT limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/chain-of-thought-prompting-zero-shot-fine-tuning-limitations) | ⚪ Planned |
| **295** | **Reasoning Strategies**<br>_self-consistency, tree of thought, least-to-most prompting, decomposition strategies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reasoning-strategies-self-consistency-tree-of-thought-decomposition) | ⚪ Planned |
| **296** | **Reasoning Verification**<br>_step verification, process reward models, verification-guided search, self-correction._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reasoning-verification-process-reward-models-guided-search) | ⚪ Planned |
| **297** | **Mathematical Reasoning**<br>_math problem solving, symbolic integration, math benchmarks, math reasoning training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mathematical-reasoning-llm-benchmarks-training-gsm8k-math) | ⚪ Planned |
| **298** | **Reasoning Limitations**<br>_systematic failures, spurious correlations, reasoning shortcuts, robustness challenges._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reasoning-limitations-systematic-failures-shortcuts-robustness) | ⚪ Planned |
| **299** | **Reasoning Frontiers**<br>_o1-style reasoning, test-time compute scaling, reasoning-capable models, open research questions._ | [📖 Read Online](https://mbrenndoerfer.com/writing/reasoning-frontiers-o1-test-time-compute-scaling-research) | ⚪ Planned |

</details>

<details id="volume-14-efficient-inference-and-on-device-models-2-parts-20-chapters">
<summary><b>📖 Volume 14 Efficient Inference and On-Device Models 2 parts · 20 chapters (20 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **307** | **Knowledge Distillation**<br>_distillation objective, temperature in distillation, teacher selection, distillation for LLMs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/knowledge-distillation-temperature-teacher-student-llm) | ⚪ Planned |
| **308** | **Distillation Variants**<br>_feature distillation, attention transfer, progressive distillation, on-policy distillation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/distillation-variants-feature-attention-transfer-progressive) | ⚪ Planned |
| **309** | **Pruning Basics**<br>_weight pruning, structured vs unstructured, pruning criteria, pruning schedule._ | [📖 Read Online](https://mbrenndoerfer.com/writing/pruning-basics-weight-structured-unstructured-criteria-schedule) | ⚪ Planned |
| **310** | **Structured Pruning**<br>_head pruning, layer pruning, width pruning, structured pruning implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/structured-pruning-head-layer-width-implementation) | ⚪ Planned |
| **311** | **Model Merging**<br>_weight averaging, task arithmetic, TIES merging, DARE merging._ | [📖 Read Online](https://mbrenndoerfer.com/writing/model-merging-weight-averaging-task-arithmetic-ties-dare) | ⚪ Planned |
| **312** | **Model Merging Applications**<br>_multi-task merging, style merging, capability composition, merging evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/model-merging-applications-multi-task-style-capability-composition) | ⚪ Planned |
| **313** | **KV Cache**<br>_KV cache motivation, cache structure, cache memory requirements, cache management._ | [📖 Read Online](https://mbrenndoerfer.com/writing/kv-cache-transformer-attention-optimization) | ⚪ Planned |
| **314** | **KV Cache Memory**<br>_cache size calculation, batch size effects, sequence length effects, memory bottleneck._ | [📖 Read Online](https://mbrenndoerfer.com/writing/kv-cache-memory-calculation-llm-inference-gpu) | ⚪ Planned |
| **315** | **Paged Attention**<br>_memory fragmentation problem, page-based allocation, vLLM approach, paged attention benefits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/paged-attention-vllm-kv-cache-memory-management) | ⚪ Planned |
| **316** | **KV Cache Compression**<br>_cache eviction strategies, attention sink preservation, H2O algorithm, cache quantization._ | [📖 Read Online](https://mbrenndoerfer.com/writing/kv-cache-compression-eviction-quantization-h2o-algorithm) | ⚪ Planned |
| **317** | **Weight Quantization Basics**<br>_quantization fundamentals, per-tensor vs per-channel, symmetric vs asymmetric, calibration._ | [📖 Read Online](https://mbrenndoerfer.com/writing/weight-quantization-basics-scale-zero-point-calibration) | ⚪ Planned |
| **318** | **INT8 Quantization**<br>_INT8 range mapping, absmax quantization, smooth quantization, INT8 accuracy._ | [📖 Read Online](https://mbrenndoerfer.com/writing/int8-quantization-absmax-smooth-quantization-implementation) | ⚪ Planned |
| **319** | **INT4 Quantization**<br>_4-bit challenges, group-wise quantization, 4-bit accuracy trade-offs, 4-bit formats._ | [📖 Read Online](https://mbrenndoerfer.com/writing/int4-quantization-group-wise-nf4-format-llms) | ⚪ Planned |
| **320** | **GPTQ**<br>_GPTQ algorithm, layer-wise quantization, Hessian approximation, GPTQ implementation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gptq-4bit-weight-quantization-llm-guide) | ⚪ Planned |
| **321** | **AWQ**<br>_salient weight preservation, AWQ algorithm, AWQ vs GPTQ, AWQ benefits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/awq-activation-aware-weight-quantization-llm) | ⚪ Planned |
| **322** | **GGUF Format**<br>_GGML/GGUF history, quantization types, GGUF file format, llama.cpp integration._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gguf-format-quantized-llm-storage-inference) | ⚪ Planned |
| **323** | **Speculative Decoding: Fast LLM Inference Without Quality Loss**<br>_speculative decoding concept, draft model selection, verification procedure, acceptance rate._ | [📖 Read Online](https://mbrenndoerfer.com/writing/speculative-decoding-accelerating-llm-inference) | ⚪ Planned |
| **324** | **Speculative Decoding Math: Algorithms & Speedup Limits**<br>_acceptance criterion, expected speedup, draft quality effects, optimal draft length._ | [📖 Read Online](https://mbrenndoerfer.com/writing/speculative-decoding-math-acceptance-criterion) | ⚪ Planned |
| **325** | **Continuous Batching: Optimizing LLM Inference Throughput**<br>_static vs continuous batching, iteration-level scheduling, request completion handling, throughput gains._ | [📖 Read Online](https://mbrenndoerfer.com/writing/continuous-batching) | ⚪ Planned |
| **326** | **LLM Inference Serving: Architecture, Routing & Auto-Scaling Master LLM inference serving architecture, token-aware load balancing, and auto-scaling. Optimize time-to-first-token and throughput for production systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/llm-inference-serving-architecture-scaling-optimization) | ⚪ Planned |

</details>

<details id="volume-15-retrieval-knowledge-and-memory-2-parts-19-chapters">
<summary><b>📖 Volume 15 Retrieval, Knowledge, and Memory 2 parts · 19 chapters (19 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **332** | **RAG Motivation: Solving Hallucinations & Knowledge Gaps Discover why LLMs need Retrieval-Augmented Generation. Learn how RAG bridges knowledge gaps, reduces hallucinations, and enables non-parametric memory.** | [📖 Read Online](https://mbrenndoerfer.com/writing/rag-motivation-llm-knowledge-limitations) | ⚪ Planned |
| **333** | **RAG Architecture: Components, Timing & Design Patterns Master RAG system design by exploring retriever-generator interactions, timing strategies like iterative retrieval, and architectural variations like RETRO.** | [📖 Read Online](https://mbrenndoerfer.com/writing/rag-architecture-retriever-generator-design-patterns) | ⚪ Planned |
| **334** | **Dense Retrieval: Semantic Search & Bi-Encoder Implementation Master dense retrieval for semantic search. Explore bi-encoder architectures, embedding metrics, and contrastive learning to overcome keyword limitations.** | [📖 Read Online](https://mbrenndoerfer.com/writing/dense-retrieval-semantic-search-bi-encoders) | ⚪ Planned |
| **335** | **Contrastive Learning for Retrieval: InfoNCE & DPR Guide Master contrastive learning for dense retrieval. Learn to train models using InfoNCE loss, in-batch negatives, and hard negative mining strategies effectively.** | [📖 Read Online](https://mbrenndoerfer.com/writing/contrastive-learning-retrieval-infonce-dpr) | ⚪ Planned |
| **336** | **Document Chunking: Optimizing RAG Retrieval Pipelines Master document chunking for RAG systems. Explore fixed-size, recursive, and semantic strategies to balance retrieval precision with context window limits.** | [📖 Read Online](https://mbrenndoerfer.com/writing/document-chunking-rag-strategies-retrieval) | ⚪ Planned |
| **337** | **Embedding Models: Architecture, Pooling & Selection Learn how embedding models convert text to vectors for RAG.**<br>_bi-encoder architecture, pooling strategies, dimensionality trade-offs, and model selection._ | [📖 Read Online](https://mbrenndoerfer.com/writing/embedding-models-architecture-pooling-selection) | ⚪ Planned |
| **338** | **Vector Similarity Search: Metrics & Approximate Methods Explore vector similarity search for RAG systems. Compare cosine, dot product, and Euclidean metrics, and implement exact vs. approximate search with FAISS.** | [📖 Read Online](https://mbrenndoerfer.com/writing/vector-similarity-search-metrics-ann-faiss) | ⚪ Planned |
| **339** | **HNSW Index: Architecture for Fast Vector Search Master Hierarchical Navigable Small World (HNSW) graphs for vector search. Learn graph architecture, construction, and tuning for high-speed retrieval.** | [📖 Read Online](https://mbrenndoerfer.com/writing/hnsw-index-vector-search-architecture) | ⚪ Planned |
| **340** | **IVF Index: Clustering-Based Vector Search & Partitioning Master IVF indexes for scalable vector search. Learn clustering-based partitioning, nprobe tuning, and IVF-PQ compression for billion-scale retrieval.** | [📖 Read Online](https://mbrenndoerfer.com/writing/ivf-index-clustering-vector-search-partitioning) | ⚪ Planned |
| **341** | **Product Quantization: Vector Compression for ANN Search Learn how Product Quantization compresses embeddings up to 100x using learned codebooks and asymmetric distance computation for scalable vector search.** | [📖 Read Online](https://mbrenndoerfer.com/writing/product-quantization-vector-compression-ann-search) | ⚪ Planned |
| **342** | **Hybrid Search: BM25 and Dense Retrieval Combined Learn how hybrid search fuses BM25 keyword retrieval with dense vector retrieval using reciprocal rank fusion and weighted score combination to improve recall.** | [📖 Read Online](https://mbrenndoerfer.com/writing/hybrid-search-bm25-dense-retrieval-fusion) | ⚪ Planned |
| **343** | **Reranking: Cross-Encoders for Precise Information Retrieval Learn how reranking with cross-encoders solves bi-encoder limitations. Master two-stage retrieval, training strategies, and latency optimization for production search systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/reranking-cross-encoders-information-retrieval) | ⚪ Planned |
| **344** | **RAG Prompt Engineering: Context Placement & Citation Strategies Master RAG prompt engineering with strategic context placement, citation formats, and truncation strategies to improve LLM accuracy and reduce hallucinations.** | [📖 Read Online](https://mbrenndoerfer.com/writing/rag-prompt-engineering-context-citations) | ⚪ Planned |
| **345** | **RAG Evaluation: Metrics for Retrieval and Generation Quality Master RAG evaluation with metrics for retrieval quality (Precision@K, NDCG, MRR) and generation faithfulness using the RAGAS framework for AI systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/rag-evaluation-metrics-retrieval-generation) | ⚪ Planned |
| **352** | **Continual Learning Problem**<br>_continual learning definition, catastrophic forgetting, continual learning scenarios._ | [📖 Read Online](https://mbrenndoerfer.com/writing/continual-learning-problem-catastrophic-forgetting-scenarios) | ⚪ Planned |
| **353** | **Regularization Methods**<br>_elastic weight consolidation, synaptic intelligence, parameter importance, regularization trade-offs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/regularization-methods-ewc-synaptic-intelligence-continual-learning) | ⚪ Planned |
| **354** | **Replay Methods**<br>_replay buffer design, pseudo-rehearsal, generative replay, replay selection._ | [📖 Read Online](https://mbrenndoerfer.com/writing/replay-methods-buffer-pseudo-rehearsal-generative-continual) | ⚪ Planned |
| **355** | **Architecture Methods**<br>_progressive networks, expert expansion, architecture search, modular approaches._ | [📖 Read Online](https://mbrenndoerfer.com/writing/architecture-methods-progressive-networks-expert-expansion-modular) | ⚪ Planned |
| **356** | **Continual Learning Evaluation**<br>_forward transfer, backward transfer, evaluation protocols, continual benchmarks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/continual-learning-evaluation-forward-backward-transfer-benchmarks) | ⚪ Planned |

</details>

<details id="volume-16-agents-and-ai-coding-systems-2-parts-16-chapters">
<summary><b>📖 Volume 16 Agents and AI Coding Systems 2 parts · 16 chapters (16 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **357** | **Code LLM Training**<br>_code training data, code tokenization, fill-in-the-middle training, code pre-training objectives._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-llm-training-fill-in-middle-tokenization-objectives) | ⚪ Planned |
| **358** | **Code Understanding**<br>_code explanation, bug detection, code review, code search._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-understanding-explanation-bug-detection-review-search) | ⚪ Planned |
| **359** | **Code Completion**<br>_completion context, completion ranking, completion latency, completion UX._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-completion-context-ranking-latency-ux-llm) | ⚪ Planned |
| **360** | **Code Generation**<br>_docstring-to-code, test-to-code, code generation strategies, generation quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-generation-docstring-test-driven-strategies-quality) | ⚪ Planned |
| **361** | **Code Execution**<br>_sandboxed execution, execution feedback, iterative refinement, execution safety._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-execution-sandboxed-feedback-iterative-refinement-safety) | ⚪ Planned |
| **362** | **Code Evaluation**<br>_functional correctness, pass@k metric, code benchmarks, beyond correctness._ | [📖 Read Online](https://mbrenndoerfer.com/writing/code-evaluation-functional-correctness-pass-at-k-benchmarks) | ⚪ Planned |
| **363** | **Tool Use Motivation: Why LLMs Need External Tools for Accuracy Discover why LLMs require external tools to overcome knowledge cutoffs, computational limits, and hallucinations. Learn about tool-augmented AI systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/tool-use-motivation-llm-limitations) | ⚪ Planned |
| **364** | **Function Calling: Structured Tool Use for Large Language Models Learn how function calling enables LLMs to invoke external tools and APIs through structured JSON schemas, bridging natural language and executable code.** | [📖 Read Online](https://mbrenndoerfer.com/writing/function-calling-llm-structured-tools) | ⚪ Planned |
| **365** | **ReAct Pattern: Interleaving Reasoning and Action for LLM Agents Learn how the ReAct pattern enables LLM agents to interleave reasoning with tool execution. Master thought-action-observation loops for autonomous AI systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/react-pattern-llm-reasoning-action-agents) | ⚪ Planned |
| **366** | **Tool Selection for LLM Agents: Routing Strategies and Implementation Master LLM tool selection through embedding-based routing, hybrid strategies, and semantic interfaces. Learn to build scalable multi-tool agent systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/tool-selection-llm-agents-routing-strategies) | ⚪ Planned |
| **367** | **Agent Architectures: Control Loops, State & Planning Master LLM agent architectures including control loops, state management strategies, planning mechanisms, and termination conditions for autonomous AI systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/agent-architectures-loop-state-planning-termination) | ⚪ Planned |
| **368** | **Agent Memory Systems: From Context to Persistent Storage Learn how AI agents manage short-term context and long-term memory. Explore vector databases, retrieval algorithms, and memory hierarchies that enable persistent, learning systems.** | [📖 Read Online](https://mbrenndoerfer.com/writing/agent-memory-systems-architecture) | ⚪ Planned |
| **369** | **Agent Evaluation: Metrics, Benchmarks and Safety Standards Learn to evaluate AI agents with task completion metrics, trajectory analysis, and safety testing.**<br>_WebArena, SWE-bench, GAIA, and OSWorld benchmarks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/agent-evaluation-metrics-benchmarks-safety) | ⚪ Planned |
| **370** | **Planning**<br>_task decomposition, goal-directed planning, plan execution, plan revision and recovery._ | [📖 Read Online](https://mbrenndoerfer.com/writing/planning-task-decomposition-goal-directed-llm-agents) | ⚪ Planned |
| **371** | **Multi-Agent Systems**<br>_agent coordination, communication protocols, role assignment, multi-agent benchmarks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multi-agent-systems-coordination-communication-protocols) | ⚪ Planned |
| **372** | **Agent Safety**<br>_unsafe action prevention, agent alignment, sandboxing, monitoring and intervention._ | [📖 Read Online](https://mbrenndoerfer.com/writing/agent-safety-alignment-sandboxing-monitoring) | ⚪ Planned |

</details>

<details id="volume-17-speech-multimodal-and-embodied-language-2-parts-17-chapters">
<summary><b>📖 Volume 17 Speech, Multimodal, and Embodied Language 2 parts · 17 chapters (17 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **381** | **Vision Transformer**<br>_image patching, patch embeddings, ViT architecture, ViT pre-training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/vision-transformer-vit-architecture-image-patching) | ⚪ Planned |
| **382** | **CLIP**<br>_CLIP architecture, CLIP training objective, CLIP zero-shot classification, CLIP embeddings._ | [📖 Read Online](https://mbrenndoerfer.com/writing/clip-contrastive-learning-zero-shot-vision) | ⚪ Planned |
| **383** | **Vision Encoders for VLMs**<br>_ViT variants for VLMs, SigLIP improvements, image resolution handling, encoder selection._ | [📖 Read Online](https://mbrenndoerfer.com/writing/vision-encoders-vlms-siglip-resolution-architecture) | ⚪ Planned |
| **384** | **Vision-Language Projection**<br>_linear projection, MLP projection, Q-Former approach, projection training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/vision-language-projection-methods-qformer-linear) | ⚪ Planned |
| **385** | **LLaVA Architecture**<br>_LLaVA design, two-stage training, visual conversation, LLaVA variants._ | [📖 Read Online](https://mbrenndoerfer.com/writing/llava-architecture-visual-instruction-tuning) | ⚪ Planned |
| **386** | **Flamingo Architecture**<br>_cross-attention to images, gated cross-attention, few-shot visual learning, Flamingo training._ | [📖 Read Online](https://mbrenndoerfer.com/writing/flamingo-architecture-multimodal-vision-language-model) | ⚪ Planned |
| **387** | **Multimodal Training Data**<br>_image-text pairs, interleaved documents, visual instruction data, data quality._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multimodal-training-data-image-text-curation) | ⚪ Planned |
| **388** | **Multimodal Evaluation**<br>_VQA benchmarks, multimodal understanding benchmarks, multimodal generation evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multimodal-evaluation-vqa-benchmarks-metrics) | ⚪ Planned |
| **389** | **Multimodal Foundations**<br>_multimodal learning principles, cross-modal alignment, joint embedding spaces, multimodal challenges._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multimodal-foundations-cross-modal-alignment-joint-embeddings) | ⚪ Planned |
| **390** | **Image Understanding**<br>_visual question answering, image captioning, visual grounding, scene understanding._ | [📖 Read Online](https://mbrenndoerfer.com/writing/image-understanding-vqa-captioning-visual-grounding) | ⚪ Planned |
| **391** | **Image Generation**<br>_diffusion models, text-to-image generation, image editing, generation evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/image-generation-diffusion-models-text-to-image) | ⚪ Planned |
| **392** | **Multimodal Applications**<br>_document understanding, medical imaging, video understanding, multimodal reasoning tasks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/multimodal-applications-document-medical-video-reasoning) | ⚪ Planned |
| **393** | **Speech Representations**<br>_mel spectrograms, mel filterbanks, feature normalization, audio preprocessing._ | [📖 Read Online](https://mbrenndoerfer.com/writing/speech-representations-mel-spectrograms) | ⚪ Planned |
| **394** | **Whisper Architecture**<br>_Whisper encoder-decoder, multitask training, language tokens, timestamp prediction._ | [📖 Read Online](https://mbrenndoerfer.com/writing/whisper-architecture-encoder-decoder-multilingual-asr) | ⚪ Planned |
| **395** | **Whisper Training**<br>_Whisper training data, weak supervision, multilingual training, Whisper capabilities._ | [📖 Read Online](https://mbrenndoerfer.com/writing/whisper-training-weak-supervision-multilingual-asr) | ⚪ Planned |
| **396** | **Speech-Language Integration**<br>_speech encoder + LLM, audio tokens, speech-to-text-to-LLM vs end-to-end, speech LLM architectures._ | [📖 Read Online](https://mbrenndoerfer.com/writing/speech-language-integration-audio-llm-architectures) | ⚪ Planned |
| **397** | **Text-to-Speech**<br>_TTS architecture overview, vocoder role, TTS quality metrics, neural TTS approaches._ | [📖 Read Online](https://mbrenndoerfer.com/writing/text-to-speech-neural-architectures-acoustic-modeling) | ⚪ Planned |

</details>

<details id="volume-18-evaluation-factuality-and-reliability-4-parts-30-chapters">
<summary><b>📖 Volume 18 Evaluation, Factuality, and Reliability 4 parts · 30 chapters (30 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **405** | **Perplexity Evaluation**<br>_perplexity calculation, perplexity interpretation, perplexity limitations, comparing perplexities._ | [📖 Read Online](https://mbrenndoerfer.com/writing/perplexity-evaluation-language-models) | ⚪ Planned |
| **406** | **Cross-Entropy Loss**<br>_cross-entropy definition, bits-per-character, cross-entropy vs perplexity, loss curves._ | [📖 Read Online](https://mbrenndoerfer.com/writing/cross-entropy-loss-language-models-information-theory) | ⚪ Planned |
| **407** | **BLEU Score**<br>_n-gram precision, brevity penalty, BLEU formula, BLEU limitations, corpus vs sentence BLEU._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bleu-score-machine-translation-evaluation-nlp) | ⚪ Planned |
| **408** | **ROUGE Scores**<br>_ROUGE-N, ROUGE-L, ROUGE-W, ROUGE interpretation, ROUGE limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/rouge-scores-text-summarization-evaluation-metrics) | ⚪ Planned |
| **409** | **BERTScore**<br>_BERTScore computation, token alignment, BERTScore variants, BERTScore vs BLEU._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bertscore-semantic-text-evaluation-nlg) | ⚪ Planned |
| **410** | **Exact Match and F1**<br>_exact match scoring, token-level F1, normalization for matching, metric selection._ | [📖 Read Online](https://mbrenndoerfer.com/writing/exact-match-f1-nlp-evaluation-metrics) | ⚪ Planned |
| **411** | **Calibration**<br>_calibration definition, expected calibration error, calibration plots, calibration methods._ | [📖 Read Online](https://mbrenndoerfer.com/writing/calibration-machine-learning-confidence-accuracy-ece) | ⚪ Planned |
| **412** | **Evaluation Fundamentals**<br>_evaluation design principles, metric selection, evaluation pitfalls, evaluation frameworks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/evaluation-fundamentals-llm) | ⚪ Planned |
| **413** | **Benchmark Design**<br>_benchmark construction, dataset collection, annotation guidelines, benchmark validity._ | [📖 Read Online](https://mbrenndoerfer.com/writing/benchmark-design-construction-annotation-validity-nlp) | ⚪ Planned |
| **414** | **Evaluation Challenges**<br>_benchmark contamination, evaluation brittleness, gaming metrics, evaluation best practices._ | [📖 Read Online](https://mbrenndoerfer.com/writing/evaluation-challenges-contamination-brittleness-gaming-metrics) | ⚪ Planned |
| **415** | **MMLU**<br>_MMLU structure, subject coverage, MMLU evaluation protocol, MMLU limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mmlu-massive-multitask-language-understanding) | ⚪ Planned |
| **416** | **HellaSwag**<br>_HellaSwag task design, adversarial filtering, HellaSwag evaluation, HellaSwag saturation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/hellaswag-adversarial-filtering-commonsense-benchmark) | ⚪ Planned |
| **417** | **GSM8K**<br>_GSM8K problem types, chain-of-thought evaluation, GSM8K accuracy metrics, math reasoning assessment._ | [📖 Read Online](https://mbrenndoerfer.com/writing/gsm8k-evaluating-mathematical-reasoning-language-models) | ⚪ Planned |
| **418** | **HumanEval**<br>_HumanEval structure, functional correctness, pass@k metric, HumanEval limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/humaneval-code-generation-benchmark-pass-at-k) | ⚪ Planned |
| **419** | **MBPP**<br>_MBPP dataset, MBPP vs HumanEval, code evaluation challenges._ | [📖 Read Online](https://mbrenndoerfer.com/writing/mbpp-mostly-basic-python-programming-benchmark) | ⚪ Planned |
| **420** | **TruthfulQA**<br>_TruthfulQA design, truthfulness vs informativeness, TruthfulQA evaluation methods._ | [📖 Read Online](https://mbrenndoerfer.com/writing/truthfulqa-ai-truthfulness-evaluation) | ⚪ Planned |
| **421** | **Benchmark Contamination**<br>_contamination problem, contamination detection methods, n-gram overlap analysis, contamination mitigation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/benchmark-contamination-llm-detection-mitigation) | ⚪ Planned |
| **422** | **Benchmark Saturation**<br>_ceiling effects, benchmark retirement, dynamic benchmarks, benchmark evolution._ | [📖 Read Online](https://mbrenndoerfer.com/writing/benchmark-saturation-ai-evaluation-metrics) | ⚪ Planned |
| **423** | **Human Evaluation Design**<br>_evaluation interface design, task instructions, annotator selection, evaluation cost._ | [📖 Read Online](https://mbrenndoerfer.com/writing/human-evaluation-design-language-models) | ⚪ Planned |
| **424** | **Inter-Annotator Agreement**<br>_Cohen's kappa, Fleiss' kappa, Krippendorff's alpha, handling disagreement._ | [📖 Read Online](https://mbrenndoerfer.com/writing/inter-annotator-agreement-kappa-alpha-reliability) | ⚪ Planned |
| **425** | **Preference Evaluation**<br>_A/B comparison design, Elo rating systems, preference aggregation, statistical significance._ | [📖 Read Online](https://mbrenndoerfer.com/writing/preference-evaluation-pairwise-comparisons-elo-llm) | ⚪ Planned |
| **426** | **LLM-as-Judge: Scalable AI Evaluation with Language Models Learn how to build LLM-as-Judge evaluation pipelines: prompt design, judge model selection, calibration against human annotations, and bias mitigation.** | [📖 Read Online](https://mbrenndoerfer.com/writing/llm-as-judge) | ⚪ Planned |
| **427** | **Position Bias in LLM Judges**<br>_position bias measurement, bias mitigation (swapping), verbosity bias, sycophancy._ | [📖 Read Online](https://mbrenndoerfer.com/writing/position-bias-in-llm-judges) | ⚪ Planned |
| **428** | **Evaluation Prompt Engineering: Designing Reliable LLM Judges Learn how to design reliable LLM judge prompts using explicit criteria, few-shot examples, and chain-of-thought formatting to maximize evaluation accuracy.** | [📖 Read Online](https://mbrenndoerfer.com/writing/evaluation-prompt-engineering) | ⚪ Planned |
| **429** | **Hallucination Types in Language Models: A Complete Guide Learn how language models hallucinate: intrinsic and extrinsic hallucination, factual errors, fabrication, and inconsistency with NLI-based detection.** | [📖 Read Online](https://mbrenndoerfer.com/writing/hallucination-types) | ⚪ Planned |
| **430** | **Hallucination Detection: NLI, Self-Consistency & Learned Models Learn four methods for detecting LLM hallucinations: entailment-based scoring, knowledge base verification, self-consistency checks, and learned detection models.** | [📖 Read Online](https://mbrenndoerfer.com/writing/hallucination-detection) | ⚪ Planned |
| **431** | **Hallucination Causes**<br>_training data issues, exposure bias, knowledge gaps, generation pressure._ | [📖 Read Online](https://mbrenndoerfer.com/writing/hallucination-causes) | ⚪ Planned |
| **432** | **Hallucination Mitigation: RAG, Decoding, and Training Learn how to reduce LLM hallucination using retrieval augmentation, self-consistency decoding, DPO training, and calibrated uncertainty expression.** | [📖 Read Online](https://mbrenndoerfer.com/writing/hallucination-mitigation) | ⚪ Planned |
| **433** | **Attribution and Citation: Sourcing LLM Outputs Learn how language models link generated claims to source documents, evaluate citation accuracy with NLI, and measure attribution precision and recall.** | [📖 Read Online](https://mbrenndoerfer.com/writing/attribution-and-citation) | ⚪ Planned |
| **434** | **Uncertainty Quantification**<br>_confidence calibration, verbalized uncertainty, sampling-based uncertainty, uncertainty communication._ | [📖 Read Online](https://mbrenndoerfer.com/writing/uncertainty-quantification) | ⚪ Planned |

</details>

<details id="volume-19-responsible-secure-and-interpretable-language-ai-3-parts-24-chapters">
<summary><b>📖 Volume 19 Responsible, Secure, and Interpretable Language AI 3 parts · 24 chapters (24 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **441** | **Bias in Language Models**<br>_bias sources, bias types (demographic, cultural), bias in training data, bias amplification._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bias-in-language-models) | ⚪ Planned |
| **442** | **Bias Measurement**<br>_embedding association tests, generation bias metrics, classification bias metrics, bias benchmarks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/bias-measurement) | ⚪ Planned |
| **443** | **Bias Mitigation: Debiasing, CDA, and Fair Fine-tuning Practical techniques for reducing demographic bias in language models: data balancing, embedding debiasing, adversarial training, and prompt-based interventions.** | [📖 Read Online](https://mbrenndoerfer.com/writing/bias-mitigation) | ⚪ Planned |
| **444** | **Fairness Metrics: Demographic Parity, Equalized Odds, and Trade-offs Learn the key mathematical definitions of algorithmic fairness, from demographic parity to equalized odds, and why satisfying all metrics simultaneously is impossible.** | [📖 Read Online](https://mbrenndoerfer.com/writing/fairness-metrics) | ⚪ Planned |
| **445** | **Representation Harms**<br>_stereotyping, erasure, demeaning associations, measuring representation harms._ | [📖 Read Online](https://mbrenndoerfer.com/writing/representation-harms) | ⚪ Planned |
| **446** | **Interpretability Goals**<br>_debugging, trust, safety, scientific understanding, interpretability approaches overview._ | [📖 Read Online](https://mbrenndoerfer.com/writing/interpretability-goals) | ⚪ Planned |
| **447** | **Attention Visualization**<br>_attention weight extraction, attention head visualization, attention interpretation caveats, attention tools._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-visualization) | ⚪ Planned |
| **448** | **Attention Analysis Limitations**<br>_attention vs importance, attention manipulation studies, gradient-based alternatives._ | [📖 Read Online](https://mbrenndoerfer.com/writing/attention-analysis-limitations) | ⚪ Planned |
| **449** | **Probing Classifiers**<br>_linear probing methodology, probing task design, probing interpretation, control tasks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/probing-classifiers) | ⚪ Planned |
| **450** | **Probing Layers**<br>_layer selection, representation evolution, task localization, layer probing patterns._ | [📖 Read Online](https://mbrenndoerfer.com/writing/probing-layers) | ⚪ Planned |
| **451** | **Activation Patching**<br>_patching methodology, locating information, patching experiments, causal tracing._ | [📖 Read Online](https://mbrenndoerfer.com/writing/activation-patching) | ⚪ Planned |
| **452** | **Logit Lens**<br>_logit lens concept, intermediate vocabulary projection, tuned lens, lens interpretation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/logit-lens) | ⚪ Planned |
| **453** | **Sparse Autoencoders**<br>_SAE architecture, sparsity constraints, dictionary learning, SAE for LLMs._ | [📖 Read Online](https://mbrenndoerfer.com/writing/sparse-autoencoders) | ⚪ Planned |
| **454** | **Feature Interpretation**<br>_feature activation patterns, feature naming, automated interpretation, feature circuits._ | [📖 Read Online](https://mbrenndoerfer.com/writing/feature-interpretation) | ⚪ Planned |
| **455** | **Mechanistic Interpretability Reverse-engineer transformer networks into human-understandable algorithms by identifying circuits, induction heads, and mechanistic discoveries.** | [📖 Read Online](https://mbrenndoerfer.com/writing/mechanistic-interpretability) | ⚪ Planned |
| **456** | **Activation Steering: Steering Vectors and Representation Engineering Learn how steering vectors and activation addition let you modify language model behavior at inference time by injecting directional nudges into the residual stream.** | [📖 Read Online](https://mbrenndoerfer.com/writing/activation-steering) | ⚪ Planned |
| **457** | **Safety Risks**<br>_harmful content generation, misuse scenarios, unintended harms, safety threat models._ | [📖 Read Online](https://mbrenndoerfer.com/writing/safety-risks) | ⚪ Planned |
| **458** | **Red Teaming Learn how red teams systematically probe language models for safety failures, covering attack taxonomies, ASR metrics, RL-based automated attack generation, and real-world findings.** | [📖 Read Online](https://mbrenndoerfer.com/writing/red-teaming) | ⚪ Planned |
| **459** | **Jailbreaking**<br>_jailbreak techniques, prompt injection, adversarial suffixes, jailbreak defenses._ | [📖 Read Online](https://mbrenndoerfer.com/writing/jailbreaking) | ⚪ Planned |
| **460** | **Prompt Injection**<br>_direct prompt injection, indirect prompt injection, injection in RAG, injection defenses._ | [📖 Read Online](https://mbrenndoerfer.com/writing/prompt-injection) | ⚪ Planned |
| **461** | **Content Filtering**<br>_classification-based filtering, rule-based filtering, filter placement, filter evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/content-filtering) | ⚪ Planned |
| **462** | **Guardrails**<br>_input guardrails, output guardrails, guardrail frameworks, guardrail design._ | [📖 Read Online](https://mbrenndoerfer.com/writing/guardrails) | ⚪ Planned |
| **463** | **Memorization and Privacy in Language Models How language models memorize training data, methods for measuring extractable memorization, PII risks in web-scale corpora, and practical privacy mitigations.** | [📖 Read Online](https://mbrenndoerfer.com/writing/memorization-and-privacy) | ⚪ Planned |
| **464** | **Differential Privacy Learn how differential privacy protects training data in language models, from the mathematical guarantee to DP-SGD, privacy budgets, and practical LLM fine-tuning.** | [📖 Read Online](https://mbrenndoerfer.com/writing/differential-privacy) | ⚪ Planned |

</details>

<details id="volume-20-applications-production-and-compound-ai-systems-2-parts-16-chapters">
<summary><b>📖 Volume 20 Applications, Production, and Compound AI Systems 2 parts · 16 chapters (16 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **478** | **Text Generation Applications**<br>_creative writing, content generation, text transformation, generation quality control. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/text-generation-applications) | ⚪ Planned |
| **479** | **Summarization**<br>_extractive vs abstractive, length control, faithfulness, multi-document summarization. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/summarization) | ⚪ Planned |
| **480** | **Question Answering**<br>_open-domain QA, reading comprehension, knowledge-intensive QA, QA evaluation. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/question-answering) | ⚪ Planned |
| **481** | **Information Extraction**<br>_named entity recognition, relation extraction, event extraction, structured output generation. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/information-extraction) | ⚪ Planned |
| **482** | **Classification Applications**<br>_sentiment analysis, intent detection, topic classification, zero-shot classification. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/classification-applications) | ⚪ Planned |
| **483** | **Conversational AI**<br>_dialogue management, context tracking, persona consistency, conversation evaluation. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/conversational-ai) | ⚪ Planned |
| **484** | **Creative Applications**<br>_story generation, poetry, code creativity, creative constraints and control. Read_ | [📖 Read Online](https://mbrenndoerfer.com/writing/creative-applications) | ⚪ Planned |
| **491** | **Model Serving**<br>_serving frameworks, model loading, request handling, serving configuration._ | [📖 Read Online](https://mbrenndoerfer.com/writing/model-serving-frameworks-loading-request-handling-configuration) | ⚪ Planned |
| **492** | **Latency Optimization**<br>_latency breakdown, batching latency, streaming responses, latency monitoring._ | [📖 Read Online](https://mbrenndoerfer.com/writing/latency-optimization-batching-streaming-monitoring-llm-serving) | ⚪ Planned |
| **493** | **Throughput Optimization**<br>_batch size tuning, GPU utilization, concurrent requests, throughput measurement._ | [📖 Read Online](https://mbrenndoerfer.com/writing/throughput-optimization-batch-size-gpu-utilization-concurrent) | ⚪ Planned |
| **494** | **Auto-scaling**<br>_scaling metrics, horizontal scaling, scale-up vs scale-out, scaling policies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/auto-scaling-horizontal-vertical-policies-llm-production) | ⚪ Planned |
| **495** | **Model Routing**<br>_model selection, A/B testing, model cascades, routing strategies._ | [📖 Read Online](https://mbrenndoerfer.com/writing/model-routing-selection-ab-testing-cascades-strategies) | ⚪ Planned |
| **496** | **Caching**<br>_prompt caching, semantic caching, cache invalidation, cache hit rates._ | [📖 Read Online](https://mbrenndoerfer.com/writing/caching-prompt-semantic-invalidation-hit-rates-llm) | ⚪ Planned |
| **497** | **Monitoring**<br>_metrics collection, alerting, logging, dashboards._ | [📖 Read Online](https://mbrenndoerfer.com/writing/monitoring-metrics-alerting-logging-dashboards-llm-production) | ⚪ Planned |
| **498** | **Quality Monitoring**<br>_output quality metrics, drift detection, regression detection, quality alerts._ | [📖 Read Online](https://mbrenndoerfer.com/writing/quality-monitoring-drift-detection-regression-alerts-llm) | ⚪ Planned |
| **499** | **Cost Management**<br>_cost modeling, cost optimization, cost allocation, cost monitoring._ | [📖 Read Online](https://mbrenndoerfer.com/writing/cost-management-modeling-optimization-allocation-llm-production) | ⚪ Planned |

</details>

<details id="language-ai-handbook-a-appendix-state-of-language-ai-2025-2-parts-14-chapters">
<summary><b>📖 Language AI Handbook A Appendix State of Language AI 2025 2 parts · 14 chapters (14 Chapters)</b></summary>

| Ch | Chapter Title & Concepts | Reading Reference | Status |
| :---: | :--- | :---: | :---: |
| **500** | **Constitutional AI**<br>_constitutional principles, critique and revision, CAI training, CAI effectiveness._ | [📖 Read Online](https://mbrenndoerfer.com/writing/constitutional-ai-principles-critique-revision-cai-training) | ⚪ Planned |
| **501** | **Process Reward Models**<br>_outcome vs process reward, PRM training, PRM for math, PRM limitations._ | [📖 Read Online](https://mbrenndoerfer.com/writing/process-reward-models-prm-outcome-math-training-limitations) | ⚪ Planned |
| **502** | **Test-Time Compute**<br>_multiple sampling, iterative refinement, compute-optimal inference, scaling test-time compute._ | [📖 Read Online](https://mbrenndoerfer.com/writing/test-time-compute-scaling-sampling-refinement-optimal-inference) | ⚪ Planned |
| **503** | **Retrieval-Augmented Training**<br>_RETRO architecture, retrieval during training, retrieved context integration._ | [📖 Read Online](https://mbrenndoerfer.com/writing/retrieval-augmented-training-retro-architecture-context-integration) | ⚪ Planned |
| **504** | **Long-Form Generation**<br>_outline-based generation, hierarchical generation, coherence maintenance, long-form evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/long-form-generation-outline-hierarchical-coherence-evaluation) | ⚪ Planned |
| **505** | **Watermarking**<br>_watermarking schemes, statistical detection, watermark robustness, watermark evaluation._ | [📖 Read Online](https://mbrenndoerfer.com/writing/watermarking-llm-schemes-statistical-detection-robustness) | ⚪ Planned |
| **506** | **Model Cards**<br>_model card contents, intended use documentation, limitation documentation, model card best practices._ | [📖 Read Online](https://mbrenndoerfer.com/writing/model-cards-documentation-intended-use-limitations-best-practices) | ⚪ Planned |
| **507** | **Responsible Deployment**<br>_release decisions, staged release, access control, deployment monitoring._ | [📖 Read Online](https://mbrenndoerfer.com/writing/responsible-deployment-staged-release-access-control-monitoring) | ⚪ Planned |
| **508** | **Scaling Frontiers**<br>_scaling limits, beyond power laws, data wall, architectural innovations for scale._ | [📖 Read Online](https://mbrenndoerfer.com/writing/scaling-frontiers-limits-power-laws-data-wall-architecture) | ⚪ Planned |
| **509** | **Efficiency Frontiers**<br>_efficient architectures, hardware co-design, inference efficiency, training efficiency advances._ | [📖 Read Online](https://mbrenndoerfer.com/writing/efficiency-frontiers-architectures-hardware-codesign-inference) | ⚪ Planned |
| **510** | **Capability Frontiers**<br>_emerging capabilities, world models, planning and agency, multimodal reasoning advances._ | [📖 Read Online](https://mbrenndoerfer.com/writing/capability-frontiers-emerging-world-models-planning-multimodal) | ⚪ Planned |
| **511** | **Alignment Challenges**<br>_scalable oversight, alignment tax, goal mis-specification, long-term alignment research._ | [📖 Read Online](https://mbrenndoerfer.com/writing/alignment-challenges-scalable-oversight-goal-specification-research) | ⚪ Planned |
| **512** | **Societal Implications**<br>_labor market effects, access and equity, regulation landscape, governance frameworks._ | [📖 Read Online](https://mbrenndoerfer.com/writing/societal-implications-labor-equity-regulation-governance-ai) | ⚪ Planned |
| **513** | **Research Directions**<br>_open problems, promising research areas, benchmark gaps, community priorities._ | [📖 Read Online](https://mbrenndoerfer.com/writing/research-directions-open-problems-benchmarks-community-priorities) | ⚪ Planned |

</details>

---

## ⚡ How to Run the Notebooks

### ☁️ Option 1: One-Click Launch in Google Colab (Recommended)
You do not need to install Python, PyTorch, or Jupyter locally to explore this handbook:
1. Navigate to the **Table of Contents** table above.
2. Click the **[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()** badge next to the chapter you want to study.
3. The notebook will open immediately in your browser via Google Colab.
4. Go to **Runtime → Run all** (or press `Ctrl+F9`) to execute the interactive code and quizzes!

---

### 💻 Option 2: Run Locally on Your Machine

If you prefer to run the code locally using **Jupyter Lab** or **VS Code**:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aimlstudy1010-engineer/Language-AI-Handbook.git
   cd Language-AI-Handbook
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # On macOS/Linux:
   python3 -m venv .venv
   source .venv/bin/activate

   # On Windows (PowerShell):
   python -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

3. **Install dependencies:**
   ```bash
   pip install --upgrade pip
   pip install jupyterlab ipywidgets numpy pandas matplotlib
   ```

4. **Launch Jupyter Lab:**
   ```bash
   jupyter lab
   ```
5. Navigate to the `Text as Data/` directory in the file sidebar and open [`text-normalization.ipynb`](Text%20as%20Data/text-normalization.ipynb) or [`character-encoding.ipynb`](Text%20as%20Data/character-encoding.ipynb).

---

## 📁 Repository Directory Structure

```text
Language-AI-Handbook/
│
├── README.md                                  # You are here! Interactive Handbook & Syllabus
├── LICENSE                                    # MIT Open Source License
│
├── Text as Data/                              # Volume 1: Part I
│   ├── character-encoding.ipynb               # Chapter 01: ASCII, Unicode, UTF-8, BOM & Mojibake
│   └── text-normalization.ipynb               # Chapter 02: NFC/NFD/NFKC/NFKD, Case Folding, Security & Quiz
│
├── Classical Text Representations/            # Volume 1: Part II (Upcoming)
│   ├── bag-of-words.ipynb                     # Chapter 06: Document-Term matrices & Sparse CSR/CSC
│   ├── tf-idf.ipynb                           # Chapter 13: TF-IDF vectorization & scikit-learn
│   └── bm25.ipynb                             # Chapter 14: Probabilistic IR & BM25 Ranking
│
├── Distributional Semantics/                  # Volume 1: Part III (Upcoming)
│   ├── co-occurrence-matrices.ipynb           # Chapter 16: Word-word matrices & windowing
│   ├── pointwise-mutual-information.ipynb     # Chapter 17: PMI & PPMI associations
│   └── singular-value-decomposition.ipynb     # Chapter 18: Truncated SVD & Latent Semantic Analysis
│
└── ... (Volumes 2 through 20 structured sequentially)
```

---

## 💡 Chapter Highlights: Inside Chapter 02 (Text Normalization)

Here is a glimpse of what each notebook delivers:

```python
from text_normalizer import TextNormalizer

# Create a production normalization pipeline
normalizer = TextNormalizer(
    form="NFKC",                # Full compatibility composition (expands ligatures, converts full-width)
    case_fold=True,             # Multilingual case folding (handles German 'ß', Greek 'Σ')
    strip_accents=False,        # Conservative: preserves accents to avoid collisions (año != ano)
    remove_invisible=True,      # Strips malicious Zero-Width Spaces (U+200B)
    strip_redundant_spaces=True # Normalizes non-breaking, em, en, and ideographic spaces
)

raw_input = "  T​e xﬁ   Normaliﬂation １２３  "
clean_output = normalizer(raw_input)
# Result: 'texfi normalization 123'
```

Every notebook ends with an interactive, instant-feedback quiz:

<p align="center">
  <img src="https://img.shields.io/badge/Self--Assessment-Automated_Grading-brightgreen?style=for-the-badge&logo=target" alt="Automated Grading">
</p>

---

## 🤝 Contributing & Community

Contributions, suggestions, and corrections are welcome! If you find a typo, want to suggest an interactive visualization, or submit an implementation for an upcoming chapter:
1. **Fork** the repository.
2. Create your feature branch (`git checkout -b feature/ch03-regular-expressions`).
3. Commit your changes (`git commit -m 'feat: add chapter 03 notebook'`).
4. Push to the branch (`git push origin feature/ch03-regular-expressions`).
5. Open a **Pull Request**.

---

## 📜 Acknowledgments & Citation

This interactive codebook curriculum is directly inspired by and builds upon the comprehensive literature in:
- **[Language AI Handbook](https://mbrenndoerfer.com/books/language-ai-handbook)** by **Michael Brenndoerfer** — An exhaustive 20-volume guide from classical NLP to modern LLM engineering.
- **The Unicode Consortium Standard Annex #15** (Unicode Normalization Forms).
- The Python NLP community (`nltk`, `spacy`, `huggingface`, `tiktoken`).

### License
This project is licensed under the **[MIT License](LICENSE)** — feel free to use this code for personal study, academic courses, or commercial research.

---
<p align="center">
  <b>Built with ❤️ for AI Researchers, NLP Engineers, and LLM Practitioners.</b><br>
  <i>Star ⭐ this repo if you find it helpful on your NLP journey!</i>
</p>
