# CompanyBudget

<h2>Description</h2>
This project shows how organizations can utilize VLOOKUP to clearly compare their departmental budgets to their actual spending. Additionally, conditional formatting is utilized to quickly draw attention to budget variances.

<h2>Environments Used</h2>

- <b> Microsoft Excel </b>

<h2>Functions Used</h2>

- <b> VLOOKUP </b>
- <b> Conditional Formatting </b>
- <b> Subtraction Calculation

<h2>Project Walk-Through</h2>

<p align="center">
Organizations will first create a table of their Budgets and then a separate Actuals table when they've finalized actual spendings: <br/>
  
<img src="https://imgur.com/ambkAYI.png" height="60%" width="60%" alt="BudgetVariance"/>
<br />
<br />
Then, A 'Budgeted Spend' column will be added to the Actual Spending table. VLOOKUP is used in the first cell of this column to fill this column with the values from the budget table: <br/>
<img src="https://imgur.com/lqr7mMi.png" height="60%" width="60%" alt="BudgetVariance"/>
<br />
<br />
A closer look at the VLOOKUP formula: <br/>

<p align="center">
<img src="https://imgur.com/Y4vYuuz.png" height="60%" width="60%" alt="BudgetVariance"/>
  
<p align="Left">
- The lookup_value refers to the chosen department (Marketing in this case) in the actual table, because we want to find the budget for this department
<br />
- <b>The table_array refers to the entirety of the budget table, where excel will be looking to find the information</b>
<br />
- <b>The col_index_num refers to the second column in the budget table, because we are looking to pull the budgets and not the department names</b>
<br />
- <b>We want an exact match, so range_lookup is FALSE</b>
<br />
<br />
<p align="center">
Next, A Budget Variance column will be added by subtracting the actual spend column from the budget column to see if actual spending is within or exceeded the budget: </b>

<img src="https://imgur.com/bFMHaOH.png" height="60%" width="60%" alt="BudgetVariance"/>
<br />
<br />
<p align="center">
Conditional Formatting was added to the Budget Variance column to quickly visualize which departments go over the budget (red) and which remain within the planned budget (green): </b>
<img src="https://imgur.com/pSyAiqq.png" height="60%" width="60%" alt="BudgetVariance"/>
<br />
<br />
<img src="https://imgur.com/EsOuu6i.png" height="60%" width="60%" alt="BudgetVariance"/>


<h2>Conclusion</h2>
VLOOKUP allows organizations to easily analyze how well they stick to budgets, and areas that require improvements. Pushing the organization to develop strategies for effective and efficient allocation of finances across departments. In addition, using conditional formatting on tables allows quick and clear communication of findings.
