# Vocab_Compare
Vocab comparison of Macbeth &amp; Romeo and Juliet

Using Hadoop's map-reduce framework and Java

  In this assignment, I try to answer the professor's questions which states "How does the vocabulary of Macbeth compare 
  with that of Romeo and Juliet?"

  It is important because the professor wants to understand the vocabulary and words usage in both the plays by Shakespeare. To know how
rich is the vocabulary of Macbeth and Romeo & Juliet. 

I have written a java program which will be run in the Hadoop cluster to answer the question. This java source code contains 3 main 
classes and they are mapper class, reducer class and stemmer class.I will run the code against each play (Macbeth and Romeo & Juliet) 
and then get the list of all the words in each play. I will fetch the top 50 words (with highest recurrence) for each play and put it 
in an excel file. I will then open this excel file in Tableau to generate the graph. I will then derive a comparison between both 
the plays and answer which play has a better vocabulary. Here Macbeth’s vocabulary is considered as a standard and is compared with 
Rome & Juliet.

I have created a graph using Tableau to visually represent how the vocabularies of each play compare with each other. It can be found 
below. The graph contains the list of words and are sorted in descending order from highest recurring word to the least recurring word. This also represents the rank of each word starting from 1 to 50. The word with
rank 1 in the play Romeo & Juliet appears 161 times whereas in Macbeth it appears only 82 times. The average number of occurrence 
for each word in the top 50 words is calculated by adding all the occurrences of top 50 words divided by 50. For Macbeth it was 
1437/50 and for Romeo & Juliet it was 2487/50. This came out to be 28.74 for Macbeth and 49.74 for Romeo & Juliet.

Conclusion: Since the average occurrence of top 50 words for Romeo & Juliet is way more than that of Macbeth, this concludes that 
the vocabulary of Macbeth is better than Romeo & Juliet.

![Correlation-Value](https://github.com/PrasannaSajjan/Vocab_Compare/blob/master/images/Results.JPG)
