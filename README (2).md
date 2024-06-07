
## EDA

The process started with first of all understanding the data for which EDA had to be done , all particular EDA can be seen in the EDA notebook.

Product name and Product IDs numbers have a mismtach , base don analysis single product name can hve multiple ID'scoresimilar was the case for Customer but the reason is because isnlg ecustomer can be part of multiple departments in an office aand hence can have multiple ID's.

Shipment mode was on same day there was cases where shipped mode is on a different day and not on the  same day .

For the categories Furniture, office supllies and technology, we have chairs storage and phones contributing to maximum sales respectively.
West and East regions also contributed to maximum profits and sales based of our analysis. Whereas average discount was maximium in the central region which shows that they might me increasing the discounts to attract more customer purchase in that region as this region contributes to kess profits and sales. California is the state that has the highest sales and profits.

Further more what is of quintessential importance is that we correct the prices due to huge variations in prices.Hence we built a statistical approach such that in cases where we see variations where discount =0 on Price Per Unit for each level of Product, Region and Segment we correct it by clustering them first.Once we get these 2 price points if there is a variation of more than 25% we flag them. In these cases we calculate the weighted average based on frequency and then use this weighted average for cases where the price per unit on the aforementioned level is betweeb 25th and 75th percentile then its correct else we take the weighted average.This is mentioned in the notebook Price_Correction.

 In terms of sub-categories we have binders and machines providing maximum discount.

 Based on the analytical question that were provided, following are the insights (GRAPHS AND RESULTS AVAILABLE IN NOTEBOOKS):
1) The results fo this can be seen on Question_1 notebook
2)This Jupyter Notebook analyzes the effectiveness of promotional campaigns by examining sales data before, during, and after promotions to measure their impact on sales performance. It includes data loading, preprocessing, exploratory data analysis, and detailed statistical analysis to evaluate the impact of promotions. Key metrics such as average sales before, during, and after promotions and the lift in sales are calculated and visualized. The findings indicate a significant increase in sales during promotions, with a noticeable but smaller lift in sales immediately after the promotions end. These insights suggest that promotional campaigns are effective in boosting sales, and the notebook provides recommendations for optimizing future promotional strategies based on these results. 
3) Purchsing pattern shows that consumer segment has the most order size andpurchase freuency. Each segment prefers office supplies over other categories, with consumer segment purchasing most of the office supplies.




