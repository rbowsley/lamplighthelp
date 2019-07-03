# 16.7.1 Which Custom Fields to Choose in Profiles

> It is important to think about what type of field you need - if it is just for qualitative information, or whether it is something that you will need to use for reporting in the future

The choice of fields that can be added is the same wherever you are  putting them. When making a decision on which field to choose, think carefully about not only what information you would like to capture, but also how you will need to report on it. You can run a {{report}} using the information in a drop-down list, for example, but while a free-text field is good for storing qualitative information, you will not be able to use it in {{report}}s or {{group}}s.

**Reporting on Custom Fields**

There are a number of different ways in which custom fields in profiles can be used for reporting. Depending on the type of field that you choose you will be able to:

- Use it for presenting {{report}}s: this allows you to show columns in a {{report}} using this field. If you have a demographic field, for example gender, you could run a report on the number of {{work}} sessions you've had in the last six months, and then choose to present it by your 'Gender' field. This would then give you a column or row for each of the options in that field so that you could see the results for each different group at a glance. (For more on this see [13.1.4 {{Report}} Presentation](/help/index/13/1/4).)
- For creating {{group}}s: again, using the above field example you can create an auto {{group}} with gender as a filter. (For more on this see [11.1.3 Groups: {{Work}}, {{Referral}} and {{Grant}} Fields](/help/index/p/11.1.3)).
- Add as a column or filter records in a table: you can view tables of records from the main menu (to find out more please see [7.3.0 Viewing All {{Work}} Records](/help/index/p/7.3.0)). In this example, you could use the search bar above the table to add in a column for each of the options.
There are a number of different ways in which custom fields in profiles can be used for reporting. 

The table below gives details for each type of field. 


| Field name | Description |For Filtering {{Feport}}s | For Presenting {{Report}}s | For Creating {{Group}}s | As a {{Group}} Data View Column |
| :--------- | :---------- | :------------------- | :--------------------- | :---------------------- | :----------------------------- |
| Select box | A drop-down list of options which operators will be able to choose one of | Yes | Yes | Yes | Yes |
| Multi-select box | A drop-down list of options from which operators select as many as apply | Yes | Yes | Yes | Yes| 
| Plain text area | A field for a short amount of free text | No | No | Yes | Yes |
| Plain text box | A larger box for longer amounts of free text | No | No | Yes | Yes |
| Rich text | A free text box to which formatting can be added | No | No | Yes | Yes |
| Check box | A single box which can be clicked to fill in a tick | No | Yes | Yes | Yes |
| Radio button | A single button - operators can click on the button to indicate a yes. Once clicked it cannot be deselected | No | Yes | Yes | Yes |
| Dates | Dates are entered in UK format by selecting from the day/month/year select boxes or using the popup calendar | No | Yes | Yes | Yes |
| Date/Times | Dates and times are entered on a 24-hour clock from select boxes | No | No | Yes | Yes |
|Date of birth selector | Dates are entered in UK format by selecting from the day/month/year select boxes and a current age is displayed | No | Yes | Yes | Yes |
| Number box | Enter numbers only into a small text box | No | Yes | Yes | Yes |
| Caption | To add a label for instructions or sub headings | No | No | No | No |
| Fixed text box | Descriptive text that cannot be altered - useful for adding descriptive text or reminders about the other information on the tab | No | No | No | No |
| Year selector | Choose just the year from a drop-down | No | Yes | Yes | Yes |
| Radio buttons | Select one from a range of options | No | Yes | Yes | Yes |
| Checkboxes | Select multiple options using tick boxes | No | Yes | Yes | Yes |
| Charity number lookup | enter a Charity Commission registered number and Lamplight will add a link to their page on the Charity Commission website | NO | No | Yes | Yes |
| Twitter name | A text box that will let you look up their recent tweets | No | No | Yes | Yes |
| Web address | For additional websites - also providing a link to the site | No | Yes | Yes | Yes |


**What Will This Look Like in My System?**

![Single Select Fields](16.7.1a.png)

![Multi Select Fields](16.7.1b.png)

![Specific Data Type Fields](16.7.1c.png)

![Text Fields](16.7.1d.png)

![Titles and Explanations](16.7.1e.png)

**Linked Fields**

Linked fields are useful for saving information that you will view through the profile. You will not be able to use them in {{report}}s, {{groups}} or {{group}} data views.

Most of the time your fields will have a single value that doesn't change (unless you enter an incorrect value by mistake). For example, a person only has one date of birth, and this will never change. In some other cases you may need to be able to enter multiple records under a particular field. For example, you may need to be able to enter multiple text entries describing medical conditions as a person's medical condition changes. You may also need to be able to {{group}} a set of records together - in this example you may need a 'date diagnosed' field, a 'description of condition' field, and a medication 'field', all linked together. On the profile, this would be displayed as a table:

![Linked Fields](16.7.1f.png)


##### Tags
System admin
Advanced topics

###### core module
