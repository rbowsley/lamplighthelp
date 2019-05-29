# 13.6.0 {{Linked Case}} {{Report}}s

> {{Linked case}} {{report}}s provide a summary of records in {{linked case}}s, and you can filter to show open and closed {{linked case}}s within any time period

The {{linked case}} {{report}} can list the open and/or closed cases, showing how many records are associated with them in the period. It can also aggregate data across {{linked case}}s. If the {{linked case}} data is combined, it can be presented using profile information, for example.

### Running a {{Report}}

To run a {{linked case}} {{report}}:

- On the main menu click '{{report}}s -> more -> {{linked case}} {{report}}'.
- You will come to the '{{Report}} filters' screen:

![{{Linked Case}} {{Report}} Filters](13.6.0a.png)

- Most of the filters are the same as for other reports (see [13.1.1 {{Report}} Filters](/help/index/p/13.1.1)).
- At the bottom you have specific filters for your {{linked case}} report for {{referral}} success and direction. These are custom fields and will be different for each organisation. In our system they are '{{Linked Case}} type', 'Level of support' and 'On completion'. What you see here will reflect your organisation's processes. 
- If you do not choose anything from these fields, then your {{report}} will return all information. It is only when you pick an option that {{Lamplight}} filters the information it returns. 

### {{Report}} Presentation

![{{Linked Case}} {{Report}} Presentation](13.6.0b.png)

**How Should Dates Be Handled?**

{{Linked case}}s involve a start and end date for each one, so you can choose here how you want {{Lamplight}} to handle your date filters on the first page. These options are additional filters, which will narrow down your results.
- Include {{linked case}}s that were open during the period. When you choose this option, {{Lamplight}} will include data on {{linked case}}s that were open at any point between your 'Date from' and 'Date to' on the first tab. It does not matter whether they were open the whole time, opened half way through, or closed before the end of the period specified.
- Include only {{linked case}}s that were opened during the period. This will filter out {{linked case}}s that were already open before your 'Date from', even if they were open during the time you specified.
- Include only {{linked case}}s that were closed during the period. When you choose this option, {{Lamplight}} includes {{linked case}}s which were closed in your time period, regardless of then they were opened. They could have been opened before the 'Date from', or they could also have been opened between your 'Date from' and 'Date to'.

**How Should Rows Be Grouped?**

- The options in this drop-down come from your {{linked case}} categories as well as profile information. 
- If you choose one of these, {{Lamplight}} will display the information in additional table rows.  In the example below, we chose our custom 'Hair colour' field.

![{{Linked Case}} {{Report}} Presentation](13.6.0c.png)


### The {{Report}} Results

**Aggregated {{Linked Case}} {{Report}}**

If you run a {{report}} which collates your {{linked case}} data across the timescale that you have chosen, it will show you:

![{{Linked Case}} {{Report}} table](13.6.0d.png)

- Number of {{linked cases}} open at any time in the timescale chosen.
- Number of new {{linked case}}s opened.
- Number of {{linked case}}s that were closed during the period.
- Number of {{activity}} records (including {{work}}, {{referral}}, {{outcome}} etc.) attached to any of the {{linked case}}s.

**Individual {{Linked Case}} {{Report}}**

If you choose to group your rows 'by {{linked case}}' in the '{{Report}} Presentation' tab, then the table will show each {{linked case}} that fits your filter criteria in a separate row. The report below is for {{linked case}}s which were opened between 1st January and 30th April 2019.

![{{Linked Case}} {{Report}} table](13.6.0e.png)

The {{report}} shows:
- {{Linked case}} name.
- Date the {{linked case}} was opened.
- Whether the {{linked case}} is open or closed at the time you are running the {{report}}.
- The date the {{linked case}} was closed, if applicable.
- The total length to of time up to now in weekdays that the {{linked case}} has been/was open. This does not count weekends.
- The total lenght of time up to now, including weekends, that the {{linked case}} has been/was open.
- The total amount of time spent on this {{linked case}}. This will look at **all** the records attached to each {{linked case}} (not just those in the time period specified for the {{report}}) and total up the time they have taken.
- Number of {{activity}} records (including {{work}}, {{outcome}}, {{referral}} etc.) attached to each {{linked case}} in the time period.


###### core module
