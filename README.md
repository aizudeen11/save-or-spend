# save-or-spend
if you have a loan with a bank. you might want to pay the bank more than your monthly installment, probably because you want to pay less interest or to settle the loan faster or improve credit score. however we have another option. instead use the extra money in monthly loan installments, you might want to use it to invest in investment account such as fixed deposit or EPF. 

but which option will you choose? to spend it and pay more in loan monthly installments or save it in investment account? 

this is the purpose of this program. it will calculate and compare your investment value (if you save it in investment account) and interest saving (if you pay more in monthly loan installments) 

# formula use
Equated Monthly Instalment

EMI/M = P x R x (1+R)^N / [(1+R)^N-1]

P: Principal loan amount 

N: Loan tenure in months 

R: Interest rate per month

from EMI, formula to get loan tenure

N = ln(M/(M-PR))/ln(1+R)

future value

A=P([(1+r/n)^nt]-1)/(r/n)

A : future value of the annuity (the investment account).

P : amount of each monthly deposit.

r : annual interest rate (as a decimal).

n : number of times interest is compounded per year 

t : number of years the money is invested.

# how to use
<p>call the class function **Calculation** and enter your data__< br / >
loan_interest: float - annual loan interest__< br / >
loan_amount: float  - loan principal__< br / >
ln_tenure: float - loan tenure__< br / >
fv_interest_rate: float - annual interest rate for investment account__< br / >
every_rm= 100 - default at RM100__ < br / >
until_rm=1000 - default at rm1000__< br / >
fv_n=12 - default at 12 month__< br / >
ln_n=12 - default at 12 month__< br / ><p/>
