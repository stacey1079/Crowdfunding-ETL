# Crowdfunding-ETL
Module 8
## Summary
The purpose of this analysis was to perform ETL and data analysis on a new dataset that contains backer information who have pledged to live projects.  Independent Funding requested some new tables made from the backers email information and what was left of the goal for the live projects.  They also requested a table from the contacts information with the remaining goal amount.  This was done by creating three new tables.  
1. The backers table is made up of the backers information.  The columns are: backer_id, cf_id, first_name, last_name, and email.
2. The email_contacts_remaining_goal_amount.  This table was made to have a list of all the backers emails, names, their company names, cf_id, description of the campaign, the ending date of the campaign, and the reamining goal amount.
3. The email_backers_remaining_goal_amount.  This table was created in order to have an email list to send the backers of the live campaigns emails to keep them aware of the remaining goal amount.  It's columns are first_name, last_name, email, and remaining goal amount.
