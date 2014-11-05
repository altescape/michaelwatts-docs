michaelwatts.me-website
=======================

Include: links.md

---

Include: Saudi Fashion Magazine.md

---
## POS Store Incentive application
url: private Github repository, need to make clone public and remove any DB refs.

Aim:
- To increase membership to Saudi Fashion Magazine. Cashier staff were incentivised to 'sign-up' customers at POS. Data is processed using Oracle and sent to our server where its validated and processed for use.

Languages:
- PHP

Breakdown of work:
- Designed and wrote application to process data from Oracle POS.
- Data is exported every day from Oracle as CSV by Saudi team and uploaded to our server.
- A Cron job on our server checks every 12 hours for a newly uploaded file.
- Application reads the CSV file, error checks, validates, formats, logs and creates files as XML (for import to ExpressionEngine), JSON (for fun) and CSV (for use in Excel).
- Data is syphoned into good and bad reports so that the Saudi team can deal with problems or system cheats (cashiers are incentivised to ask customers for data so a cashier could enter dummy data on a transaction to boost earnings).
- Using Campaign Monitor's API it then creates custom fields and subscribers. 
- Emails are sent from Campaign Monitor where successful opens can be segmented by gender, store, brand, mall, location or staff id.

---
## #Are you fashion competition
url: http://are-you-fashion.com (login with mike@smswmedia.com) can also see backend at /report

Aim:
- Marketing campaign to build up awareness of Saudi Fashion Magazine with massive posters on the side of malls, campaigns on Facebook, Twitter, etc, etc. The aim was to have people enter their details and tell us why they 'were fashion' and also upload a picture of themselves.

Languages:
- PHP
- Laravel
- SCSS

Breakdown of work:
- need to add

---

Include: Gap Facebook Applications.m

---

Include: Picture Matching Facebook Game.md

---
## SITA Horizon Value Calculator

Languages:
- AngularJS
- SCSS

Breakdown of work:
- need to add
