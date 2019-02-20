#  16.5.5 Login Security Policies

> Login security policies limit when and from where operators may log in

Login security policies relate to the IP addresses that {{Lamplight}} can be accessed from, and the times at which it can be accessed. For example, you might have a policy that only allows logging in on weekday mornings, and another that allows logging in from the office network, Monday to Friday. Different database operators can have different login security policies applied.

**Creating a Login Security Policy**

- Click ‘admin’ in the main menu, then ‘system administration’
- In the ‘Manage database operators’ section, click ‘Set up login security policies’.
- You will see a screen like this:





- Click the ‘add new’ button.
- Give your login security policy a name.
- If you have static IP addresses and want to restrict access to Lamplight to the ones you specify, you can enter multiple addresses here, on different rows. 
- You can set days and times for the policy (times used are GMT/BST).

**Appying a Login Security Policy

- Click ‘admin’ in the main menu, then ‘system administration’.
- In the ‘Manage database operators’ section, click ‘Add, edit and remove database operators’.
- Find the database operator you want to apply the policy to in the table and access the contextual menu by right-clicking anywhere in the row (or left-clicking the menu button in the left-hand column).
- Click ‘Edit’.
- At the bottom of the popup window, select the login security policy to apply.
- An operator trying to log in at a time, or from an IP address, that is not allowed will see a message saying that they cannot log in at present. 


###### core module
