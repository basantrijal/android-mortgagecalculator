# Mortgage Calculator Android App Assignment

This project covers question from the text book "Android HOW TO PROGRAM SECOND EDITION" page number 95 - Q 3.6.

Create a mortgage calculator app that allows the user to enter a purchase price, down payment amount and an interest rate. Based on these values, the app should calculate the loan amount (purchase price minus down payment) and display the monthly payment and total payment. Allow the user to select a custom loan duration in years (<= 30 years) by using a SeekBar.
The following formula is used to calculate the fixed monthly payment (P) required to fully amortize a loan of L dollars over a term of n months at a monthly interest rate of c. If the quoted rate is 6%, for example, c is .06/12 or .005. 

P = L[c(1 + c)^n]/[(1 + c)^n - 1]

Or you can use the Loan.java class to calculate the monthly and total payment.

