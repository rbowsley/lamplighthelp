# 26.4.0 Matching Module - Matching {{volunteering application}} and {{volunteering opportunity}} records

> {{Lamplight}} will find the best matches for {{volunteering opportunity}} and {{volunteering application}} records

{{Volunteering application}} and {{volunteering opportunity}} records each have a location; times (availability); and soem categorisation about what they involve.  These characteristics can be used to find appropriate matches from one to the other.

You can match {{volunteering application}}s to {{volunteering opportunity}} records; or the other way round.  {{Lamplight}} will calculate an overall match score and show you the best matches in order.

### How to match

Find the record that you want to find matches for.  You can find these in the profiles of those involved, or from the main menu: {{activity}} > view > {{volunteering application}} (or {{volunteering opportunity}}.  [Use the search filters](/help/index/p/26.3.0) to find the record you need, and right-click (or click the small 'menu' button) to bring up the context menu:

![{{Volunteering opportunity}} context menu](26.3.0c.PNG)

For the sake of explanation we'll assume that we are looking at {{volunteering opportunity}} records, and seeking {{volunteering application}} records that match.  You can match in the other direction and it works in just the same way.

#### Match on all criteria

This will search for records that are near to the address; have some crossover in availability; and have most interests in common.

#### Match nearby

This will show records in order of distance, but ignore other factors.  Distance is calculated as the crow flies, using the latitude and longitude of the postcodes of the profiles linked to the {{volunteering application}} and {{volunteering opportunity}}.

#### Match by interests

This will show records by how many interests the {{volunteering application}}s have in common with the {{volunteering opportunity}}.

Interests are the category selectors, which by default are labelled 'interests', 'topics', 'requirements', 'ideal for', and 'skills gained' (although these may be different in your system).

#### Match availability

This will only look for records that have some availability overlap.  If start and end dates are specified they will be used, as well as whether there are any time slots shared by the {{volunteering application}} and {{volunteering opportunity}}.  Records with more common time slots will be ranked higher.


### Using the matched records

When you run a match (using any of the options above) you will see a summary of the {{volunteering opportunity}} that you are seeking matches for, and then summaries of each {{volunteering application}} that matches:

![Showing matches](26.4.0a.PNG)

From here you can review the possible matches.  The bottom half of the window has a scrollbar to scroll down through the matching records: the best matches are shown at the top.  If you wish to match a {{volunteering application}} to the {{volunteering opportunity}}, click the 'Add to the opportunity' button on the {{volunteering application}} in question.

When you do so, the {{volunteering applicant}} will be added to the {{volunteering opportunity}} attendance table.


###### match module
