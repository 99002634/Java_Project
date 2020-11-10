# Test Plan

|Requirement|	Type|	Description	|Result|
|------------|-----|-------------|------|
|L1|	Amount	|Amount present in the account|	Amount is obtained|
|L2|	Time |Period	Time for which the amount was present in the account| 	Time period is obtained|
|L3	|Age	|Age of the account holder|	Age is obtained|
|L1_L2_H1|	Fixed account related to amount and time	|The amount present in the fixed account will give the interest according to the time period	|Interest is obtained|
|L2_L1_H2|	Recurring account related to amount  time and age	|The interest  for recurring deposit is depending on the amount time and age	|Interest is obtained according to age and time of the deposit|
|H1|	Fixed Deposit	|Fixed account is the type of account discussed above	|Fixed account is explained|
|H2|	Recurring Deposit|	Recurring deposit is the type of deposit where every month some part of the amount is added and interest is obtained	|Recurring deposit is made and interest  is obtained|
|H3|	Savings Deposit	|This is a very commonly used account for salaries by most of the employees	|Savings account is obtained|
|L2_H3|	Recurring account related to AGE	|The interest is obtained according to the age of the person	|Interest is obtained according to the age|
|L2_H2	|Recurring account related to time  |	The interest is obtained to the time of money  deposited in the account|	Interest is obtained according to the time of amount deposited|
|L1_H3|	Savings account depends on the amount deposited	|The amount deposited in the account |	Interest is obtained according to the amount deposited|
|L2_L1_H3|	Savings account depends on the amount and time	|The amount deposited in the account depends on time	|Interest is obtained according to time|

#JUnit

