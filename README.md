# Accounting Overview

The following nemonic can help us to understand what Debit and Credit represents in any Accounting software.

**Fundamentals:**

**F1:**
```
Assets (What you own) = Liabilities (What you owe) + Equity (What you get capital Profits Losses)
```
**F2:**
```
Equity = Assets - Liabilities
```

**F3:**
```
Liabilities = Assets - Equity
```

**General Chart of Accounts:**

```markdown
| Root Headers   |
|----------------|
| Assets         |
| Liabilities    |
| Equity         |
| Revenue/Income |
| Expenses       |
```
**Financial Workflow:**

**Journal Entry:**
Record financial transactions.

**Ledger:**
Post entries from the journal into individual ledger accounts.

**Trial Balance:**
  Summarize ledger balances to check for accuracy.
  
**Trading and Profit and Loss Account:**
Determine the profit or loss from trading activities.

**Balance Sheet:**
Provide a snapshot of the company's financial position.

**Example:**

`Journal Entry → Ledger → Trial Balance → Trading and Profit and Loss → Balance Sheet`

**Debit & Credit:**

We can remember how accounting Debit and Credit work using this mnemonic called _**DEALER.**_

| Letter | Meaning        |
|--------|----------------|
| D      | Debit          |
| E      | Expenses       |
| A      | Assets         |
| L      | Liabilities    |
| E      | Equity         |
| R      | Revenue/Income |

**Debit:**

Increases ***Expenses*** and ***Assets***

Decreases ***Liabilities***, ***Equity***, and ***Revenue/Income***


**Credit:**

Increases ***Liabilities***, ***Equity***, and ***Revenue/Income***

Decreases ***Expenses*** and ***Assets***

# Journal Entry Scenarios:

### **Scenario 1: Sales Invoice to Customer:**

| Root Category |     Sub-Category    | Debit | Credit |
|:-------------:|:-------------------:|:-----:|:------:|
| Asset         | Accounts Receivable | $1000 |        |
| Income        | Sales Revenue       |       | $900   |
| Liability     | Tax Payable         |       | $100   |
| Expense       | Cost of Goods Sold  | $600  |        |
| Asset         | Inventory           |       | $600   |

### Explanation:

-   **Asset (Accounts Receivable)**: The customer owes $1,000.
-   **Income (Sales Revenue)**: Revenue from the sale is $900.
-   **Liability (Tax Payable)**: $100 tax is owed to the government.
-   **Expense (COGS)**: The cost of goods sold is $600.
-   **Asset (Inventory)**: Inventory decreases by $600.

### **Scenario 2: Payment Entry against the Sales Invoice:**
 
| Root Category |     Sub-Category    | Debit | Credit |
|:-------------:|:-------------------:|:-----:|:------:|
| Asset         | Cash/Bank           | $1000 |        |
| Asset         | Accounts Receivable |       | $1000  |

### Explanation:

-   **Asset (Cash/Bank)**: The company receives $1,000 in payment.
-   **Asset (Accounts Receivable)**: The customer’s outstanding balance is cleared.

### **Scenario 3: Regular Salary to the Employee:**

| Root Category |    Sub-Category    | Debit | Credit |
|:-------------:|:------------------:|:-----:|:------:|
| Expense       | Salary Expense     | $3000 |        |
| Liability     | Deductions Payable |       | $500   |
| Asset         | Cash/Bank          |       | $2500  |

### Explanation:

-   **Expense (Salary Expense)**: The full salary expense of $3,000 is recorded.
-   **Liability (Deductions Payable)**: $500 is withheld for taxes/contributions.
-   **Asset (Cash/Bank)**: The company pays $2,500 to the employee.

### **Scenario 4: Bonus Given to the Employee:**
 
| Root Category |  Sub-Category | Debit | Credit |
|:-------------:|:-------------:|:-----:|:------:|
| Expense       | Bonus Expense | $500  |        |
| Asset         | Cash/Bank     |       | $500   |

### Explanation:

-   **Expense (Bonus Expense)**: Debited by $500 to record the cost of the bonus payment.
-   **Asset (Cash/Bank)**: Credited by $500 as the company pays the bonus in cash.

### **Scenario 5: When the Bonus is Paid Along with Salary:**

Let’s assume the employee’s regular salary is **$3,000**, and the bonus is paid along with the salary.

#### Combined Table (Salary + Bonus Payment):

| Root Category |    Sub-Category    | Debit | Credit |
|:-------------:|:------------------:|:-----:|:------:|
| Expense       | Salary Expense     | $3000 |        |
| Expense       | Bonus Expense      | $500  |        |
| Liability     | Deductions Payable |       | $500   |
| Asset         | Cash/Bank          |       | $3000  |

### Explanation:

-   **Expense (Salary Expense)**: Debited by $3,000 for the regular salary.
-   **Expense (Bonus Expense)**: Debited by $500 for the bonus.
-   **Liability (Deductions Payable)**: Credited by $500 for any deductions (taxes, contributions, etc.).
-   **Asset (Cash/Bank)**: Credited by $3,000 for the net payment (including the bonus).

### **Scenario 6: Advance Salary to the Employee:**

| Root Category |  Sub-Category  | Debit | Credit |
|:-------------:|:--------------:|:-----:|:------:|
| Asset         | Advance Salary | $1000 |        |
| Asset         | Cash/Bank      |       | $1000  |

### Explanation:

-   **Asset (Advance Salary)**: The advance salary is treated as a receivable from the employee.
-   **Asset (Cash/Bank)**: The company pays out $1,000 in cash.

### **Scenario 7: Salary to the Employee with Advance Deduction:**

| Root Category |  Sub-Category  | Debit | Credit |
|:-------------:|:--------------:|:-----:|:------:|
| Expense       | Salary Expense | $3000 |        |
| Asset         | Advance Salary |       | $1000  |
| Asset         | Cash/Bank      |       | $2000  |

### Explanation:

-   **Expense (Salary Expense)**: The employee’s full salary is recorded as $3,000.
-   **Asset (Advance Salary)**: The $1,000 advance is deducted from the total.
-   **Asset (Cash/Bank)**: The company pays $2,000 to the employee after the advance deduction.

### **Scenario 8: Employee Takes a Loan from the Company:**

| Root Category |  Sub-Category | Debit | Credit |
|:-------------:|:-------------:|:-----:|:------:|
| Asset         | Employee Loan | $2000 |        |
| Asset         | Cash/Bank     |       | $2000  |

### Explanation:

-   **Asset (Employee Loan)**: Debited by $2,000 as the company records the loan given to the employee. This is treated as a receivable because the employee will repay the loan in the future.
-   **Asset (Cash/Bank)**: Credited by $2,000 because the company is paying out this amount to the employee.

### **Scenario 9: Deduct 6% of Loan during Salary Payment:**

The employee's regular salary is **$3,000**, and **6%** of the loan **($120)** is deducted during the salary payment.

| Root Category |    Sub-Category    | Debit | Credit |
|:-------------:|:------------------:|:-----:|:------:|
| Expense       | Salary Expense     | $3000 |        |
| Liability     | Deductions Payable |       | $500   |
| Asset         | Cash/Bank          |       | $2380  |
| Asset         | Employee Loan      |       | $120   |

### Explanation:

-   **Expense (Salary Expense)**: Debited by $3,000 for the full salary amount.
-   **Liability (Deductions Payable)**: Credited by $500 for tax or other deductions.
-   **Asset (Cash/Bank)**: Credited by $2,380, which is the net salary paid to the employee after the 6% loan deduction and taxes.
-   **Asset (Employee Loan)**: Credited by $120 to reflect the reduction in the employee's loan balance (6% of $2,000).


### License:
MIT
