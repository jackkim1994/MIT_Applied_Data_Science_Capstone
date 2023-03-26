# MIT Professional Education Applied Data Science Capstone Project
For reference, [link for my MIT Profession Education Certificate](https://www.credential.net/c5728bdb-3927-4881-b2d7-12a8d7f34d54)

## Purpose of the Capstone Project
The hypothetical mortgage loan company had been experiencing a signficant overhead cost and time because of the incessant manual process to approve each aplicant. This process was highly inefficient and was prone to a human error.

My task was analyzing the Home Equity Dataset (HMEQ) with baseline and loan performance information for 5,960 recent home equity loans.
Ultimately, I needed to construct a classification machine-learning model that will be able to predict the deliqnuency of each applicant and automatically aprpove the application.

## Business Impact
Not only this automation will significantly reduce a overhead cost and time of approving each applicant, but also we could efficiently reduce the rate of erroneously approving high-risk applicants.

## Modeling
After trying different models, I decided to go with `Fine-Tuned Random Forest` model because it showed the highest `Recall` rate at around 73%.

While it is true that having `Precision` is an important metric for approving low-risk applicants, I prioritize on the `Recall` rate because we do not to erroneously approve applicants that have a high-risk of defaulting. 

Potentially, it will cost significantly more for the company to clean up the mess from defaulted users than miss low-risk applicants.

## Conclusion
Ultimately, it will be up to the company to decide.

However, it was an intriguing experience to analyze the home loan data and concurrently understand the business and the reality it faced.

Lastly, I learned that the machine-learning model would not be perfect and would require a human intervention. In this case, an underwriter would need to step-in for a sanity check.

"Trust and Verify," my mentor always emphasized. 
