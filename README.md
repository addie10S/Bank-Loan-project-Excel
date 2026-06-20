### Bank Loan Report
I analyzed a Bank Loan Report dashboard (Excel). Here's what the numbers are telling us.

**Context: what is this dashboard about?**

This is a loan portfolio dashboard. It tracks loan applications, money given out (funded), money collected back, interest rates, and risk (DTI = Debt to Income).
Basically, it tells a bank: "Are we lending well? Are we getting our money back?"

**Findings: the key numbers**

Total loan applications: 38.6k
Total funded amount: $435.8M
Total amount received back: $473.1M
Average interest rate: 12.05%
Average DTI: 13.33%

**Loan health split:**
Good loans: 86.18% (33.2K applications, $370.2M funded, $435.8M received)
Bad loans: 13.82% (5.3K applications, $65.5M funded, $37.3M received)

**Status breakdown:**
Fully Paid: 32.1K loans → $351.4M funded → $411.6M received → 11.64% interest, 13.17% DTI
Charged Off: 5.3K loans → $65.5M funded → only $37.3M received → 13.68% interest, 14.00% DTI
Current: 1.1K loans → $18.9M funded → 15.10% interest, 14.72% DTI

**Other patterns:**
Applications grew every month, from 2.3k in Jan to 4.3k in Dec
Debt consolidation is the top reason for loans (18.2K applications)
Most borrowers prefer 36-month terms (28.2K) over 60-month (10.3K)
People with 10+ years of work experience apply the most (8.9K)
Most borrowers are on Rent (18,439) or Mortgage (17,198), very few own a house

**Impact: why this matters**

Charged off loans are only 13.82% in count, but look closer:
The bank gave $65.5M to these borrowers and got back just $37.3M.
That's a real loss of $28.2M.

**Also notice:** Charged Off and Current loans have higher interest rates (13.68% and 15.10%) and higher DTI than Fully Paid loans.
This means higher risk borrowers are being charged more interest, which is normal in lending, but it also means risk is not fully under control yet, since defaults are still happening.

**Recommendations**

1. Borrowers with DTI above 14% should get extra checks before approval
2. Debt consolidation loans are the highest in number, so build a separate risk model just for this category
3. Push more people towards 36-month terms, shorter terms means faster recovery and lower risk
4. Track Current loans closely, their DTI (14.72%) is even higher than Charged Off loans, this group needs early attention before they turn bad
