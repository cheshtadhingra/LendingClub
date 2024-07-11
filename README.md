# LendingClub

### Background Information
The Lending Club is a peer-to-peer lending network offering loans.It provides extensive loan data online, enabling investors to make informed investment decisions. This data, includes borrower demographics, credit history, loan specifics (e.g., purpose, requested amount, funded amount, interest rate, and loan grade).

### Project Aim
The primary goal of this project is to develop a model that predicts whether a Lending Club-approved loan will be fully paid or charged off. Such predictions are invaluable to investors for making informed investment choices. The model should be:
1. **Accurate**: Effectively predicting loan outcomes.
2. **Non-discriminatory**: Ensuring fairness concerning demographic features like race and home address.

Only completed loans are included in the model to ensure outcome certainty, excluding those still in progress or in default.

### Data
The data used for this project is sourced from the Lending Club's website (https://www.lendingclub.com/). Due to limited information on rejected loans (e.g., risk score, debt-to-income ratio, zip code, and employment length), they were excluded from the model.

Borrower FICO scores were not incorporated as access is restricted to approved investors. Nonetheless, the dataset includes various credit risk-related features, such as the number of delinquencies in the past two years, average current balance, and total credit revolving balance. Additionally, the Lending Club's loan grades, which factor in the FICO score and other variables, are included.

### Methodology and Results
Detailed methodologies for data exploration, cleaning, processing, modeling, and fairness adjustments are documented on the relevant dataset pages. A summary of results and future considerations can be found on the Discussions page.
