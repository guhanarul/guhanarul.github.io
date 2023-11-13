---
title: "TinyGoogle"
layout: post
---
# Abstract
<em>"The whole idea is to implement the process that google does to respond to a user query In the search engine but with less details involved"<em>

# Implemented ideas
1.Implemented an algorithm that behave like the google bots that surf the whole internet to index the webpages and cumulate them under some common index names. 

2.Instead of using natural language processing (NLP) to understand the user search query  words other than the stop words like (is, the, a, an) are considered to gather the final result and give it back to the user. 

3.Determining the search query which part it falls among the segments that are created by the bots during the segmentation process.

# Detailed Explanation

**Internet.txt**

The internet.txt file here is considered as the whole internet and various contents of different genere presents there to imitate it with internet but instead of webpages in internet her each sentences in the internet.txt is considered as a webpage with the corresponding title.

**Scrollbots**

The scroll bots are the set of programs that surf through the whole internet.txt file to segregate it as three index here(covid,chickenpox, dmk). 
These bots will surf through the internet. txt file and result us a final index of different possible tags.

**Segments**

The segments are the part of the program where it decides the category of user query to match up it with the segregated index. 
If the user-query is found to be not related or outliers then this part will tell the user to really give meaningful queries to get useful results. 

**Final Output**

In this part of the program,the top 4 results related to user query will be chosen by program. 
The gathered stop words will be then used to rank the results to the user's queries.
To avoid getting repeated results for the user queries here we used the random indexing  to access the contents in the "internet.txt" file, so that each time the program tries hard to find the contents that are closely related to the user's requested query. 

**Conclusion**

To measure the effectiveness of the program's implementation increase the contents of the "internet.txt" file similar to the structure it has and keep in mind that the sentence must talk either about "Covid", " Chickenpox", "Dmk" or the possible combinations of those three keys.
  
To discuss the whole thing just drop a mail(its down right) or connect with me in twitter! 
  
**What can be added?**

To improve it further LLM can be used to really understand the whole user's query and by increasing the capacity of the internet.txt file we could add interesting features but that's for the next time. 

**Bye..**

  
  
