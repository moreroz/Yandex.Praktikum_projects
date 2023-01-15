If you have problems viewing the code, please use https://nbviewer.jupyter.org/

# Initial data

CSV files containing data on churn for a given month and information on the month preceding it.

The dataset includes the following fields:

**Churn** — the fact of churn for the month in question
Current dataset fields: User data for the preceding month

- **gender**
- **Near_Location** - whether the user lives or works in the neighborhood where the gym is located
- **Partner** - whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers)
- **Phone** - whether the user provided their phone number
- **Age**
- **Lifetime** - the time (in months) since the customer first came to the gym

Data from the log of visits and purchases and data on current membership status

- **Contract_period** - 1 month, 3 months, 6 months, or 1 year
- **Month_to_end_contract** - the months remaining until the contract expires
- **Group_visits** - whether the user takes part in group sessions
- **Avg_class_frequency_total** - average frequency of visits per week over the customer's lifetime
- **Avg_class_frequency_current_month** - average frequency of visits per week over the preceding month
- **Avg_additional_charges_total** - the total amount of money spent on other gym services: cafe, athletic goods, cosmetics, massages, etc.

# Goals

To analyze data on customer profiles and come up with a customer retention strategy.

# Libraries used

- pandas
- seaborn
- time
- matplotlib
- sklearn
- scipy

# Content

The following tasks were solved:
- model to predict user churn was built
- user clusters were created
- clustering model was trained

# Main conclusions
- The lenght of the contract as well as amount of months till the end of it play an important role in retention of users - so it's necessary to suggest clients profitable long-term contracts, increase engagements and check for the errors on the part of the client service. If a client doesn't come to the gym for a couple of weeks it is worth ask him why.
- Loyal users are also a subject for higher engagement - some addittional activities, new bonuses included to contracts, discounts, fresh offers - all that could help in client retention. The opportunity to receive profitable contract will motivate users to stay.
