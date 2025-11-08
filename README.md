[![Lexical Semantic Change Detection Poster](poster_thumbnail.png)]([https://github.com/nicoolesy/nicoolesy-SI671_Lexical-Semantic-Change-Detection/blob/main/671_final_poster-copy.pdf](https://github.com/nicoolesy/Lexical-Semantic-Change-Detection/blob/main/final_poster-copy.pdf))
# Lexical Semantic Change Detection
**Authors:** Nicole Chen, Tammy Yang, Tzu-Yu Ko  
**Affiliation:** University of Michigan  

## Research Objectives
1. **Detect and quantify lexical semantic changes** in Spanish.  
2. **Measure the evolution of Spanish word meanings** over time.  

---

## Introduction
Traditionally, linguists relied on manually annotated word lists for studying semantic change in vocabulary. Recent advancements in computational linguistics and artificial intelligence have enabled self-driving language models to analyze massive text corpora.  

This project applies **Lexical Semantic Change Detection (LSCD)** techniques to identify how Spanish words have shifted in meaning over time. By leveraging **Word2Vec** and large-scale historical corpora, the research contributes to understanding semantic evolution—insights that can be applied in digital journalism, AI translation systems, and conversational agents.

---

## Data
Two diachronic Spanish language corpora were used:

| Corpus | Time Period | Tokens |
|---------|--------------|---------|
| Old Corpus | 1810–1906 | ~13M |
| Modern Corpus | 1994–2020 | ~22M |

Data were preprocessed using **spaCy**, and selected target words were analyzed to assess their semantic shifts over time.  

---

## Models and Methods
- **Word Embeddings:** Word2Vec trained on historical and modern corpora.  
- **Semantic Change Detection:** Lexical Semantic Change Detection (LSCD) model applied to identify evolving meanings.  
- **Vector Comparison Techniques:**  
  - Skip-gram with Negative Sampling (SGNS)  
  - Orthogonal Procrustes (OP) alignment  
  - Cosine Similarity (CS) for vector distance measurement  
- **Evaluation Metrics:** Spearman’s Correlation Coefficient and COMPARE scores.  

---

## Findings
- The models successfully detected **semantic evolution** in selected Spanish words.  
- **Spearman’s Correlation Coefficient (0.543)** and **COMPARE score (0.561)** confirmed consistent performance in capturing meaning changes across corpora.  
- Results revealed meaningful differences between 19th-century and modern Spanish, confirming the potential of LSCD for analyzing linguistic drift and digital lexicography.

---

## Discussion
The findings support the use of computational models in detecting word sense evolution and highlight promising directions for future work, including:
1. Cross-linguistic comparative studies  
2. Fine-tuning LSCD for specific domains  
3. Multimodal semantic change detection  
4. Applications in AI-based retrieval and translation systems  

---

## Tools and Technologies
- **Python**
- **spaCy**
- **Gensim (Word2Vec)**
- **scikit-learn**
- **NumPy / pandas**
- **Matplotlib**

---

## Example Output
Visualizations include:
- **Cosine Similarity Bar Charts** for target words  
- **3D Scatter Plots** representing word vector spaces  
- **Comparative Correlation Analysis** between time periods  

---

## Acknowledgments
Special thanks to the **University of Michigan School of Information** for academic guidance and access to linguistic data resources.

---

## 📚 Keywords
`#SemanticChange` · `#ComputationalLinguistics` · `#WordEmbeddings` · `#NaturalLanguageProcessing` · `#AIApplication`
