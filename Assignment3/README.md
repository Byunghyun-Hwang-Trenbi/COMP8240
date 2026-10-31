**Notebook Structure & Outline**
The primary workflow is implemented in COMP8240_DeepSurv_Survival_Analysis.ipynb and follows this detailed outline:

A. Replication - Original Dataset
A-1. Import Libraries
A-2. Load Original Data
A-3. Model Development (DeepSurv)
A-4. Model Development (CPH and RSF)

Research Question 1: Does DeepSurv perform effectively on a domain-informed dataset?
B. Test Models - Cirrhosis Dataset
B-1. Load Cirrhosis Data
B-2. Preprocess Data
B-3. Test Models on the domain-guided cirrhosis survival dataset

C. Test Models - German Credit Dataset
C-1. Load German Bank Data
C-2. Preprocess Data
C-3. Test Models on the domain-guided German credit dataset

Research Question 2: Does DeepSurv outperform its performance on a raw dataset when using a domain-informed dataset?
D. Test Models - Cirrhosis Dataset (Raw Features)
E. Test Models - German Credit Dataset (Raw Features)

LLM-as-a-Judge
F. LLM-as-a-Judge (Cirrhosis Dataset)

**Getting Started in Google Colab**

1. Mount Google Drive & Load Data
Ensure your data files (cirrhosis.csv, german.data, metabric_IHC4_clinical_train_test.h5) are located in your Google Drive working directory, and run the mounting block

2. Install Libraries 
The required survival analysis and deep learning libraries are automatically installed via the notebook cells

3. Configure Gemini API Key
Before executing Section F (LLM-as-a-Judge), ensure you generate and provide your Google Gemini API key within the notebook environment to authorize automated evaluation requests.

**Author**

Byunghyun Hwang (Master of Data Science, Macquarie University)
