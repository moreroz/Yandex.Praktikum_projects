If you have problems viewing the code, please use https://nbviewer.jupyter.org/
# Initial data
Data on store's product range:
- order identifier
- item identifier
- item name
- quantity
- order date
- price per item
- customer id
# Libraries used
pandas, numpy, matplotlib.pyplot, scipy, seaborn, plotly, itertools, collections, datetime, squarify
# Goals
Analyze the store's product range
Carry out exploratory data analysis
Analyze the product range
Formulate and test statistical hypotheses
# Content
The following tasks were solved:
 - changing of data types
 - removing of errors/not applicable data
 - removing of duplicates
 - product range was analysed, recommendations on further product strategy were done
 - testing hypotheses (sales are growing during the holidays, average revenue on weekends and weekdays)
# Main conclusions
- In general Revenue tends to grow during period given
- Demand increase is clearly visible in October and especially in November which is most likely due to Christmas and New year.
- List of products which are often sold together was prepared - we recommend to provide a discount on them when contain in one invoice and also to promote this oppotunity to users.
- Top-10 products should stay in the store as well as products with high RFM score. Products with lowest RFM score are subject to refuse
- There is also seasonality for best sellers was identified (high sales of them in November). It means that they definitely should be in stock in demanded amount just before November.
- We created list of cheap and popular items which are always should be promoted on the store's website.
- Average check (based on amount of orders) on holidays is equal to average check on working days.
- Average check on weekends is not equal to average check on weekdays
