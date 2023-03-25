
### Steps

0. Find the dataset
1. Determine ranking of criteria and weights with SRF method
2. Adjust threshold values
3. Apply
	1. Promethee I
	2. Promethee II
	3. Electre TriB
		1. Pessimistic
		2. Optimistic
4. Present the results
	1. Evaluate against own preference
	2. Change model parameters if inconsistency found
	3. Compare results between methods

## Requirements

- 12-50 alternatives
- 4-9 criteria
- >=4 decision classes ( boundary profiles )
- >=4 pairwise comparisons
- one method should perform at least 2 iterations of problem solving


## Report

### Dataset

**Q**: What is the domain of the problem about?  
**A:** Apartments for rent in Poznań

**Q**: What is the source of the data?  
**A:** Otodom

**Q**: What is the point of view of the decision maker? 
**A:** Student looking for an apartment close to Politechnika and gyms

**Q**: What is the number of alternatives considered? Were there more of them in the original data set?  
**A:** 14

**Q**: Describe one of the alternatives considered (give its name, evaluations, specify preferences for this  
alternative)  
**A:** 
name: "2 niezależne pokoje. Balkon. Nowy blok. Blisko PST"
price: 2350
area: 40m^2
aesthetics: 7
transit: 40
gyms nearby: 7

**Q**: What is the number of criteria considered? Were there more of them in the original data set?  
**A:** 5

**Q**: What is the origin of the various criteria? (catalog parameter / created by the decision maker - how?)  
**A:**
price : given by the landlord
area : given by the landlord
aesthetics : self-evaluated by decision makers on scale 0-10
transit : distance between apartment and politechnika in minutes by public transit, provided by google maps
gyms nearby: number of gyms in neighborhood, distance < 2km, google maps

**Q**: What are the domains of the individual criteria (discrete / continuous)? Note: in the case of continuous 
domains, specify the range of the criterion’s variability, in the case of others: list the values. What is  
the nature (gain / cost) of the individual criteria?  
**A:** 

**Q**:Are all criteria of equal importance (should they have the same ”weights”)? If not, can the relative  
importance of the criteria under consideration be expressed in terms of weights? In this case, estimate  
the weights of each criterion on a scale of 1 to 10. Are there any criteria among the criteria that are  
completely or almost invalid / irrelevant?  
**A:**

**Q**: Are there dominated alternatives among the considered data set? If so, present all of them (dominating  
and dominated alternative), giving their names and values on the individual criteria. 
**A:**

**Q**: What should the theoretically best alternative look like in your opinion? Is it a small advantage on  
many criteria, or rather a strong advantage on few (but key) criteria? Which?  
**A:**

**Q**: Which of the considered alternatives (provide name and values on individual criteria) seems to be the  
best / definitely better than the others? Is it determined by one reason (e.g. definitely the lowest  
price) or rather the overall value of the criteria? Does this alternative still have any weaknesses? 
**A:**

**Q**: Which of the considered alternatives (provide name and values on individual criteria) seems to be the  
worst / definitely worse than the others? Is it determined by one reason (e.g. definitely the highest  
price), or rather the overall value of the criteria? Does this alternative still have any strengths?
**A:**



### PROMETHEE I and PROMETHEE II

1. Write the preferential information you provided at the input of the method.  
2. Enter the final result obtained with the method. Usually, the first result is not the final one, you can  slightly adjust the parameter values to your preferences.  
3. Compare the complete and partial ranking.  
4. Comment on the compliance of the results with your expectations and preferences. Refer, among  others, to to the results for the alternatives that you indicated as the best and worst during the data  analysis. What operations were required to obtain the final result (e.g. changing the ranking of criteria,  adding blank cards, changing the value of threshold)?

1. ()
2. (Rankingi wyprintowane)
3. ()
4. najlepsze/najgorsze

### ELECTRE TRI-B  
1. Write the preferential information you provided at the input of the method.  
2. Enter the final result obtained with the method. Usually, the first result is not the final one, you can  
slightly adjust the parameter values to your preferences.  
3. Comment on the compliance of the results with your expectations and preferences. Refer, among  others, to to the results for the alternatives that you indicated as the best and worst during the data  analysis. What operations were required to obtain the final result (e.g. changing the ranking of criteria,  adding blank cards, changing the value of threshold)?  
4. Compare the optimistic and pessimistic class assignments.  
5. Comment on the compliance of the results with your expectations and preferences. Refer, among  others, to to the results for the alternatives that you indicated as the best and worst during the data  analysis. What operations were required to obtain the final result (e.g. changing the ranking of criteria,  adding blank cards, changing the value of threshold, boundaries or the λ parameter)?

1. ()
2. (ranking i assignment do klas)
3. ()
4. assignment optimistic vs assignment pessimistic podświetlone na czerwono różnica
5. ()