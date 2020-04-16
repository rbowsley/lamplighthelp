# 21.1.4 List of all Word template merge tags

> Merge tags in Word Templates are replaced with information from profiles and {{activity}} records.  This is the list of all the tags you can use.

These are the mail merge tags you can use in Word templates.  They are all case-senstive and need to be entered into your templates exactly as they appear here.  Ignore any translations in your system (e.g. you have 'House number' instead of 'Address line 1' on the contact details tab of a profile, you need to use 'Address line 1' in your templates.

### Profile tags - name and contact details

| Field | Tag |
| :--- | :--- |
| Title | ${Title} |
| First name | ${First name} |
| First name initial | ${First name initial} |
| Middle name | ${Middle name} |
| Middle name initial | ${Middle name initial} |
| Surname | ${Surname} |
| Surname initial | ${Surname initial} |
| Suffix | ${Suffix} |
| Organisation name | ${Organisation name} |
| Organisation name if available | ${Organisation name if available} |
| Address line 1 | ${Address line 1} |
| Address line 2 | ${Address line 2} |
| Address line 3 | ${Address line 3} |
| Address line 4 | ${Address line 4} |
| Address line 5 | ${Address line 5} |
| Postcode | ${Postcode} |
| Phone | ${Phone} |
| Mobile | ${Mobile} |
| Email | ${Email} |
| Web | ${Web} |
| ID | ${bodyid} |


### Linked (related) profile tags

You can use the tags above to add information from a linked profile (where two profiles appear in one line of the recipients table) by inserting the word 'Linked' into the tag name.

| Field from linked profile | Tag |
| :--- | :--- |
| Title | ${Linked Title} |
| First name | ${Linked First name} |
| First name initial | ${Linked First name initial} |
| Middle name | ${Linked Middle name} |
| Middle name initial | ${Linked Middle name initial} |
| Surname | ${Linked Surname} |
| Surname initial | ${Linked Surname initial} |
| Suffix | ${Linked Suffix} |
| Organisation name | ${Linked Organisation name} |
| Organisation name if available | ${Linked Organisation name if available} |
| Address line 1 | ${Linked Address line 1} |
| Address line 2 | ${Linked Address line 2} |
| Address line 3 | ${Linked Address line 3} |
| Address line 4 | ${Linked Address line 4} |
| Address line 5 | ${Linked Address line 5} |
| Postcode | ${Linked Postcode} |
| Phone | ${Linked Phone} |
| Mobile | ${Linked Mobile} |
| Email | ${Linked Email} |
| Web | ${Linked Web} |


### Operator profile tags

You can use the tags below to add information from the profile of the operator creating the {{comm}}:

| Field from profile | Tag |
| :--- | :--- |
| Title | ${me|Title} |
| First name | ${me|First name} |
| First name initial | ${me|First name initial} |
| Middle name | ${me|Middle name} |
| Middle name initial | ${me|Middle name initial} |
| Surname | ${me|Surname} |
| Surname initial | ${me|Surname initial} |
| Suffix | ${me|Suffix} |
| Organisation name | ${me|Organisation name} |
| Organisation name if available | ${me|Organisation name if available} |
| Address line 1 | ${me|Address line 1} |
| Address line 2 | ${me|Address line 2} |
| Address line 3 | ${me|Address line 3} |
| Address line 4 | ${me|Address line 4} |
| Address line 5 | ${me|Address line 5} |
| Postcode | ${me|Postcode} |
| Phone | ${me|Phone} |
| Mobile | ${me|Mobile} |
| Email | ${me|Email} |
| Web | ${me|Web} |



### Special tags

${today} will insert today's date in the form '1st March 2020'

${repeat_template} (your template here) ${/repeat_template} will create a copy of (your template here) for each recipient, merged appropriately.

${repeat_row} at the start of a table row will repeat that row for each recipient of the {{comm}}, with merge tags in the rest of the row merged from the profile.


### Custom profile fields

Data from the recipient custom profile fields can be inserted by typing the field name in the merge tag.  So the tag for the field 'Gender' in your system would be ${Gender}.

The spelling and capitalisation has to be exactly as it appears in your system and if you have any difficulties we recommend that you download the settings from your system, which gives you field names in an Excel spreadsheet you can copy and paste from.

Note that if you have any custom fields with the same names as any of the built-in fields in this page you will get unpredictable results.  Please edit your custom field names slightly to avoid these conflicts.


### {{Work}} record tags


| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| Summary | ${description} | (just the text that appears in the record) |
| Description | ${description} | (just the text that appears in the record) |
| Follow up | ${followup} | (just the text that appears in the record) |


### {{Referral}} record tags


| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| {{Referral}} reason | ${referral reason} | (just the text that appears in the record) |
| {{Referral}} notes | ${referral notes} | (just the text that appears in the record) |
| Appointment date | ${appointment date} | 14/04/2020 |

### {{Grant}} record tags


| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| Summary | ${description} | (just the text that appears in the record) |
| Description | ${description} | (just the text that appears in the record) |
| Monitoring | ${monitoring} | (just the text that appears in the record) |
| Amount | ${amount} | 150 |
| {{Grant}} type | ${grant type} | Capital |
| Approval date | ${approval date} | 18/04/2020 |

