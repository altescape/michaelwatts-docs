## POS Store Incentive application

[sits on private Github repository, need to make clone public and remove any DB refs.]

### Languages/Principles:
- PHP OOP
- Dependancy Injection
- Inheritance
- Using SOLID principles

### Summary:
- A POS sign-up process to increase membership to Saudi Fashion Magazine. Cashier staff were incentivised to 'sign-up' customers at the till. They are then signed up to Saudi Fashion Magazine as members and contacted via email.  Data is processed using Oracle and sent to our server where its validated and processed for use.

Breakdown of work:
- Designed and wrote specification of requirements and the application to process data from Oracle POS.
- Implemented the following:
	- Data is exported every day from an Oracle server in Saudi and uploaded to our server in UK.
	- Every 12 hours our application checks for a new file from Oracle.
	- The application then reads the uploaded Oracle file, it then... 
		1. error checks,
		2. validates,
		3. formats,
		4. logs, 
		5. creates XML file for import to Saudi Fashion Magazine, 
		6. creates a JSON file
		7. and creates a CSV file for use in Excel.
	- Data is syphoned into good and bad reports so that the Saudi team can deal with problems or system cheats (cashiers are incentivised to ask customers for data so a cashier could enter dummy data on a transaction to boost earnings).
	- The application then creates and adds subscribers to Campaign Monitor via their API. 
	- Emails are then sent from Campaign Monitor where successful opens can be reported on and segmented by gender, store, brand, mall, location and staff id.
