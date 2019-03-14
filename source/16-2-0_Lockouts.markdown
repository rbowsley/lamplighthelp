#  16.2.0 Lockouts

> If a database operator has tried to log in to their account 10 times without success the account will be locked. It is also possible to temporarily lock the acccount of an operator if you do not want them to access the system for any reason

### Failed Log-in Attempts

Failed attempts to access {{Lamplight}} don't have to be all at once, so they can be across a number of sessions, days or weeks. 

They'll see this message:

xxxxxx Picture here xxxxxx


A system administrator will need to unlock the account. 

To do this:
- Go to system admin, then under Manage Database Operators choose Add, edit and remove operators.
- In the database operators table, right-click on the operator’s name.
- Click on 'Unlock operator login' from the menu.


xxxxxx Picture here xxxxxx



- The next time the operator logs in they need to use their most recent password - if they have requested a new one they will need to use the last password they were sent.

Please note: There will only be one chance to log in correctly before being locked out again. If this happens you will need to go through the same process as above. Once successfully logged in the account is set back to 10 attempts at log in before locking again.


### Deliberate Lock-Out

If you do not want a database operator to access the database for any reason, a system administrator can lock the account. 

- Go to system admin, then under Manage Database Operators choose Add, edit and remove operators.
- In the database operators table, right-click on the operator’s name.
- Click on 'Unlock operator login' from the menu.
- When you would like them to have access again, the system administrator can unlock the account (see above under 'Failed Log-In Attempts').

If the operator will not need to access the database again, for example if they have left your organisation, then it is better to delete their operator log-in. For more on this see XXXXXXXX.


###### core module
