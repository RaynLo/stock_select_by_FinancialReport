# stock_select_by_FinancialReport
To select stocks in TWSE market by the financial criteria.  

Core idea: To invest a company has the highest revenue in the industry that is growing. 


Step1. To obtain the stock financial data via CMoney Application with Excel functions, incloud the following data(10 columns):  

       股票代號/股票名稱/2020產業名稱/2019Q4毛利率(%)/2020Q1毛利率(%)/2020Q2毛利率(%)/202007近三月合併營收年成長(%)/202007單月合併營收(千)/自訂.季毛利率成長率/自訂.前兩季的毛利率QoQ成長率  
       

Step2. To calculate and select:  

       - the median of the quarterly profit rate in all the stocks of its own industries.  
       
       - select the Top 10 industries that the median stock profit rate is growing (QoQ).  
       
       - select (i) the Top 3 high revenue companies in each above industries.  
       
                    --> here, the revenue mean: the last monthly revenue.  
                    
                (ii) the Top 3 companies have high revenue growth rate in each above industries.  
                
                    --> the revenue growth rate mean: the Annual growth rate of consolidated revenue in the last three months.  




