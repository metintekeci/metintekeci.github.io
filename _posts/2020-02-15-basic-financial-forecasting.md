---
layout: post
title: Basic Financial Forecasting
subtitle: ...developing a start-up company financials from scratch.
tags: [financial-modeling, three-statement financial model, balance sheet,  income statement, cash flow ]
---

You meet-up with your friends in a coffee shop and decided to start a company to sell out your new product. You know the details of the business, but you don't want to go deep into the financial vocabulary. Here you can find a simple way to develop your initial pro-forma financials to keep handy for a possible investor meeting or a tool for thinking about the viability of your business. 

You are thinking of putting $100K of start-up capital as ***equity*** on the table, and you will put all the amount right into this business as ***working capital***. You do not want to blow any portion of your money to ***fixed assets*** at least for now, and you are going to rent a fully furnished co-working space. This means, you are not going to think of ***depreciation and amortization*** of the equipments you will use in your company financials. You are not going ask for a loan from a bank, and you are planning to stay away from debt or any other ***liabilities***.

Your final model will look something like this!

![Basic Financial Model](/basic-financial-model.gif)

I think you feel more comfortable, once you saw the simple flow of three-statement financial model just in a spreadsheet.  Let's dive in!  


Your initial Balance Sheet on day 1 will look like this. Your initial capital on the Equity, and your decision to put the entire amount into the business is your Working Capital. You also decided not to rent a furnished office space, and this helped omitting **fixed assets** item in a balance sheet. 

| Assets | USD 000 | Liabilities + Equity | USD 000 |
|------|------:|------|------:|
| Cash |     0  | Liabilities | 0     |
| Working Capital | 100 | Equity | 100| 


You think you are going to sell at least $100K in the first year, and expect to grow your sales by 10% every year. The products you will sell, will cost you - ***Cost of Goods Sold - COGS*** - 20% of sales amount. 

Besides, you expect the ***Operational Expenses*** like payroll, sales commissions, employee benefits, transportation and travel, rent and other expenses to incur 70% of sales amount. 

You also think to keep your cash in the bank and receive 5% ***interest income*** over the year. The ***tax rate*** from your net income will be 30% and inevitable. 

Since you want to grow your business, you will continue to put 90% of your sales into the ***Working Capital***.

Now, we can summarize the assumptions of our financial model. 

| ASSUMPTIONS                  | USD |
|------------------------------|----:|
| Equity Capital               | 100 |
| Dividends                    | 0   |
| First-year sales             | 100 |
| Sales Growth per annum       | 10% |
| Cost of Goods Sold / Sales   | 20% |
| Operating Expense / Sales    | 70% |
| Interest Income rate         | 5%  |
| Tax rate                     | 30% |
| Working capital as % of sale | 90% |
| Depreciation                 | 0   |

Before continue reading, you may want to open a spreadsheet and type or copy the assumptions table above. Based on these assumptions, we can proceed to create our Income Statement. 

Note that, while you are entering the formulas into the spreadsheet you should not type any number including the first year Sales amount. Just link to the proper assumption item and lock the cell with F4. You may want to refer to the description table below the income statement for calculation details. 

| Line# | INCOME STATEMENT   | FY1   | FY2   | FY3   | FY4   | FY5    | 
|:-----:|--------------------|------:|------:|------:|------:|-------:| 
| 1     | Sales              | 100.0 | 110.0 | 121.0 | 133.1 | 146.4  | 
| 2     | Cost of Goods Sold | -20.0 | -22.0 | -24.2 | -26.6 | -29.3  | 
| 3     | Operating Expenses | -70.0 | -77.0 | -84.7 | -93.2 | -102.5 | 
| 4     | Interest Income    | 0.0   | 0.9   | 0.8   | 0.8   | 0.7    | 
| 5     | Income Before Tax  | 10.0  | 11.9  | 12.9  | 14.1  | 15.4   | 
| 6     | Taxes              | -3.0  | -3.6  | -3.9  | -4.2  | -4.6   | 
| 7     | Net Income         | 7.0   | 8.3   | 9.0   | 9.9   | 10.8   | 

As you can guess; Income Statement items are mainly derived from our **Sales**  amount, as per the assumptions. Sales forecasts may be very detailed, with separate forecasts for each product, geography, customer segment.  Similarly, **COGS** and **OPEX** can be broken down into detailed line items which can be forecasted separately. For the purposes of this post, we keep everything in its simplest form.  You can go over the descriptions for the Income statement items below. 


| Line# | Descriptions                                                                          | 
|-------|---------------------------------------------------------------------------------------| 
| 1     | **SALES** : Assumed $100 for the first year and grows by  "Sales Growth" assumption | 
| 2     | less - **COGS** : Assumed to be a percentage of Sales                         | 
| 3     | less - **OPEX** : Assumed to be a percentage of Sales                         | 
| 4     | **INTEREST INCOME** : Calculated as a percent of previous years Cash                 | 
| 5     | = **INCOME BEFORE TAX** : Sum of the above items                                            | 
| 6     | less - **TAX** : Percent of Income Before Tax                                                  | 
| 7     | = **NET INCOME** : is the net of Taxes from Income Before Tax                                 | 


  

Once you have finished with Income Statement, you can proceed to Balance Sheet items. Before typing the numbers lets get a brief overview of the balance sheet. This will help us to visualize which items balances with each other. Start with putting the most important equilibrium.

> **Assets = Liabilities + Equity**

preserving the above equilibrium, the details are;


|Cash / Borrowing          |Liabilities                   |
|:-------------------------|:-----------------------------|
|Working Capital (non-cash)|Equity                        |
|**TOTAL ASSETS**          |**TOTAL LIABILITIES + EQUITY**|


You may have seen various balance sheet layouts different then above. This is an over simplified version, that omits irrelevant items specific to our case. Remember we do not have fixed assets, as we rent the office, and we do not use bank loan. this level of granularity is sufficient for our purposes. 

|Line#|BALANCE SHEET             |Start|FY1  |FY2  |FY3  |FY4  |FY5  |
|-----|--------------------------|----:|----:|----:|----:|----:|----:|
|8    |Cash / Borrowing          |0,0  |17,0 |16,3 |15,4 |14,4 |13,2 |
|9    |Working Capital (non-cash)|100,0|90,0 |99,0 |108,9|119,8|131,8|
|10   |Total Assets              |100,0|107,0|115,3|124,3|134,2|144,9|
|     |                          |     |     |     |     |     |     |
|11   |Liabilities               |0,0  |0,0  |0,0  |0,0  |0,0  |0,0  |
|12   |Equity                    |100,0|107,0|115,3|124,3|134,2|144,9|
|13   |Total Liabilities + Equity|100,0|107,0|115,3|124,3|134,2|144,9|


Let's take a look at the calculation of **Balance Sheet** items below. 

|Line#|BALANCE SHEET             |Descriptions                                                            |
|-----|:-------------------------|------------------------------------------------------------------------|
|8    |Cash / Borrowing          |Cash = [Total Liabilities + Equity] - Working Capital       |
|9    |Working Capital (non-cash)|Start with initial $100 Equity; continue as a percentage of annual Sales|
|10   |Total Assets              |Sum of the above items                                                  |
|     |                          |                                                                        |
|11   |Liabilities               |Assumed no debt during the horizon                                      |
|12   |Equity                    |Starts with initial $100 Equity and grows with Net Income               |
|13   |Total Liabilities + Equity|Sum of the above items                                                  |

Before going deep into details of each item, **CHECK** if your balance sheet balances, that is to verify Line 10 equals to Line 13. If that is not ok, you might have an error in your formulas or links. Take some time to correct your spreadsheet and come back.

...

Now, we can continue to create Cash Flow Statement. ***Cash Flow Statements*** records the amount of cash entering into or leaving the company. Cash flow statements reveal the financial health of company. 

Since we focus on the cash movements only, we will focus on changes relating to cash. We will start by adjusting **Net Income** in the statement of Cash Flow.  
For example, we normally deduct Depreciation in the Income Statement calculations, but for cash flow statement we have to add it back as an adjustment to Net Income amount in the cash flow statement. No cash goes out of the company because of depreciation. In our case this is zero for all years, as seen in Line 15.

Likewise, increase in Fixed Capital grows the balance sheet but we deduct that amount for each year in the Cash Flow statement calculations. Any new investment made will lead a decrease in company cash, and we need to reflect it on the cash flow statement.  


 To calculate each period's cash flow, we will begin with Net Income from the Income Statement, (simply link Line 7 to Line 14). 

|Line#|CASH FLOW                          |FY1  |FY2 |FY3 |FY4 |FY5 |
|-----|-----------------------------------|----:|---:|---:|---:|---:|
|14   |Net Income                         |7,0  |8,3 |9,0 |9,9 |10,8|
|15   |Plus: Non-cash Items               |0,0  |0,0 |0,0 |0,0 |0,0 |
|16   |Less: Investment in Working Capital|-10,0|9,0 |9,9 |10,9|12,0|
|17   |Less: Investment in Fixed Capital  |0,0  |0,0 |0,0 |0,0 |0,0 |
|18   |Change in Cash                     |17,0 |-0,7|-0,9|-1,0|-1,2|
|19   |Beginning Cash                     |0,0  |17,0|16,3|15,4|14,4|
|20   |Ending Cash                        |17,0 |16,3|15,4|14,4|13,2|


You can have a more detailed description for each line item in below table. 

|Line#|CASH FLOW                          |Descriptions                                                                         |
|-----|-----------------------------------|-------------------------------------------------------------------------------------|
|14   |Net Income                         |Net Income from Line 7 in the Income statement.                                                              |
|15   |Plus: Non-cash Items               |Non cash Items ie. depreciation is to be added but this is zero in our case                                       |
|16   |Less: Investment in Working Capital|Annual change in Working Capital from Balance Sheet, take difference from previous year in (Line 9)                         |
|17   |Less: Investment in Fixed Capital  |Deduct increase in fixed capital, but since the company does not invest in fixed assets, there is no depreciation|
|18   |Change in Cash                     |Net Income + Non-Cash Items - Investment in Working Capital - Inv in Fixed Capital   |
|19   |Beginning Cash                     |Ending cash balance of the previous period from balance sheet                                     |
|20   |Ending Cash                        |Sum of the beginning Cash and Change in Cash  and **CHECK** if it is equal to Line 8                  |


 If you have finished creating spreadsheet version of your model, you can play with the initial assumptions table and observe changes. 

 If you are able to come this far, you can trust yourself that you can develop a basic three-statement financial model for your company. 
 
 Thank you for reading.

 ***
