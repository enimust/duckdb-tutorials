# DuckDB tutorials

Tutorials for duckdb usage in CS 234.

A. **1_Create_Wiki_DuckDB.ipynb**: A tutorial that shows how one can create a DuckDB database from a large CSV file. It also shows how to query the database to create CSV files for a question we are interested in.  

B. **2_DuckDB_Tutorial.ipynb**: A tutorial that shows how to connect to a remote DuckDB database and how to generate queries to get data from it. DuckDB is faster than pandas, and makes sense when our data is big (since Github, where we will host our streamlit code/files, has a limit on the size of files we can upload).  

C. **3_Zero_shot_Classification_Tutorial**: A tutorial that shows how to use a HuggingFace classifier to label German and French articles as being about politics or not-politics. It uses a ground truth dataset labeled by Gemini. It shows how to evaluate the Zero-shot classifiers. For both languages, they hover around 0.7 to 0.77 accuracy, but the F1 scores for the "P" (political) class are pretty bad. 

There is a folder named **data** with several CSV files that were used by the third tutorial. Because the 3rd tutorial was run via Google Colab, you will need to upload the files in the Google Colab space to use them.
