# Product-Price-Suggestion
The problem is quite straightforward to understand where, given the details of the product the output, the price for the product should be. When we pose this as a machine learning problem we call this out as a Regression Problem as as the output is real numbers(price).

OBJECTIVE
We are using Mercari Dataset which is Japan’s biggest community – powered shopping app. We would build an algorithm that automatically suggests the right product prices. This will help both the seller and buyers with their prices, hopefully, yield more transactions. User descriptions of the products, including details like product category name, brand name, and item condition. It contains about 2 million rows when combining both the train and test sets.
A.	Define the objective in business terms: The objective is to develop the right pricing algorithm we can use as a pricing suggestion to the users.
B.	How will your solution be used? Allowing the users to see a suggested price before purchasing or selling will hopefully allow more transactions within Mercari’s business.
C.	How should you frame this problem? This problem can be solved using a supervised learning approach.
D.	How should performance be measured? The evaluation metric for this regression problem should be RMSE (Root Mean Squared Error), but here it’s evaluated on RMSLE (Root Mean Squared Logistic Error).

