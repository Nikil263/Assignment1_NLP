# Assignment1_NLP
Auto-spell Correction using Minimum Edit Distance

Done by 

Nikil Rajasekaran Sargunar Bhoopathy and Swarnamukhi Chintalapudi

In this Assignment, the Minimum Edit Distance for the misspelled words in **Brikbeck** corpus is calculated for every word in the **Wordnet** corpus. The aim of this assignment to find the correct spelling of the misspelled word and the success at k (s@k) to measure the success of result from the top-k similar result (minimum edit distance) from the MED algorithm. We find the success at k for k = {1, 5, 10}. 

## Setup
To install all the necessary libraries required to run this project, Run the following command.

```pip install -r requirements.txt```

## Structure
The essential functions are located in the **utils** folder and the **assignment1.ipynb** notebook uses those functions to generate the result.

## Parallelization
Comparing the misspelled words with all the words in the dictionary takes a lot of Computational time. So, **multiprocessing** is used to achieve parallelization to reduce the Computational time. 
