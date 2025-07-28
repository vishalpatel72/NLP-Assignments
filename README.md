# **Language Modeling – Statistical vs Neural Approaches**

This repository contains implementations and comparisons of **Statistical Language Models (SLMs)** and **Neural Language Models (NLMs)**.
The work is divided into two assignments:

1. **Assignment 1:** Building and evaluating **N‑gram Statistical Language Models**
2. **Assignment 2:** Building and evaluating **Neural Language Models**

---

## **Assignment 1 – Statistical Language Model (SLM)**

* Built **N‑gram language models** on two different text corpora.
* Implemented **smoothing techniques**:

  * **Kneser‑Ney smoothing**
  * **Witten‑Bell smoothing**
* Calculated **perplexity scores**:

  * Sentence‑level perplexity for each model on each corpus
  * Average perplexity score on the training corpus
* **Insights:**

  * Smoothing significantly improved model robustness on unseen data.

---

## **Assignment 2 – Neural Language Model (NLM)**

* Implemented a **Neural Language Model** using neural networks.
* Compared **neural model performance vs statistical N‑gram models** on the same corpora.
* Evaluated using **perplexity metrics** for consistency.
* **Insights:**

  * Neural models handle long‑range dependencies better than statistical models.
  * Statistical models are simpler and interpretable but limited in handling unseen sequences.

---

## **Comparison & Key Takeaways**

* **Statistical LMs:** Efficient and interpretable; rely heavily on smoothing techniques to handle data sparsity.
* **Neural LMs:** Learn rich word representations and context, typically achieving **lower perplexity** on test data.
* **Overall:** Neural approaches outperform statistical models on language modeling tasks but require more computational resources.

---

## **Requirements**

* Python 3.x
* NumPy, Pandas
* PyTorch / TensorFlow (for Neural LM)
* Jupyter Notebook

---

## **Usage**

1. Run notebooks for Assignment 1 to build statistical models and compute perplexity.
2. Run notebooks for Assignment 2 to build and evaluate neural models.
3. Compare perplexity outputs to analyze performance differences.

---

## **License**

This project is licensed under the MIT License.


