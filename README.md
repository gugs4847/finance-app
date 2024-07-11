# finance-app
An app to track my spending and my investing each month. Uses Plaid API, React, and SQL. 

# How to run:
- Clone repo
- Go to plaid.com and create a user
- In Plaid Dashboard, go to developers > keys, or go to https://dashboard.plaid.com/account/keys
- In repo, open the 'env' file with a notepad or text editor
- Copy the keys from Plaid and paste them where appropiate. Change the PLAID_ENV to sandbox. Save.
- In the repo, click 'ngrok.exe' and follow prompts
- Open a command window and navigate to the repo
- run ngrok http 8001
- Open a new command windows and navigate to the repo again
- run npm run watch
- go to localhost:8000

  
# To-do
- Make a column that shows all spending for a month
- Make a column that shows all spending for a particular date range
- Make a column that shows all investments for a month
- Make a column that shows all investments for a particular date range

- Eventually create an executable that will assist in starting the app.


# To-do, Extended
- Use Plaid to connect to banks
- Use the financial data from banks to sort output into categories
- Show weekend, weekly, and monthly spending
- Notifications for weekly spending?
- Show reoccurring bills
- Send info to finance sheet if able
