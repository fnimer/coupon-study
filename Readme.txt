Study: What types of customers accept more "Carry out & Take away" coupons?

GitHub link: https://github.com/fnimer/coupon-study/Coupons-final

Problem Statement: I studied the "Carry out & Take away" coupon. Understand if Customers who accepted a Carry out & Take away were ore or less likely to accept he ffer when they have Children, are of any specific marital status or at specific age. Discover the differences between individuals who accepted and rejected the offer.


Visualizations: I used mostly Seaborn and Matplotlib and Pandas. Given the type of data analyzed, I used mostly histplots and pairplots that uncover the insights of looking at customer who had children OR had kids as passengers in the car, and age groups and marital status. All plots are stored in the "images" folder, including: 8 plots with the analysis of the types of (histograms named 1a, 1b, 2a, 2b, 3a, 3b, 3c, 3d); additional 8 histograms with data analysis of variables; 2 pairplots. I also ran correlation heatmaps, contingency tables and covariance, and I also ran distributions in every column of the dataset, to understand the data better. I did not save them in images, though. The code is preserved in the notebook. I performed a few data cleansing activities, and transformation of some data types.

Data Analysis:

Customers who accepted a Carry out & Take away = 73.58% 
This is the coupon who received more acceptance from individuals.

Hypothesis
- I tested age (greater than 41 years-old) was a factor in accepting ore coupons.
- I also tested the 'alone factor', that is, if an individual who has a marital status = single, divorced or widowed were more likely to accept the offer.
- I also tested the 'kids factor' to understand if kids influence the decision to accept a coupon in two ways:
  a) if customers have kids on their own (column 'has_children') even when not in the car; or 
  b) if customers have kids in the car as passengers (column 'passenger == "Kid(s)') even if not their own kids.

Responses for individuals older than 41 years AND 'alone' (single, divorced or widowed):
  - Accepted the offer: 8.24%
  - Rejected the offer: 2.78% 

Responses for individuals who have children and are of any age and marital status:
  - Accepted the offer: 31.48%
  - Rejected the offer: 11.15% 

Responses for individuals who do not have children and are of any age and marital status:
  - Accepted the offer: 42.10%
  - Rejected the offer: 15.27% 

For Carry out & Take away coupons with Kids as Passengers:
  - Individuals Who Had Kids as Passengers: 6.31%
  - Individuals Who Had Kids AND accepted the offer: 4.39%
  - Individuals Who Had Kids AND rejected the offer: 1.93% 


Conclusions:

1- Older age and marital status does not seem to be factors that drive individuals to accept the coupon offer.

2- Individuals who DO NOT have children were more likely to accept the Carry out & Take away coupon offer. They were 42.10%, higher than the 31.48% from people without children. This seems to be counterintuitive, as normally we should expect that individuals with children would accept more "Carry out & Take away" coupons than the other types.

3- Individuals who had kids as passengers accepted less coupons than the other groups of individuals. However, when kids are in the car, they tend to accept more offers (4.39% from the total of 6.31%).


Next Steps and Recommendations

- many other factors needed to be tested, for instance, control for other subgroups of age groups; control for other types of marital status, and additional factors as temperature. I recommend add this to a better version of the study.

- the 'kids factor' may be a false assumption, as we do not know if the kids at the car (passengers) are aware of the offer and, therefore, could 'pressure' the customer to accept. 

- there are other extensions to this study, especially testing for the time spend until the customer decided to accept the offer. This may add additional insight to the type of coupon accepted and if each type leads - or not - to more flash decisions.

- I performed a few data cleansing activities, however there are more that could be done and would help evolve this study.