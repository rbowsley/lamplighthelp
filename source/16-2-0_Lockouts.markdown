#  16.2.0 Lockouts

> If a database operator has tried to log in to their account 10 times without success the account will be locked. 

Failed attempts to access {{Lamplight}} don't have to be all at once, so they can be across a number of sessions, days or weeks. 

They'll see this message:







A system administrator will need to unlock the account. 

To do this:
- Go to system admin, then under Manage Database Operators choose Add, edit and remove operators.
- In the database operators table, right-click on the operator’s name.
- Click on 'Unlock operator login' from the menu.






The next time the operator logs in they need to use their most recent password - if they have requested a new one they will need to use the last password they were sent.

Please note: There will only be one chance to log in correctly before being locked out again. If this happens you will need to go through the same process as above. Once successfully logged in the account is set back to 10 attempts at log in before locking again.


###### core module
