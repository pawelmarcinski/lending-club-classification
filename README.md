This is my Data Science Bootcamp at Future Collars final project
Pawel Marcinski
Lending Club
Lending Club is a peer-to-peer lending company that connects borrowers with investors for
via the online platform. Serves people who need personal loans in
from USD 1,000 to USD 40,000. Borrowers receive the full amount of the loan granted
minus the initial fee that is paid to the company. Investors buy secured notes
personal loans and pay Lending Club a service fee. The Lending Club company provides data about
all loans issued through its platform during the specified periods. On
For the purposes of this project, data on loans granted through Lending Club were used
over the years 2007 -2011. Each loan is accompanied by information about whether it was finally granted
paid off (Fully Paid or Charged off in the loan_status column).
Your task is to build a classification model that will be based on this data
predicted with certain accuracy whether a potential borrower would repay his debt under the title
the loan taken. The dataset is accompanied by a file with a description of all variables and the file "FICO
Score ranged.pdf”, which describes in detail the meaning of one of the columns.
Below are presented the individual stages of the analysis, the implementation of which is necessary to pass
of the project and their scoring:
1. Data Processing (70 points) - as an experienced Data Scientist you probably know
specific steps to follow at this stage, so we won't detail them here.
2. EDA, i.e. extensive data mining (100 points) Describe the conclusions drawn from each graph, your
support hypotheses with statistical tests such as the t-test or Chi-square. Additionally, reply to
the following questions:
A. How does the FICO score relate to the likelihood of a loan being repaid
borrower?
B. How does credit age relate to probability of default and whether
this risk is independent or related to the FICO score
C. How home mortgage status relates to probability
insolvency?
D. How does annual income relate to probability of default?
E. How employment history relates to probability of default
obligations?
F. How the size of the loan requested is related to the probability of default
obligations?
3. Feature Engineering - create 20 new variables (60 pts)
4. Modeling (150 points)
A. Perform data clustering (try several methods for this purpose, min. 3) and check if there are
some segments of borrowers, use appropriate methods to determine the optimal one
number of clusters (40 points)
B. Train 5 different models using a different algorithm for each and then compare them
action, the AUROC score is the model quality assessment metric. (50 points)
C. Check the operation of previously used methods on compressed data using PCA,
compare the results (AUROC score) with the models trained in the previous section. (20 points)
D. Build the final model whose AUROC score will be >= 80%, remember about the selection of important ones
variables, cross-validation and fine-tuning of model parameters, also think about balancing
classes. (40 points)
There are 380 points to be won for the whole thing. A minimum of 300 points is required to pass the project. Good luck!
