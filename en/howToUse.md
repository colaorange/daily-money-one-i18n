## Concepts

The main concepts of Daily Money are very simple, there are only three:

> 1. One or many `Account Books`
> 2. Various `Accounts` within Account Books
> 3. Transferring amounts between different accounts and recording these `Transactions`

## ![Account Books](icon:///notebook-multiple) Account Books

At least one Account Book is required, with accounts having the same currency unit. You can also create multiple Account Books with the same currency unit according to your needs.

## ![Accounts](icon:///bookmark-multiple) Accounts

There are five different types of accounts, which you can add, edit, or delete on the account management screen.

> - `Income`: Salary, etc.
> - `Expense`: Food, entertainment, etc.
> - `Assets`: Cash, bank, etc.
> - `Liabilities`: Credit cards, loans, etc.
> - `Others`: ...

* Account names can use dots (.) to separate (e.g., Food.Dining, Food.Gathering), providing a better hierarchical display when selecting accounts or viewing balance sheets.
* You can sort accounts to prioritize more frequently used accounts.

## ![Transactions](icon:///receipt) Transactions 

When there is a transaction between accounts, such as spending, withdrawing, depositing, or swiping a credit card (e.g., you spent 320 yuan on a meal), use `New Transaction` to create a new transaction.
> - Select `Date and Time`: Date and time of the transaction.
> - Select `Transfer-out Account`: Cash
> - Select `Transfer-in Account`: Dining
> - Input `Amount`: 320
> - Input `Note`: Gathering with friends
> - Click `Create`

## Examples

### Salary Transfer to Bank

> Transfer-out `Income` Account: Salary
> Transfer-in `Assets` Account: Bank

### Withdraw Cash from Bank

> Transfer-out `Assets` Account: Bank
> Transfer-in `Assets` Account: Cash

### Purchase a Phone with Credit Card

> Transfer-out `Liabilities` Account: Credit Card
> Transfer-in `Expense` Account: Electronics

### Pay Credit Card Bill with Bank

> Transfer-out `Assets` Account: Bank 
> Transfer-in `Liabilities` Account: Credit Card

## ![Balance Sheet](icon:///scale-balance)![Balance Chart](icon:///chart-pie) Balance Sheet & Chart

Through diligent accounting, the application will help you record all transaction details and generate a balance sheet according to query conditions. This sheet clearly presents the balance of assets and liabilities in different time periods, allowing you to better understand your financial situation. Additionally, the application can generate various charts to visually represent your income and expenses, making it easier for you to understand your financial flow.

## Initial Values of Accounts

When you first use the application, you may already have some current accounts with actual values, such as bank deposits, cash on hand, or credit card debts. To ensure that the balance sheet provides more accurate calculation results, you can use the function of initializing accounts to establish the correct initial values of these accounts. In this way, you can make the balance sheet reflect the true financial situation.

## One-to-Many Splitting

Sometimes, a single expense may involve multiple categories of expenditure. For example, when shopping at a supermarket, you may purchase food, daily necessities, and electronic products at once. To cope with this situation, the application provides advanced transaction creation editing, allowing a single expense to be allocated to multiple different expenditure categories. In other words, you can allocate the amount of a single credit card swipe expense to multiple categories such as food, daily necessities, and electronic products. Please note: In transactions within the same account book, because the currency units are equal, the total amount transferred out must be equal to the total amount transferred in, otherwise the program will reject your transaction creation.

## Transfer between Account Books

The program allows you to transfer between accounts in different account books. Whether in the basic or advanced transaction editing or creation screen, you can select accounts from other account books when selecting accounts. Since the currency values between different account books may differ, and the exchange rate is not fixed at the moment, such as transferring from New Taiwan Dollars to US Dollars, the program will not limit you to create a transaction where the total amount transferred out must be equal to the total amount transferred in. Please create transactions based on the actual amounts when creating and be careful.

## Quick View of Balance Sheet and Charts

When browsing the balance sheet or charts, you can add specific account items to the quick view to the home screen [*1]. Simply swipe right on the item in the balance sheet and click `Add to Quick View`, or click "Add to Quick View Icon" at the upper right corner of the balance chart card. Next, on the home screen, you'll see the balance of assets and liabilities for that item, or you can view it on the chart page of the home screen. Additionally, you can sort or remove these items in `Preferences > Home Screen Settings`.

[*1] Excessive quick views on the home screen may affect the loading time of the home screen.