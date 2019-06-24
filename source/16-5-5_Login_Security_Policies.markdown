#  16.5.5 Login Security Policies

> Login security policies limit when and from where operators may log in

Login security policies relate to the IP addresses that {{Lamplight}} can be accessed from, and the times at which it can be accessed. For example, you might have a policy that only allows logging in on weekday mornings, and another that allows logging in from the office network, Monday to Friday. Different database operators can have different login security policies applied.

**Creating a Login Security Policy**

- Go to ‘admin -> system administration -> Database Operators and Security -> Set up login security policies’.
- You will see a screen like this:

[Log-in Security Policies](16.5.5a.png)

- Any policies that you already have will be at the top of the page (so in the example above we just have one - 'Main Office Mon-Wed).
- Click the ‘add new’ button at the bottom.
- Give your login security policy a name.
- If you have static IP addresses and want to restrict access to Lamplight to the ones you specify, you can enter multiple addresses in the 'Ip addresses to allow access from' box. Each one should be on a different row.  
- If you want to restrict operator access to specific days and times you can use the boxes underneath (times used are GMT/BST).

**Appying a Login Security Policy**

- Go to ‘admin -> system administration -> Database Operators and Security -> Manage database operators'.
- Find the database operator you want to apply the policy to in the table.
- Right-click anywhere in their row or left-click the menu button in the left-hand column.
- From the pop-up menu choose ‘Edit’.
- In the next pop-up window, select the login security policy to apply from the drop-down list.

[Applying a Log-in Security Policy](16.5.5b.png)

- An operator trying to log in at a time, or from an IP address, that is not allowed will see a message saying that they cannot log in at present. 

[Lockout Message](16.5.5c.png)

Why not watch our video demonstration? (Please note, the layout of the system administration page has changed since this video was recorded, but the process is the same).

<iframe src="https://player.vimeo.com/video/293151730" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>


##### Tags
Advanced topics
System admin

###### core module
