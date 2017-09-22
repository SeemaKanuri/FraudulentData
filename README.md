# FraudulentData
 Build a model to detect financial crime at the transaction level. 



List all the features the financial institution  should incorporate into their financial crime detection model, as well as the step-by-step approach you would take to solving this problem. Be as specific as possible, including particular techniques you would employ, etc. 

We need the features which allow (us) to identify the unusual trend in the transaction or transaction behavior. To be very specific the required feature and approach would be as below:

•	Account holder personal details like physical Address, Age, Job, Salary, gender and other meta data regarding the education and job status. 

•	Account holder ( History)

•	Logging data of the each transacted / withdrawal including the IP address

•	Location and date:  if the transacted / withdrawal location is different from the account holder ‘registered location’ is worth checking

•	General information (From, To, Date of transaction)

•	Invoice for which purpose Work/Service

•	Method of Transfer (Electronic transfer, Cash) with Date, Value,

•	Title of transfer

•	Transfer Amount and date

•	Balance and balance history

•	Account holder metadata ( Loan, Housing, Job, Education)

•	Electronic Transfer (Account of sender, Account of receiver)

•	Amount of cash withdrawn (large currency transactions are suspicious)

•	Comparing the average balance of the account holder and wit the value of the amount withdrawn. If the proportion of the amount transacted / withdrawal is more than the average balance than it’s unusual

•	Also, the proportion of value of amount withdrawal / transacted by the account holder to that of the previous deposit.

•	Sometimes the identity of the  transaction is hidden that is  structuring of transactions to avoid identification  can be suspicious

•	Also if personal identity is not able to determine can be suspicious

•	Comparing the proportion of value of amount withdrawal / transacted to with the “average/mean’ withdrawal of the customer s who share similar credit score or characteristics like gender , age , income or economic status , education ,  job ,salary, housing, loan. If its inconsistent that its unusual 

•	Unusual deviations from normal account deposit and transaction patterns. Also history data to know the timeline of transactions and deposit usually done on an average by the account holder is not consistent

•	 Understand historical patterns using visualization

•	correlating all the features in real time making sure to exclude the lurking variables / confounding variable because correlation is not causation

•	Removing the outliers because outliers introduced a bias.

•	For the problem solving, monitoring the list of transactions where we can have a column containing the value of ‘0’ or ‘1’ for the non-fraudulent and fraudulent transaction respectively.

•	 Supervised learning models like Random forest, decision tree, neural networks and SVM and logistic regressions can be used on the each transaction and they generate the models in an optimal way classifying the the ‘0’ and ‘1’ to get the true positive and with the minimum false positive incidence.

•	To know the best models works for the transaction data can go with the one with highest Area Under the Curve (ACU) for choosing the model among those algorithms.



