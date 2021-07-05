# polypharmacyofdrugs-miniproject-DA2021-31120011-31120037
This project was made as a part of our academic project. Under this project we have dealt with the problem of polypharmacy of drugs, the solution to which we have provided by building a drug recommender system.
## Abstract
Polypharmacy or the use of multiple medicines has become quite common especially in the older generation. Individuals suffering with multiple diseases are prescribed with multiple medicines to be consumed. Polypharmacy leads to drug drug interactions, drug toxicity, drug protein interactions which usually leads to increased side effects problems in the patients. In this project, we have proposed a drug- drug recommender which makes use of similarity scores between different drugs and thus recommends drug pairs with least interactions. Through this project we have dealt with the problem of drug-drug interactions by creating a recommendation system that assess drug-drug interactions thereby reducing the side effects for the same.
## UML
![pasted image 0](https://user-images.githubusercontent.com/68891126/124430477-d85c0000-dd8c-11eb-988f-34cfd533750e.png)
## Algorithm
 -  Step 1: We take input in the form of a pair of drugs.
 -  Step 2: We then find out the similarity scores between the two drugs (using TWO SIDES dataset).
 -  Step 3: We then search for the five most similar drugs to each drug in the input pair using the RWR algorithm.
 -  Step 4: Finally, we try all the combinations of the resulting similar drugs and recommend the one with the lowest drug-drug interaction score.
