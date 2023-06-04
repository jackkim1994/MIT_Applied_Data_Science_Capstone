# MIT Professional Education Applied Data Science Capstone Project
For reference, [link for my MIT Profession Education Certificate](https://www.credential.net/c5728bdb-3927-4881-b2d7-12a8d7f34d54)

## Purpose of the Capstone Project
The hypothetical mortgage loan company had been experiencing a signficant overhead cost and time because of the incessant manual process to approve each aplicant. This process was highly inefficient and was prone to a human error.

My task was analyzing the Home Equity Dataset (HMEQ) with baseline and loan performance information for 5,960 recent home equity loans.
The purpose was to construct a classification machine-learning model that can predict the deliqnuency of each applicant and automatically aprpove the application.

## Business Impact
Not only this automation will significantly reduce a overhead cost and time of approving each applicant, but also we could efficiently reduce the rate of erroneously approving high-risk applicants.

## Modeling
Before going further, below list is the important terminology when I utilized Confusion Matrix.

- `Accuracy`: Overall performance
- `Precision`: How accurate the positive predictions
- `Recall`: Coverage of actual positive sample
- `Specificity`: Coverage of actual negative sample
- `F1 Score`: 


After trying different models, I decided to go with `Fine-Tuned Random Forest` model because it showed the highest `Recall` rate at around 73% with `Accuracy` rate at around 87%.

While it is true that having `Precision` is an important metric for approving low-risk applicants, I prioritize on the `Recall` rate because we wanted to minimize the false-approval rate of applicants who have a high-risk of defaulting. 

Potentially, it will cost significantly more for the company to pay expenses from defaulted users rather than missing low-risk applicants.

## Conclusion
I recommended the following below:
- Ensure that applicants provide their net incomes and debts. Otherwise, automatically decline their applications.
- If Debt-to-Income Ratio is greater than 44%, decline the loan.
- If the applicant does not provide either delinquent credit lines or age of credit lines (month), decline the loan approval.
- Ensure a collaboration between underwriters and the automation model is established.

It was an intriguing experience to indirectly analyze the home loan data and understand its business and the outlying problem that loan companies can encounter in real-life.

After working on the Capstone Project, I learned that the machine-learning model is not perfect and sometimes will require a human intervention. In this case, an underwriter would need to step-in for a sanity check.

"Trust and Verify," my mentor always emphasized.
