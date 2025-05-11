# PubMed_BigData_Analysis

1. PubMedData/parquet (Folder):
Contains raw data files in Parquet format, directly extracted from PubMed XML files. The Parquet format is used for efficient storage and fast data processing within Apache Spark. These files represent the foundational data for further analysis.

2. SCHEMA_SELECTION.ipynb:
A Jupyter Notebook dedicated to schema design and selection for the PubMed dataset. It includes defining data structures, handling nested JSON formats, and optimizing the representation of metadata and citation information.

3. Automated_Citation_Retrieval_with_PubMed_E_utilities_API_Final_Version_only_with_abstracts.ipynb:
A Jupyter Notebook that automates the retrieval of citation data from PubMed using the E-utilities API. It specifically focuses on fetching citation counts for articles that contain abstracts, enriching the dataset with citation information.

4. EDA.ipynb:
This Jupyter Notebook performs Exploratory Data Analysis (EDA) on the PubMed dataset. It includes data cleaning, distribution analysis (e.g., publication years, citation counts), keyword frequency analysis, and visualization of data patterns. The primary goal is to explore, clean, and preprocess the data to gain insights and prepare it for advanced analytics. This EDA is foundational for further data enrichment and advanced analytics. By cleaning and structuring the data at this stage, the notebook ensures that downstream tasks are performed on reliable and comprehensive datasets.

5. PUBMED_GENEONTOLOGY.ipynb:
This notebook focuses on Gene Ontology (GO) term extraction and classification. It maps biomedical terms from PubMed abstracts to GO categories: Biological Process (BP), Molecular Function (MF), and Cellular Component (CC), enabling semantic classification of articles.

6. LDA.ipynb:
Implements Latent Dirichlet Allocation (LDA) for topic modeling on the PubMed abstracts. The notebook extracts thematic clusters of biomedical literature, helping identify key topics and areas of research.

7. PUBMED_GRAPHFRAMES.ipynb:
Uses GraphFrames in Apache Spark to construct citation and author collaboration networks from the PubMed dataset. Analyzes the connectivity, centrality, and influence of scientific articles through graph-based metrics.

8. PUBMED_Spark_GraphFrames.ipynb:
Another notebook leveraging GraphFrames for more advanced graph analytics on PubMed data. It explores citation trees, author collaboration networks, and the propagation of scientific influence across connected publications.

9. high_impact_pmid_journal.parquet:
A processed dataset extracted from previous work, containing only PMIDs from high-impact journals. The high-impact threshold was set above 20 to filter significant publications.

10. impact factor journals.xlsx:
An Excel file containing a list of high-impact biomedical journals with an impact factor threshold of 20 or higher. Used to match and identify high-quality articles within the PubMed dataset.

11. pmid_citations_901.csv:
A CSV file containing citation data extracted using the PubMed E-utilities API from the notebook Automated_Citation_Retrieval_with_PubMed_E_utilities_API_Final_Version_only_with_abstracts. It includes PMIDs and their respective citation counts.

![image](https://github.com/user-attachments/assets/e549d46e-12ae-456e-b060-285002ad9b84)

![image](https://github.com/user-attachments/assets/dd5977c4-b318-4da9-8630-4bb4b8b47586)

![image](https://github.com/user-attachments/assets/b310274c-d4cd-4f0f-beeb-4bf3a13056c0)

![image](https://github.com/user-attachments/assets/bbbf0b29-e886-4958-8b11-000729bff652)

![image](https://github.com/user-attachments/assets/208a52d8-fbd6-4dbd-b24a-e3ed35e6b1d0)

![image](https://github.com/user-attachments/assets/3b3f11de-2994-4fb1-ba46-5533a64dcc85)

![image](https://github.com/user-attachments/assets/ebbc4e10-f869-402d-bdf6-7e901d485339)

![image](https://github.com/user-attachments/assets/da56167a-7dd2-4958-8245-e3a4eb5fc466)

![image](https://github.com/user-attachments/assets/821f7035-5385-48e7-9b4c-a7a9f379af0a)

![image](https://github.com/user-attachments/assets/df33e094-97ee-4dc9-b5e7-6837f0085338)

![image](https://github.com/user-attachments/assets/974ec8f8-623d-4412-be71-66abec7486d2)

![image](https://github.com/user-attachments/assets/79843ca7-f007-41b2-8666-35055f903c58)

![image](https://github.com/user-attachments/assets/1c0e6669-8587-44bd-91c0-77a1d9ee32b9)

![image](https://github.com/user-attachments/assets/2e975387-7634-42fb-88bc-42b800a505ca)

![image](https://github.com/user-attachments/assets/ab3309e4-473e-4bae-91c7-4815e7a9f13e)

![image](https://github.com/user-attachments/assets/e452a071-4347-4e71-925b-229ba2c1825f)

![image](https://github.com/user-attachments/assets/79cf9efe-2fb1-465e-82ae-bf2530b5183d)

![image](https://github.com/user-attachments/assets/ac8b04bd-f171-44cc-b0e4-305bbca74511)

![image](https://github.com/user-attachments/assets/9623830d-2894-47e1-bef2-08d83855d3c0)

![image](https://github.com/user-attachments/assets/734b099d-c5b6-4ccb-8eec-8e4ab0ada4f5)
