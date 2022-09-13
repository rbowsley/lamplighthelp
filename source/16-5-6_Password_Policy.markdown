# 16.5.6  <i class="fas fa-address-card"></i> Password Policy

> Password policies set rules for database operator passwords



A System or Project Administrator can determine the rules for all passwords on their {{Lamplight}} system. For example, your organisation’s IT policy may require passwords to be at least 10 characters long with a mixture of characters. You can set this up in {{Lamplight}} to ensure that everyone complies. Password policies apply to all database operators.

### To Set Up a Password Policy
- Go to 'admin -> system administration -> Database Operators and Security -> Set up or edit your password policy’.
- You will see the following options:

![Password Policy](16.5.6a.png)

- Tick the ones that you wish to apply, and click ‘save’ when done.

Whichever options you choose, when operators next change their passwords they will have to comply with this policy.  Guidance on passwords is available from the [National Cyber Security Centre](https://www.ncsc.gov.uk/section/advice-guidance/all-topics?topics=passwords&sort=date%2Bdesc&start=0&rows=20).

If you need to make sure that all operators change their passwords so that they comply immediately:
   - Go to in system administration go to Database Operators and Security -> Manage database operators.
   - Right-click on the first operator in the list. 
   - From the pop-up menu choose 'Force password change'.
   - Repeat this for every database operator in the table. 
   - The next time they log in they will have to change their password to comply with the new rules. 


##### Tags
Advanced topics
System admin
Security

###### core module
