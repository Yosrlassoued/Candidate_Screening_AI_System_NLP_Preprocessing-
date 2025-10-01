## 🎯 Goal  
The objective of this notebook is to build a **minimal but complete NLP workflow** for resume screening.  
We will process a small set of candidate resumes and experiment with different text representation techniques to analyze similarity and retrieval.  

---

## 📂 Dataset  
- ~5 sample resumes in **.txt** format  

---

## ⚙️ Workflow Overview  

1. **Load Data**
   - Import and preview ~5 sample resumes  

2. **Text Preprocessing**
   - Tokenization  
   - Stopword removal  
   - Stemming  
   - Lemmatization  
   - Part-of-Speech (POS) tagging  
   - Named Entity Recognition (NER)  

3. **Document Embeddings**
   - Word2Vec **CBOW**  
   - Word2Vec **Skip-gram**  
   - **BERT** embeddings  

4. **Analysis & Visualization**
   - Compare embedding spaces  
   - Compute nearest neighbors between resumes  
   - Visualize similarities (e.g., scatter plots, clustering)  

5. **Discussion**
   - Trade-offs between CBOW, Skip-gram, and BERT  
   - Observations on resume similarity and screening  

---

## ✅ Expected Outcome  
By the end of this notebook, we will have:  
- A **pipeline** for preprocessing resumes  
- Multiple **document embeddings** for comparison  
- **Visualizations** of resume similarity  
- A discussion of **advantages and limitations** of each embedding approach
