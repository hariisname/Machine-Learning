# 1)Bigmart Sales Analysis using ML(Regression Problem)

### Project Overview & Brief Introduction:
-------------------------------------------
The main aim of this project is to analyze and predict sales for a retail stores, BigMart's, 
based on various features such as item weight, visibility, type, MRP, outlet details, etc. 
'Item_Identifier', 'Item_Weight', 'Item_Fat_Content', 'Item_Visibility','Item_Type', 'Item_MRP', 'Outlet_Identifier','Outlet_Establishment_Year', 'Outlet_Size', 'Outlet_Location_Type','Outlet_Type', 'Item_Outlet_Sales'
The problem addressed is the need for accurate sales predictions, which can lead to better decision-making regarding 
stocking, pricing, and overall business performance.

### Tools & Technologies:
---------------------------
Programming Language            : Python                                                                 
Machine Learning Libraries      : Scikit-learn for model building
Data Analysis and Visualization : NumPy, Pandas, Matplotlib, Seaborn
IDE                             : Jupyter Notebook
while Im doing this project i followed one structure that :-
Project Structure that i followed as EDA, data preprocessing, model training, evaluation, and visualization.

### the analysis and insights i got through this project are:
------------------------------------------------------------
	(Univariate Plots(for categorical features), with help of count plot)
	- Item_Fat_Content: Most Items sold are low Fat.
	- Item_Type: specifically fruits & vegitables, food snacks are popular.
	- Item_Type_Combined: Most Sold Item cateogory is food.
	- Outlet_Identifier: Sold items are ditributed evenly amoung all stores, execpt OUT010 and OUT019.
	- Outlet_Size: Bigmart Stores are mostly in medium size in this data.
	- Outlet_Location_Type: Most comon type of location is Tier3
	- Outlet_Type: By a wide mergin Most Store Types are SuperMarket Type1.
	(Univariate Plots(for numerical features),with help of histogram)	
	-  Most Common Outlets are 35 year's old.
	(Bivariate Plots(for Numerical features), with help of scatter plot)
	- negative relationship between item visibility and sales; as visibility increases, sales tend to decrease.
	- there is no relationship between item weight and sales.
	- There is a positive correlation between item MRP and sales; higher MRP items tend to have better sales.
	(Bivariate Plots(for Numerical features), with help of Bar plot)
	- compare to others like drinks and non-consumable(Household Items, Personal Care Products, Clothing and electronic) products; 
	  the Food category has the highest sales including vegitables, snacks, breakfast and sea food
	- Outlet027 is the most profitable, while Outlet019 and Outlet010 have the lowest sales
	- SuperMarket Type3 has the highest sales

### while doing this project i faced some Challenges:
----------------------------------------------------
	- while data cleaing i have some missing/null values in Item_weight and Outlet_Size
	  * in item_weight I filled the missing values based on the item identifier, because each item identifier was associated with a different item weight.
	  * in Outlet_Size I filled the missing values based on the Outlet_Type, because each Outlet_Type was associated with a different Outlet_Size. 
	- and some of the columns have 0 item visibility, those items i filled with mean value 
	- and in Item fat content have(Low Fat, Regular, low fat,LF, REG) 5 columns but actual is only 2 types regular fat and low fact so that i replaced data accordingly

### models building:
-------------------
	- i tried different ml modles like linear, lasso, righe, decision tree, random forest, SVM and KNN : through out all models knn is performing well  
### Conclusions:
------------------
	- The BigMart Sales Project is a powerful tool for optimizing inventory and sales strategies. 
	  By leveraging data, BigMart can make informed decisions to enhance customer experience, reduce costs, 
          and boost overall sales. Based on these insights, business leaders can improve decision-making. 
          BigMart has the opportunity to enhance customer experience, streamline stocking and pricing decisions, and ultimately elevate its overall business performance.

