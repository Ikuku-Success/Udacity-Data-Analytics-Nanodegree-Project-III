<h1 align="center"> ALX-Udacity Data Analytics Nanodegree Project-III </h1>
<p align="center"> 
  <img src="https://opportunitycrib.com/wp-content/uploads/2022/04/Alx-Virtual-Assistant-Programme-696x473.jpg" alt="Sample signal" width="70%" height="70%">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Introduction -->
<h2 id="introduction"> :pencil:Introduction</h2>
<p align="justify"> 
  The prosperLoanData contains 113937 entries spanning across 81 columns. There are three columns with boolean values, fifty columns with float values, eleven and seventeen columns with integer and string values respectively.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Data Sourcing -->
<h2 id="Data Sourcing"> :pencil:Data Sourcing</h2>
The dataset was assigned as my first Nanodegree project. After asking questions, I went ahead to explore the data and see what's really in for me. I noticed it has;

- The dataset contains 54 years of movies data, cutting across several genres
- It contains 21 columns and 10866 rows
- Twenty-one of which are strings. Then floats and integres are divided in the ratio 4 : 6

<!-- Data Cleaning & Transformation -->
<h2 id="Data Sourcing"> :pencil:Data Cleaning & Transformation</h2>

Our dataset was not really dirty, it only needed a little data cleanng to make it set for EDA.
<!-- Conclusion & Observation -->
<h2 id="Conclusion & Observation"> :pencil:Conclusion & Observation</h2>

- For the Original Loan Amount, high loan amounts were noticed around 5000, 10000 and 15000 dollars. A log transformation was done to the scale but a similar information was provided. Interestingly, it was revealed that the Borrower Interest Rate (%) shows a unimodal distribution with a very high peak around 0.4% interest rate. From the stated monthly income, it was revealed that the income is symmetric/unimodal in nature and majorly distributed around 5000 dollars. This indicates that there could be a relationship between the stated monthly income and the Loan amount. For the Loan term, about 77% of the loans provided were for 36 months. Histogram plotted for the Credit Score after computation informs that the borrowers have good credit score with highest peak around 700.
- An unusual distribution was obtained from the stated monthly income where the only populated frequency was in 0. A scale transformation was done to get a proper data visuals. Before that, a constant was added to the data before the log transformation since there is a zero value in the records. A new column Credit Score was created by averaging the Upper Credit Limit and Lower Credit Limit Score.
- There is a slight moderate negative correlation between original loan amount and rate which implies that higher loan amount could mean lower interest rate. Although fairly low, the correlation between Loan original amount and stated monthly income and credit score is positive.

- The correlation between borrower rate and stated monthly income is very low and negative. However, the credit score tend to have a negative and moderate relationship with borrower's interest rate.
- A moderate negative relationship exist between original loan amout and interest rate. In other words, higher loan could imply lower interest rate. A slightly positive relationship also exist between original amount and stated monthly income and credit score is positive. On the other hand, a low negative relatioship was discovered between borrower rate and stated monthly income which means that the stated monthly income might not affect the borrower's rate. However, the credit score tend to have a negatively fair relationship with borrower's interest rate.
- Although some positive realtionship exist between the categorical variables and Loan Original amount, they are generally low. The most obivious one is its relationship with Loan term. The loan amount tend to be higher with more loan term. It was also suggested that credit score has no relationship with verifiable income while a positive but very low relationship exist between credit score and loan term.
- There is a slight moderate negative correlation between original loan amount and rate which implies that higher loan amount could mean lower interest rate. Although fairly low, the correlation between Loan original amount and stated monthly income and credit score is positive.
- The correlation between borrower rate and stated monthly income is very low and negative. However, the credit score tend to have a negative and moderate relationship with borrower's interest rate.
- It is obvious here that despite the positive relationship between Loan amount and credit score, loan terms of 60 months were released to customers that have higher credit score and those with higher loan original amount. Although there isn't much of a difference considering the influence of the term categories on the relationship between interest rate and loan amount. However, it is obvious that lower term is associated with interest rate. 12 months term loans recieved the lowest interest rate while 60months loan terms get higher interest rate.
- It was also revealed in the loan term has a slight influence on the relationship between stated monthly income and loan amount recieved by the borrower. In addition to the relationship between loan recieved and stated monthly income, it was revealed that credit score influence the loan recieved. Customers with higher credit score and higher monthly income recieved higher loan amount.
