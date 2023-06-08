# NLP_Project

Explanation: 

1- As explained in the report, the dataset can be download from this link: https://data.statmt.org/cc-100/ . It is the portuguese language, and after the download, the file can be extracted, although it is very large (around 50 GB). The file should be renamed "pt_not_full.txt". If the professors want a smaller version to work with, the groups is available to make a much smaller version available for download.

2- Run only the notebooks, and in the following order: NLP1_1, NLP1_2, and NLP2. Notebook NLP1_1 will stop at a cell with only the word "error" as content, which should be removed. 

3- To arrive at the results used to create the "Most meaningful words w.r.t data % used" (in notebook NLP1) and "Most meaningful words w.r.t matrix rank" (this graph has the incorrect name in the notebook, with the same title as the previous one, but in notebook NLP2) graphs, run NLP1_1.py and and NLP2.py and check the result of the final print statement.

4 (Additional) NLP_numpy does not have functionality, as it only contains code of a poorly working version of the neural network implemented with only numpy. 
To run the NN_NLP notebook, a couple of things must be changed. The NN_NLP notebook will stop in a cell which contains the following code:

![image](https://github.com/Sebastiao-C/NLP_Project/assets/80716012/c480fa35-3ada-4e58-9bdd-cfc099f0abba)

The contents of the range() function should be changed to range(1), and the name of the file in quotes should be sentences_for_NN{k}.txt, instead of the current content. In the cell that contain the code 

![image](https://github.com/Sebastiao-C/NLP_Project/assets/80716012/e7243bec-a822-4612-bd1d-62bab8514b48)

the -475 should be changed to -219.

Finally, the cell with the code

![image](https://github.com/Sebastiao-C/NLP_Project/assets/80716012/26a44a82-86f6-4002-a89f-113c90dd11d9)

should be deleted
