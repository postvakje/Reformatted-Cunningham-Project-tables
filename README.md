# Reformatted Cunningham Project Tables
 The goal of this project is to reformat the data files from [The Cunningham Project](https://homes.cerias.purdue.edu/~ssw/cun/) into a more machine readable JSON format listing all the prime factors in a list.
 
 Currently the JSON files are created from data in the April 6, 2022 file at Sam Wagstaff's website (https://homes.cerias.purdue.edu/~ssw/cun/pmain422.txt)

 So far, the following files are available:

 [`pmain422_table2-.json`](Reformatted-Cunningham-Project-tables/blob/main/pmain422_table2-.json)
 Table 2-: factorization of $2^m-1$. Only values of $m$ where a full factorization of $2^m-1$ is known are included. Includes both odd and even values of $m$.

 [`pmain422_table2+.json`](Reformatted-Cunningham-Project-tables/blob/main/pmain422_table2%2B.json)
 Table 2+: factorization of $2^m+1$. Only values of $m$ where a full factorization of $2^m+1$ is known are included. Includes both odd and even values of $m$.

 [`pmain422_table2LM.json`](Reformatted-Cunningham-Project-tables/blob/main/pmain422_table2LM.json)
 Table 2LM: factorization of Aurifeuillean factors $L$, $M$ of $2^{4k+2}+1=L\times M$ where $L = 2^{2k+1}-2^{k+1}+1$ and $M = 2^{2k+1}+2^{k+1}+1$.
 Only values of $m = 4k+2$ where a full factorization of both $M$ and $L$ are known are included.
 
Since keys in JSON are required to be strings, the values of $m$ are stored as strings in the JSON files. 

**TODO**: 
    1. include values of $m$ for which there are composite factors that have not been factored yet.
    2. include other machine readable formats. 




