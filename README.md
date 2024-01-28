# Statistical-Techniques-for-Data-AnalysisCA1

## Introduction

The report presented here examines data collected from past marketing campaigns, specifically focusing on whether or not customers subscribed to a term deposit. The primary goal of this data collection by the bank was to gain insights on customer behaviour and evaluate the success of their marketing strategies.

The findings from the conducted analysis have been summarised, and the resulting conclusions drawn.
- The purpose of this report is to profile the key characteristics of the customer who is more inclined to subscribe to a term deposit based on our analysis.
  - Assuming we seek customers who are willing to invest long term without taking unnecessary risks.
- It have been conducted following the next steps:
  - Data overview
  - Comprehensive analysis of Features
  - The probability of a target customer successfully subscribing to a term deposit.

The data collected to perform this report is the result of questions that have been done to 4521 customers of a bank in order to profile them. It was as of interest their:
- age
- job
- marital: Marital status
- education: Education level achieved
  - Primary
  - Secondary
  - Tertiary
- bank_debt : Whether or not they have a debt in their bank account.
- avg_balance : Average yearly balance in their bank account.
- housing_loan : Whether or not they have a housing loan.
- personal_loan : Whether or not they have a personal loan.
- month: Month they were contacted last time.
- duration: Last contact duration.
- n_contacts_done : N umber of contacts performed during this campaign and for this client
- pre_n_contacts_done : N umber of contacts performed before this campaign and for this client
- results_prev_campains : outcome of the previous marketing campaign
  - failure
  - nonexistent
  - success
- campaign_results ::: Whether or not the client has subscribed to a term
- age_group : G roup s of customers based on their age
  - Young: P opulation from 19 to 34
  - Adul: Population from 35 to 59
  - Elderly : Population from 60 to 87.
- balance_clasification : Groups of customers based on their balance.
  - low: Population from -3.333 to 1.421€
  - standard: : Population from 1.422 to 4.000€.
  - high: Population from 4.001 to 71.188€

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture3.JPG)

## Data overview

At the beginning of the analysis, an overview of the data was carried out, where the following conclusions were drawn

1. Data description of numeric features gathered from customers

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture4.JPG)

- The mean age is 41.
- Mean balance in their bank account 1423€.

2. Data description of categorical features gathered from customers

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture5.JPG)

- Working in management
- Married
- With a secondary level of education.
- Without a bank debt.
- With a housing loan
- Without a personal loan
- Adult
- With a low average balance in their bank account.

3. Data collection

We may decide not to include information about the results of previous campaigns in further analysis because the number of customers from whom we have collected information is too small.
- From the 4521 customers contacted, we were unable to collect information from 3705 of them.

## Comprehensive Analysis of Features

Once it was discovered what the data is that we are working on, it was decided to carry out an analysis of the characteristics that we could consider relevant to draw an approach of what could be an interesting profile of customers that we could consider d eveloping further strategies to reach out.

## Campaign Success

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture6.JPG)

The previous campaign results we are working with are:

- 11.5% of customers who were contacted were successfully subscribed to a term deposit.
- 89.5% of customers who were contacted were unsuccessfully subscribed to a term deposit.

## Campaign Results by Group of Ages

To conduct a study of the success of previous campaigns by age group, we decided to group customers aged 19-34 as young, 35-59 as adults and 60-87 as older.

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture7.JPG)
![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture8.JPG)

In previous campaigns:
- 63.5% of customers contacted were adults.
- 32.5% of customers contacted were young.
- 4% of customers contacted were elderly

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture9.JPG)

We have discovered that even if most of customers contacted were adults, it is actually young customers who seems to **be proportionately more likely to subscribe to a term deposit.**

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture10.JPG)

Conducting a more thorough analysis of young and adult clients, it was observed that out of 1472 young customers contacted, 12% were successfully subscribed to a term deposit Which is proportionally a higher proportion of customers if we compare with adults where it was the 10% of them who did it.

However, adult customers are considered more suitable for term deposit offers, as young customers are perceived as vulnerable. This is why we consider this group of people to be best suited to better contact and persuasion strategies.

- It is worth noting that, due to company strategies, further analysis of elder customers was not conducted in this study, although they may be potential clients. However, it is outside the scope of this analysis to consider them.

## Campaign Results by Job

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture11.JPG)
![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture12.JPG)

In previous campaigns:
- 21.4 % of customers contacted were managers
- 20.9 % of customers contacted were

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture13.JPG)
![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture14.JPG)

A more detailed analysis of
customers working as managers and blue collar shows that 131 out of 969 managers contacted , or 13.5%, successfully subscribed to a term deposit . This is a proportionally higher percentage of customers compared to blue collar customers , where it was 7% Therefore, it is recommended to increase efforts to reach customers with management roles.

## Campaign Results by Average Balance in the Bank

In order to study how successful was the campaign by the average balance in the bank account, we have decided group ing customers by their average balance and where low is population from -3.333 to 1.421 €, standard from 1.422€ to 4.000 and high from 4.001 to 71.188€

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture15.JPG)

In previous campaigns:
- 74.2 % of customers contacted had a low average balance in their bank account.
- 16.1 % of customers contacted had a standard average balance in their bank account.
- 9.7 % of customers contacted had a high average balance in their bank account.

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture16.JPG)

Although it seems obvious that most customers have a low average balance, it may be recommended to make a better effort to reach people with a standard and high average balance in order to take a safer position.
- As it may be obvious that people with a high average balance in their bank account are a target for further campaigns, we may not consider them for further analysis.

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture17.JPG)

Conducting a more thorough analysis customers with a standard Balance in their Bank Account, it was observed that 118 out of 729, 16% were successfully subscribed to a term deposit.

## Summary Analysis

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture18.JPG)

- Customers contacted by age are a group of population following a Normal Distribution in the data.
- The Average balance of customers in their bank accounts are following a Normal Distribution in the data.
- Age and average balance of customers in their bank accounts are following a Normal Distribution in the data.
- The average age of customers reached during the campaign is 41 , with the majority of pupation analysed within +/ 10 years of this age.

The balance average of customers reached during the campaign is 1.422€, with the majority of pupation analysed within +/ 3.000€ of this amount.

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture19.JPG)

- People in management roles are more likely to subscribe to a term deposit followed by technicians.
  - 131 out of 969 managers contacted, or 13.5%, successfully subscribed to a term deposit.
- Adult customers are deemed more suitable for term deposit offers since young customers are perceived as precarious prospects, and the elderly may not be inclined to show interest for commercial strategic reasons.
  - 288 out of 2875 adult customers contacted, the 10 % were successfully subscribed to a term deposit.
- Although we could adopt a more conservative approach and target customers with a high average balance, we have decided to concentrate on clients with a regular balance who are more statistically inclined to apply for a term deposit.
  - 118 out of 729 customers with a standard average balance , 16% were successfully subscribed to a term deposit.

Based on the study delivered in previous steps we have defined our potential client more likely to subscribe a term deposit a customer with:
- A Management role
- Adult
- In possession of a Standard Average balance account

## Recommendations to help future campaigns succeed

- It may be recommended to make a better effort to reach people with a standard and high average balance in order to take a safer position.
- It is recommended to increase efforts to reach customers with management roles.
- We have discovered that even if most of customers contacted were adults, it is actually young customers who seems to be proportionately more likely to subscribe to a term deposit.

## Probability of managers successfully subscribing to a term deposit

![image](https://github.com/EduardoJMatosRomero/StatTechsCA1/blob/main/images/Capture20.JPG)

In order to study the probability of a manager successfully subscribing to a term deposit , we decided to perform a binomial distribution analysis.

To develop this analysis:

1. We have study which is the probability a manager successfully subscribed to a term deposit, studying their relative frequencies.

2. We have taken the total amount of managers we have in our dataset.

3. With those values:
  - Number of managers: 969
  - Probability of successfully 'management' customers subscribe to a term deposit : 14%
- We have studied
  - The total amount of managers we are expecting to successfully subscribe to a term deposit is 136.
  - The probability of exactly 136 managers successfully subscribe to a term deposit is 3.69 %
  - The probability of more than 136 managers successfully subscribe to a term deposit is 46.46 %.
