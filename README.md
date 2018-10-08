# Text Mining Lab

0. 00_Configure_Folder_Structure.ipynb
   - This notebook intends to create a flexible folder structure, which aims to minimize the effort to change the folder path every time.
1. 01-Convert_JSON_to_TXT.ipynb
   - Since someone has already preprocessed all the original PDF files for business report, what we got is the human-readable JSON files, which is quite nice. Nevertheless, there are so much useless information inside. Therefore, we decide to extract useful information from JSON file and convert to TXT file, in order to speed up the processing speed.
2. 02-Preprocessing.ipynb
   - 80:20 rule of data science: 80% of the work are spent on pre-processing, data cleansing; 20% of the work are spent on data analysis and visualization
3. 03-Corpus_Generation.ipynb
   - After preprocessing, we want to generate text corpus for each document, which consists of a list of potentially duplicated words.
4. 04-TF-IDF_Raw_Implementation.ipynb
   - TF-IDF, short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.
5. 05-TF-IDF_ScikitLearn.ipynb
   - Implement TF-IDF using Scikit-Learn Library
6. 06-LSI_Search.ipynb
   -  LSI overcomes two of the most problematic constraints of Boolean keyword queries: multiple words that have similar meanings (synonymy) and words that have more than one meaning (polysemy)
7. 07-LDA.ipynb
   - Topic Modeling, a method for discovery of representative groups of words from a set of documents, which implicitly present topics. In addition, the technique we use is LDA, which is one of the most common topic modeling approaches. The basic idea of LDA is to regard every document as a mixture of topics and to assign every word in a document to one of the document's topics. In the context of LDA, the topic is represented by a probability distribution over all words.
8. 08-Hierarchical_LDA.ipynb
   - Hierarchical Latent Dirichlet Allocation (hLDA) addresses the problem of learning topic hierarchies from data. The model relies on a non-parametric prior called the nested Chinese restaurant process, which allows for arbitrarily large branching factors and readily accommodates growing data collections. The hLDA model combines this prior with a likelihood that is based on a hierarchical variant of latent Dirichlet allocation 
