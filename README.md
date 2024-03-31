## Analyzing and exploring the Online Shoppers Purchasing Intention Dataset

The dataset consists of feature vectors belonging to 12,330 sessions.The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period. The dataset contains information about the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.
The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction.The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year. 

## Goal

We are trying to understand if a user is more likely to finalize a transaction close to a special day compared to the weekend and how the Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" columns are related to a user completing a transcation. 

## Result 

In the data set, May and February are the only months that have special days while other months do not have any data to show if there was a successful transaction during special days. Therefore this effects our result as there is not enough data in special days to shows the trends over a year of sessions.
It is important to note that while considering the month of May, which has the most documented special day values, we see that the average number of visits to a product related page increase slightly as we approach the special day.
The “Weekend vs. No. of Product Related pages visited” graph show us that the webpages generate more revenue on weekdays as compared to the weekends. Comparing this to the “Special Day vs. No. of Product Related pages visited” graph we see that more revenue is generated on a Weekend as opposed to a Special Day.
Thus, the data set shows that a user is most likely to shop a successful transaction during the weekend than special days.
From the “Product related Duration vs Bounce Rate” we see that the more time a user spends on a Product Related webpage the less likely they are to bounce from that page. We see from our data exploration that the six columns - “Administrative”, “Administrative Duration”, “Informational”, “Informational Duration”, “Product Related” and “Product Related Duration” - are not directly correlated to the user completing a successful transaction.
