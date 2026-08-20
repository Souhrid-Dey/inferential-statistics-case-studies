# Problem Statement

## Questions

### Problem 1
A physiotherapist with a male football team is interested in studying the relationship between foot injuries and the positions at which the players play from the data collected.

| |Striker|Forward|Attacking Midfielder|Winger|Total|
|:---:|:---:|:---:|:---:|:---:|:---:|
|Players Injured|45|56|24|20|145|
|Players Not Injured|32|38|11|9|90|
|Total|77|94|35|29|235|

Based on the above data, answer the following questions.  
1.1 What is the probability that a randomly chosen player would suffer an injury?  
1.2 What is the probability that a player is a forward or a winger?  
1.3 What is the probability that a randomly chosen player plays in a striker position and has a foot injury?  
1.4 What is the probability that a randomly chosen injured player is a striker?  

### Problem 2
The breaking strength of gunny bags used for packaging cement is normally distributed with a mean of 5 kg per sq. centimeter and a standard deviation of 1.5 kg per sq. centimeter. The quality team of the cement company wants to know the following about the packaging material to better understand wastage or pilferage within the supply chain; Answer the questions below based on the given information; (Provide an appropriate visual representation of your answers, without which marks will be deducted)  
2.1 What proportion of the gunny bags have a breaking strength of less than 3.17 kg per sq cm?  
2.2 What proportion of the gunny bags have a breaking strength of at least 3.6 kg per sq cm.?  
2.3 What proportion of the gunny bags have a breaking strength between 5 and 5.5 kg per sq cm.?  
2.4 What proportion of the gunny bags have a breaking strength NOT between 3 and 7.5 kg per sq cm.?  

### Problem 3
Zingaro stone printing is a company that specializes in printing images or patterns on polished or unpolished stones. However, for the optimum level of printing of the image, the stone surface has to have a Brinell's hardness index of at least 150. Recently, Zingaro has received a batch of polished and unpolished stones from its clients. Use the data provided to answer the following (assuming a 5% significance level);  
3.1 Zingaro has reason to believe that the unpolished stones may not be suitable for printing. Do you think Zingaro is justified in thinking so?  
3.2 Is the mean hardness of the polished and unpolished stones the same?  

### Problem 4
Dental implant data: The hardness of metal implants in dental cavities depends on multiple factors, such as the method of implant, the temperature at which the metal is treated, the alloy used as well as the dentists who may favor one method above another and may work better in his/her favorite method. The response is the variable of interest.  
4.1 How does the hardness of implants vary depending on dentists?  
4.2 How does the hardness of implants vary depending on methods?  
4.3 What is the interaction effect between the dentist and method on the hardness of dental implants for each type of alloy?  
4.4 How does the hardness of implants vary depending on dentists and methods together?  
 

## FAQ 
1. In the Inferential Statistics project in Problem 3, we need to provide a visual representation but there is no data set provided for the same. Then, how to show the plot
We can plot by generating n random numbers from the Standard Normal Distribution, and sorting the generated random numbers.

2. Question 1 and 2 don't need the use of Jupyter Notebook as they are mathematical calculations. Is it OK if Jupiter notebook is not used for these questions?
Yes, we can do that without Jupyter Notebook. But please mention the formula by which you have calculated the answer.

3. In the Inferential Statistics project in Problem 2, we need to provide a visual representation but there is no data set provided for the same. Then how to show the plot?
We can plot by generating n random numbers from the Standard Normal Distribution and sorting the generated random numbers.

4. How to attempt Problem 4?
To attempt Problem 4, learners need to subset the data based on alloy 1 & alloy 2 and then attempt Problem 4. Request you to do the needful and attempt Problem 4. Excel output will not be accepted as the solution in Problem 4

5. In the Inferential Statistics module Project Problem 4, what does the column response mean?
Response is the variable of interest

## Rubric

### Criteria
1.1 What is the probability that a randomly chosen player would suffer an injury?
* Comments
Correctly identified total injured and total players. Probability calculation is accurate and clearly presented.
* Points
1/1

### Criteria
1.2 What is the probability that a player is a forward or a winger?
* Comments
Forward and winger counts are correctly summed. Probability is computed with correct denominator.
* Points
1/1

### Criteria
1.3 What is the probability that a randomly chosen player plays in a striker position and has a foot injury?
* Comments
Joint probability is well-identified using correct numerator and total. Clear understanding of simultaneous conditions.
* Points
2/2

### Criteria
1.4 What is the probability that a randomly chosen injured player is a striker?
* Comments
Conditional probability is correctly applied. Student used the right subset (injured players) as the base.
* Points
2/2

### Criteria
2.1 What proportion of the gunny bags have a breaking strength less than 3.17 kg per sq cm?
* Comments
Used cumulative distribution function appropriately. Value and interpretation are accurate.
* Points
1/1

### Criteria
2.2 What proportion of the gunny bags have a breaking strength at least 3.6 kg per sq cm.?
* Comments
Complement rule applied correctly for “at least” condition. Output is precise and well-explained.
* Points
1/1

### Criteria
2.3 What proportion of the gunny bags have a breaking strength between 5 and 5.5 kg per sq cm.?
* Comments
Difference of cumulative probabilities used correctly. Interval interpretation is accurate.
* Points
2/2

### Criteria
2.4 What proportion of the gunny bags have a breaking strength NOT between 3 and 7.5 kg per sq cm.?
* Comments
Complement of central probability range is correctly calculated. Both tails are considered properly.
* Points
2/2

### Criteria
3.1 Zingaro has reason to believe that the unpolished stones may not be suitable for printing. Do you think Zingaro is justified in thinking so?
'- State the null and alternate hypotheses
- Conduct the hypothesis test and compute the p-value
- Write down conclusions from the test results
Note: Consider the level of significance as 5%."
* Comments
Null and alternate hypotheses are clearly stated. P-value interpretation supports a justified conclusion.
* Points
4/4

### Criteria
3.2 Is the mean hardness of the polished and unpolished stones the same?
- State the null and alternate hypotheses.
- Conduct the hypothesis test.
- Write down conclusions from the test results.
Note: Consider the level of significance as 5%.
* Comments
Two-tailed test is correctly identified. Student interprets test statistic and p-value appropriately.
* Points
4/4

### Criteria
4.1 How does the hardness of implants vary depending on dentists?
"- State the null and alternate hypotheses
- Check the assumptions of the hypothesis test.
- Conduct the hypothesis test and compute the p-value
- Write down conclusions from the test results
- In case the implant hardness differs, identify for which pairs it differs
Note:
1. Both types of alloys cannot be considered together. You must conduct the analysis separately for the two types of alloys.
2. Even if the assumptions of the test fail, kindly proceed with the test."
* Comments
Separate ANOVA for each alloy is correctly done. Assumptions and conclusions are clearly addressed.
* Points
10/10

### Criteria
4.2 How does the hardness of implants vary depending on methods?
"- State the null and alternate hypotheses
- Check the assumptions of the hypothesis test.
- Conduct the hypothesis test and compute the p-value
- Write down conclusions from the test results
- In case the implant hardness differs, identify for which pairs it differs
Note:
1. Both types of alloys cannot be considered together. You must conduct the analysis separately for the two types of alloys.
2. Even if the assumptions of the test fail, kindly proceed with the test."
* Comments
Method-wise variation is tested separately for each alloy. Post hoc analysis is included where needed.
* Points
10/10

### Criteria
4.3 What is the interaction effect between the dentist and method on the hardness of dental implants for each type of alloy?
"- Create Interaction Plot
- Inferences from the plot
Note: Both types of alloys cannot be considered together. You must conduct the analysis separately for the two types of alloys."
* Comments
Interaction plots are created and interpreted well. Student identifies significant interaction patterns.
* Points
4/4

### Criteria
4.4 How does the hardness of implants vary depending on dentists and methods together?
"- State the null and alternate hypotheses
- Check the assumptions of the hypothesis test.
- Conduct the hypothesis test and compute the p-value
- Write down conclusions from the test results
- Identify which dentists and methods combinations are different, and which interaction levels are different.
Note:
1. Both types of alloys cannot be considered together. You must conduct the analysis separately for the two types of alloys.
2. Even if the assumptions of the test fail, kindly proceed with the test."
* Comments
Two-way ANOVA is conducted with clear hypotheses. Interaction effects and combinations are well-analyzed.
* Points
10/10

### Criteria
Quality of Business Report
* Comments
Report is well-structured and logically organized. Visuals are clear, and code is excluded as required.
* Points
6/6