# Collection_Anlysis_PowerBi
## **Introduction:** 
We have a dataset Operation Collection Performance of a Bank X in 2020 and 2021. One of their main core activities is collection debt via several smaller companies (partners). 

## **Dataset structure:** 

| **Field**     | **Meaning**   | **Example**   | 
| ------------- | ------------- | ------------- | 
| Year  | Year that the data is reported  | 2020, 2021 |
| Month  | Month that the data is reported  | 1, 2, 3, 4, 5 .....|
| Os_company  | Companies that collect debt for Bank X  | GLX, DK, HMK, BFC.... |
| Range_DPD  | Debt group by day | 0-180, 360-720, 180-360, Deadloan....|
| Product_final  | Kind of debt  | Credit card, Securred Loan, ...|
| Payment_for_fee  | The amount of money that each companies collected at given month|
| PR_amount  | Principal Payment - The amount of money that you originally aggreed to pay back (remember that Interest is the cost for borrowing this Principal Payment and it won't be included in this dataset |
| Balance  | The total amount of money that need to be collected |

Some definition of financial terms which help you deeply understand the meaning of insights:
 - Overdraft: an financial service that allow clients to withdraw more money from their checking bank account than what they really have in the account. Ex: if you have $100 in your bank account and make a purchase of $150, the bank may allow the transaction to go through, at the same time the bank create an overdraft of $50 and will charge interest on $50 until you pay it off.
 - Securred Loan: a loan that is given for clients who put their assests as a collateral for a loan.
 - Unsecurred Loan: the opposite of Securred Loan.
 - Deadloan: a loan that is written off since the borrower is unable to pay.

## **Task question:** 
Stakeholder of the bank want to know the effectiveness of debt collection of their partners. Base on the result stakeholder launch an efficent strategy for next fiscal quarter.

## **Solution:**
Please first read file ***"Apply Design Thinking into Problem Solving Bank X case"*** to see how this method tackle the task question related to Bank X case. After that you can open file PowerBi Dashboard  ***"Dashboard Collection Analysis ver 1"*** or ***"Dashboard Collection Analysis ver 2"***.

## **Note:** 
 - The difference between 02 version is how the data is interpreted (not about the design) but both of them generate the same insight which will be present below.
 
## **Insight about the effectiveness of debt collection:**

"Overview:
 - 44% of debt is over 1080 days ( >3 years); 27% of debt is from 720 to 1080 days (2-3 years) and the rest is all Deadloans.
 - Creadit card product has the highest rate of payment (0.17%) and the following is Overdraft product (0.10%).
 - Secured loan product has the lowest rate of payment (0.02%) and it's ranked the third-highest outstanding balance, valued at 41 billion dollars. NDC company is the most successful collector related to this kind of product, their debt recovery rate is 0.03%. In 12/2020, the bank witness the highest debt recovery rate for this product (0.06%). In 10/2020, NDC company collect the most amount of payment which is over 950 million dollars. In 12/2020, FBI company collect the most amount of payment for the product which is over 1.1 billion dollars.
 - Unsecurred loan product has the highest amount of debt, which is account for nearly 50% of total debt, debt recovery average rate for this product is 0.07%. GLX, HMK and ASA are companies that well perform in collection payment for this product.

Detail:
"TOP 1: NDC company
 - Their balance is highest among others which is around 45 billion dollars. 
 - Debt recovery average rate: 0.09%. However, from 10/2020 NDC improved their rate to 0,15%, increased 0.06% compare to 9/2020. As the result, from 3/2021 to 5/2021, NDC ranked first in the total value of collection, nearly 5.5 billion dollars (in 3/2021).
 - NDC collect effectively with products: Credit card (debt recovery rate: 0.26%) and Others (0.32%)
 - NDC has ability for collecting bad debts. It continuously led in this field, for example, in 03/2021 it collected about 370 million dollars and in 04/2021 is over 640 million dollars."														


"TOP 2: ASA company
 - Debt recovery average rate: 0.11%
 - Their rate is unstable, in 2021 their rate fluctuated in the corresponding period last year: 
    + 1 and 2/2021: debt recovery rate lower than the rate of same period last year, in detail, 1/2020 = 0.2%, 1/2021 = 0.14%; 2/2020 = 0.28%, 2/2021 = 0.06%
    + 3, 4 and 5/2021: debt recovery rate is improved which increased significant, in detail, 3/2020 = 0.15%, 3/2021 = 0.17%; 4/2020 = 0.08, 4/2021 = 0.12%; 5/2020 = 0.11%, 5/2021 = 0.06%
 - ASA collect effectively with Overdraft product, their debt recovery rate is 0.26%													


"TOP 3: GLX company
 - Debt recovery average rate: 0.11%. Their rate dropped dramatic in 2021
 - Their adventage is Overdraft và HHB products.
 
 " Others:
 - Debt recovery rates 2021 of GLX, HNA, DK and AMG have an positive trend compare to 2021.
 - Debt recovery rate of FBI is quite low (0.03%), its adventage is HHB product.
				
## **Recomendation for Bank X based on generated insights:**

- Launch ranking strategy: give reward for those companies that have outstanding performance.

- Allocation debt portfolio according to their strongest point:
 
   + NDC: Other, Credit Card, Secured Loan
 
   + ASA: Overdraft, Unsecured Loan
 
   + GLX: Overdraft, HHB, Unsecured Loan
 
   + FBI: HHB, Secured Loan
												



***Please make proper credit if you want to use all my content (except the dataset)***



















