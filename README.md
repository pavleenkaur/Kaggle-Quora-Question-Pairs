# Kaggle Quora Questions Pairs
### Problem Statement
Since it is expected of many people to ask similarly worded questions, multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. <br>
In this competition, we were challenged to tackle this problem by applying advanced techniques to classify whether question pairs are duplicates or not. 

### Data
The data for the same can be found <a href ='https://www.kaggle.com/c/quora-question-pairs/data'>here</a>

### Approach
Here I have experimented with the muliple similarity measures such as the following and compared their individual performances : 
<ul>
<li>Cosine Similarity</li>
<li>Jacard Similarity</li>
<li>Multiple fuzzy ratios :</li>
<ul>
<li>Fuzzy QRatio</li>
<li>Fuzzy WRatio</li>
<li>Fuzzy Partial Ratio</li>
<li>Fuzzy Token Set Ratio</li>
</ul>
</ul>

Some other features that I have used are :
<ol>
<li>Number of Shared words</li>
<li>Total Number of words</li>
<li>Length of each question</li>
</ol>
