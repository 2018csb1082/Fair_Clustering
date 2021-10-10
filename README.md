# Fair_Clustering
Fair Clustering via Equitable Group Representations
The code here is an implementation of the paper [Fair Clustering via Equitable Group Representations](https://arxiv.org/pdf/2006.11009.pdf)
In the paper, the algorithms were explained to solve the problem but the code was not shared. I have implemented 1 of the algorithms (**LS-Fair**) and uploaded it here.

## Some points to note:

1. This code works on bank dataset (Also provided in repository).
2. This code implements LS - Fair algorithm explained in the paper.
3. LS fair is a modified K-median algorithm which uses a new cost function which ensures equal representations of all groups.
4. In this dataset the two groups are - **Single** and **Married**

## Code Explanation

The code can be divided into 4 parts:
1. Fist we take input and modify it to be used (dropping unnecessary columns and mormalising data).
2. Next we define newly proposed cost function.
3. We use a K-Median type of algorithm to get Final Clusters.
4. The final resulty is shown via a plot.

## How to run

1. Clone the repository.
2. Change path to bank-original.csv in Line 27 of Fair_Clustering.py.
3. Run Fair_Clustering.py.

### by:
*Daksh Sharma*
*Final Year Undergraduate*
*B.Tech Computer Science and Engineering*
*IIT Ropar*
