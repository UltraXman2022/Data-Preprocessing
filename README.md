<h1>Project description</h1>
Your project is to prepare a report for a bank’s loan division. You’ll need to find out if a customer’s marital status and number of children have an impact on whether they will default on a loan. 
The bank already has some data on customers’ credit worthiness.
Your report will be considered when building a credit score for a potential customer. A credit score is used to evaluate the ability of a potential borrower to repay their loan.<br><br>

<h2>Instructions for completing the project</h2>
Step 1. Open the data file /datasets/credit_scoring_eng.csv and have a look at the general information.<br>
Step 2. Preprocess the data:<br>
<ol><li>Identify and fill in missing values</li>
<li>Replace the real number data type with the integer type</li>
<li>Delete duplicate data</li>
<li>Categorize the data</li></ol>
  
<h2>Be sure to explain:</h2>
<ol><li>Which missing values you identified</li>
<li>Possible reasons these missing values were present</li>
<li>Which method you used to fill in missing values</li>
<li>Which method you used to find and delete duplicate data and why</li>
<li>Possible reasons why duplicate data was present</li>
<li>Which method you used to change the data type and why</li>
<li>Which dictionaries you've selected for this dataset and why</li></ol>
  
The data may contain artifacts, or values that don't correspond to reality (for instance, a negative number of days employed). This kind of thing happens when you're working with real data. You need to describe the possible reasons such data may have turned up and process it.

<h2>Step 3. Answer these questions:</h2>
<ol><li>Is there a connection between having kids and repaying a loan on time?</li>
<li>Is there a connection between marital status and repaying a loan on time?</li>
<li>Is there a connection between income level and repaying a loan on time?</li>
<li>How do different loan purposes affect on-time loan repayment?</li>
<li>Interpret your answers. Explain what the results you obtained mean.</li></ol>
  
<h2>Step 4. Write an overall conclusion.</h2>
<h3>Format:</h3>
Complete the project in the Jupyter Notebook (it will open when you click Next). Write code in code cells and notes with explanations and interpretations in markdown cells. Use formatting and headings.<br>

<b>Description of the data<b><br>
<ul><li>children: the number of children in the family</li>
<li>days_employed: how long the customer has been working</li>
<li>dob_years: the customer’s age</li>
<li>education: the customer’s education level</li>
<li>education_id: identifier for the customer’s education</li>
<li>family_status: the customer’s marital status</li>
<li>family_status_id: identifier for the customer’s marital status</li>
<li>gender: the customer’s gender</li>
<li>income_type: the customer’s income type</li>
<li>debt: whether the customer has ever defaulted on a loan</li>
<li>total_income: monthly income</li>
<li>purpose: reason for taking out a loan</li></ul><br>
