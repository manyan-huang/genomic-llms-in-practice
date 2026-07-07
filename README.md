# Genomic LLMs in Practice

A hands-on tutorial on using Transformer-based large language models (LLMs) for genomics with Hugging Face and PyTorch.

## Overview

Although originally developed for natural language processing, Transformer-based large language models have become powerful tools for modeling genomic sequences. DNA can be viewed as a language over a four-letter alphabet, where nucleotide sequences are tokenized into representations such as single nucleotides, k-mers, or byte-pair encodings. Modern genomic foundation models—including DNABERT, GENA-LM, Nucleotide Transformer, Evo 2, AlphaGenome, and related models—leverage Transformer architectures to capture long-range dependencies within DNA sequences and achieve state-of-the-art performance across many genomics tasks.

This repository accompanies a hands-on tutorial introducing genomic LLMs, covering both the theoretical foundations and practical implementation using the Hugging Face ecosystem.

---

## Repository Structure

```
.
├── Lectures/                    # Tutorial slides covering genomic LLM concepts
├── Guided Hands-On/             # Step-by-step notebooks used during the tutorial
├── Workshop/                    # Independent exercises and solutions
├── InstaDeepAI_ntv3_tutorials/  # Official Nucleotide Transformer v3 examples
├── nucleotide_transformer_dna_sequence_modelling_with_peft.ipynb
└── README.md
```

### Lectures

The lecture slides introduce the theoretical foundations of genomic foundation models, including:

- Transformer architectures for DNA sequences
- DNA tokenization strategies
- Long-context modeling
- Pretraining paradigms
- Genomic foundation models
- Model embeddings and interpretability

### Guided Hands-On

Follow the notebooks sequentially to learn how to:

- Load genomic datasets
- Tokenize DNA sequences
- Use pretrained genomic LLMs from Hugging Face
- Extract embeddings
- Fine-tune models
- Evaluate downstream performance

### Workshop

The workshop contains practical exercises where participants will:

- Load a pretrained genomic foundation model
- Fine-tune it on a downstream prediction task
- Perform inference
- Evaluate model performance

### InstaDeepAI_ntv3_tutorials

Additional example notebooks provided by InstaDeep demonstrating the capabilities of **Nucleotide Transformer v3**.

---

## Learning Objectives

After completing this tutorial, you should be able to:

- Explain why Transformer-based models are effective for DNA sequences.
- Understand different genomic tokenization strategies.
- Load and use pretrained genomic foundation models.
- Fine-tune genomic LLMs using the Hugging Face Trainer API.
- Extract and analyze sequence embeddings.
- Apply genomic LLMs to downstream genomics prediction tasks.

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- scikit-learn
- Jupyter Notebook

---

## Further Reading

### Genomic Foundation Models

- **DNABERT**
- **GENA-LM**
- **Nucleotide Transformer**
- **Evo 2**
- **HyenaDNA**
- **Caduceus**
- **AlphaGenome**
- **AlphaMissense**

### Interpretability

**Evo 2** demonstrates the use of **mechanistic interpretability** to understand biological features learned by genomic foundation models.

- Paper: https://doi.org/10.1038/s41586-026-10176-5
- Mechanistic Interpretability Glossary: https://www.neelnanda.io/mechanistic-interpretability/glossary

**GENA-LM** applies **Integrated Gradients** for token attribution, providing an alternative approach to the attribution methods demonstrated in the hands-on exercises.

- https://doi.org/10.1093/nar/gkae1310

### Embeddings

**AlphaGenome** discusses how learned sequence embeddings can be extracted and utilized for downstream genomics tasks.

- https://doi.org/10.1038/s41586-025-10014-0

**Nucleotide Transformer** explores multiple strategies for pooling and processing embeddings for downstream prediction tasks.

- https://doi.org/10.1038/s41592-024-02523-z

---

## Citation

If you find these materials useful, please cite the corresponding tutorial and the original model publications.
