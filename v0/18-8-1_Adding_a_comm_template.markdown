# 18.8.1    Adding a {{comm}} template

> To add a {{comm}} template, right-click on the table or use the menu button and select 'Add new'. 

A popup window will appear.

![Adding a new template]({{imgpath}}154a.png)

Enter the name of the template (this is what will appear on the drop-down menus), and then set up the template using the rich text editor.

Templates can include normal text, formatted as you wish. They can also include images from the image library (see section [18.9.0  {{Comm}}s module image library](/help/index/v/{{version}}/p/18.9.0) ) And you can also add mail merge fields (see section [4.4.2  Mail merge, templates and images](/help/index/v/{{version}}/p/4.4.2) ).

In addition, templates can also include other templates. So, for example, you could create a 'letterhead' template. You could then create a standard 'reminder letter' template that would include the 'letterhead' template at the start. This means that you only need to set up the letterhead once, and you can then re-use it in other templates as much as you want.

Be careful not to create circular references in your templates. If one template includes a second, then make sure the second template doesn't in turn use the first! If {{Lamplight}} finds circular references it will stop processing them and the results may not be as you expected.

When you have finished, click the 'save' button in the bottom right hand corner. This template will now be available when creating other templates and when creating {{comm}}s.

Templates are available to all {{project}}s. 

###### comms module

