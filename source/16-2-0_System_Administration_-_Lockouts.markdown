# 16.2.0 System Administration - Lockouts

> If a database operator has tried to log in to their account 10 times without success the account will be locked. It is also possible to temporarily lock the acccount of an operator if you do not want them to access the system for any reason



### Failed Log-in Attempts

Failed attempts to access {{Lamplight}} don't have to be all at once - they can be across a number of sessions, days or weeks. 

If you are locked out of {{Lamplight}} you will see this message:

!{Lockout message](16.2.0a.png)

A System Administrator will need to unlock the account. 

To do this:
- Go to system admin, then under Database Operators and Security choose 'Manage database operators'.

![Manage Database Operators](16.2.0b.png)

- Find the operator in the table then right-click on their name.
- Click on 'Unlock operator login' from the menu.

![Unlock Operator Login](16.2.0c.png)

- The next time the operator logs in they need to use their most recent password. If they have requested a new one they will need to use the last password they were sent.

**Please note: There will only be one chance to log in correctly before being locked out again. If this happens you will need to go through the same process as above. Once successfully logged in the account is set back to 10 attempts at log in before locking again.**

### Deliberate Lock-Out

If you do not want a database operator to access the database for any reason, a System Administrator can lock the account. 

- Go to system admin, then under Database Operators and Security choose 'Manage database operators'.
- In the database operators table, right-click on the operator’s name.
- Click on 'Lock operator login' from the menu.
- When you would like them to have access again, the System Administrator can unlock the account (see above under 'Failed Log-In Attempts').

If the operator will not need to access the database again, for example if they have left your organisation, then it is better to delete their operator log-in. For more on this see [5.6.0 Archiving, Deleting and Restricted Processing](/help/index/p/5.6.0).


##### Tags
Getting started  
System admin

###### core module
