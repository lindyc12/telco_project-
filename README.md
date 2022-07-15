# telco_project-

Predicting customer churn is critical for telecommunication companies to be able to retain customers. 
Especially because it is more costly to acquire new customers than to keep existing ones.
My goal is to identify main drivers of churn as well as which customers are at risk of churn
and to make any recommendations for changes so that we can reduce the churn rate and increase customer retention.
i have explored and the data by using visualization and built models to predict how likely a customer will churn by analyzing certain features: demographic (gender, dependents), account (monthly charges, contract), and services information (phone services, internet services).

My first question is if monthly cost has anything to do with churn? 
do internet services have an effect on churn?
what kind of contract churn more?


To reproduce you will need:
An env.py file that contains the host, username and password for the mySQL database and go into the Telco-churn table. 
Store that env file in the same repository.
clone my repository along with the acquire.py and prepare_Telco.py.
make sure .gitignore is hiding your env.py file
The libraries i used are pandas, matplotlib, seaborn, numpy, sklearn, scipy.
you should be able to run survival_report.