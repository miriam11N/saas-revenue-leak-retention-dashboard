\# SaaS Revenue Leak \& Customer Churn Command Center



\## Goal

Analyze why customers churn and where recurring revenue is being lost in a fictional B2B SaaS company.



\## Audience

CEO, Revenue Ops, Customer Success Manager



\## Main KPIs

\- MRR

\- Churn Rate

\- Net Revenue Retention

\- Expansion Revenue

\- At-Risk ARR



\## Dataset Tables



\### 1) customers

\- customer\_id

\- company\_name

\- industry

\- company\_size

\- region

\- acquisition\_channel

\- signup\_date



\### 2) subscriptions

\- subscription\_id

\- customer\_id

\- plan\_name

\- billing\_cycle

\- monthly\_price

\- seats

\- start\_date

\- renewal\_date

\- status



\### 3) usage\_monthly

\- customer\_id

\- month

\- active\_users

\- sessions

\- feature\_adoption\_score

\- api\_calls



\### 4) support\_tickets

\- ticket\_id

\- customer\_id

\- month

\- severity

\- resolution\_hours

\- csat\_score



\### 5) invoices

\- invoice\_id

\- customer\_id

\- invoice\_month

\- billed\_amount

\- discount\_amount

\- paid\_amount

\- payment\_status



\### 6) churn\_events

\- customer\_id

\- churn\_date

\- churn\_reason

\- voluntary\_flag

\- save\_offer\_flag

