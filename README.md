# The Expanded Equity Corpus

The Equity Evaluation Corpus (https://www.svkir.com/resources.html#EEC) was developed by 
Svetlana Kiritchenko (svetlana.kiritchenko@nrc-cnrc.gc.ca) and Saif M. Mohammad (saif.mohammad@nrc-cnrc.gc.ca) in order to test for gender and racial bias in NLP algorithms. The corpus consists of 11 template sentences that are populated with names that are typically associated with a particular race and gender, in addition to varying emotional words (sadness, anger, etc.). The resulting 8,640 English sentences contain common African American female and male first names and common European American female or male first names. In addition, the corpus includes the gendered pronouns she/her and he/him. 

When auditing an NLP system for potential bias, one must be cognizant of the context in which the algorithm is being used, and to the extent possible probe the full intersectional nature of personal identity. The code in this project allows one to extend the EEC by adding new name:race/ethnicity combinations, as well as gender-neutral pronouns. We do not provide the corpus itself, just the means to extend it. 

