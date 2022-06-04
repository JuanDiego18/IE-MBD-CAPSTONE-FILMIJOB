# IE-MBD-CAPSTONE-FILMIJOB
Final Project for the Master in Big Data and Business Analytics from IE Business School / Interview questions scoring for Filmijob


Approach for solving the problem:

1. Classify the keywords according to the job roles.

    1.1 The "manual" way: Manually check for the ocurrence of keywords on the job description.

        1.1.1 Using joins to look for words in the job description
   
        1.1.2 Information Retrieval Algorithm?

    1.2 Make a model or apply some kind of method around the keywords (embedding?) to broad the scope of the classification (For instance, if the word R appears
on the job description, and we have python as a keyword, as both words are similar or relate to each other, we count an appearance on python) 

2. Score the question accordingly to the number of appearances of the keywords (A question with 5 keywords appearances will have a better score versus one that
has 2 keywords appearances). In this step we also use the embbeding aproach to score the question (If tableau appears on the question, PowerBI keyword should 
give the question more weight.

    2.1 Scoring method 1: Page Rank Alrithm????
 
    2.2 Scoring method 2: Manual scoring method
 
3. Adding specific questions according to the keywords related to the job??????

