If you have problems viewing the code, please use https://nbviewer.jupyter.org/
# Initial data
Data on two prepaid plans of a mobile operator:
- users characteristics (id, name, age, subscription date, plan)
- calls data (unique call identifier, call date, duration, the identifier of the user making the call)
- messages data (unique text message identifier, message date, the identifier of the user sending the text)
- internet use (session identifier, mb used, web session date, user id)
- plans characteristics

# Goals
Find out which of the two plans brings in more revenue

# Libraries used
pandas, matplotlib, scipy, functools, seaborn, numpy, math

# Content
The following tasks were solved:
 - filling in missing values and data formatting
 - removing of duplicates
 - preparing pivot data with users data
 - comparing average revenue for different plans
 - comparing average revenue for different regions
 
# Main conclusions
- ultimate plan is more profitable for Megaline operator
- there is no significant difference between revenue for different regions
