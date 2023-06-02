# NLP_Project

Explanation: 

1- Ignore 300000-lines.txt and 500000-lines.txt.

2- NLP has useful code but can be ignored by now.

3- NLP_1000000_0.ipynb and NLP_1000000_1.ipynb serve two different purposes: notebook 0 (the first one) serves to collect the first million lines off the text corpus, establish a minimum occurrence threshold (150) for the word to belong to the dictionary (which results in 11988 words), and calculate the first co-occurrence matrix; notebook 1 (the second one) serves to collect subsequent sets of a million words (skipping the first N million controlled by the initial variables Nskip), import the dictionaries (with relevant words and indices) from notebook 0, compute the co-occurrence matrix for the same words and store that matrix.

4- NLP_together joins the matrix from notebook 0 and 8 other matrices obtained from running notebook 1 8 times (skipping 1 million lines the first time, 2 million lines the second time, etc...), imports the same relevant dictionaries, and ends with doing the same analysis that is present at the end of both notebooks 0 and 1.

5- output.csv and output2.csv (poor names) have the relevant dicionaries that are imported in notebooks 1 and NLP_together.
