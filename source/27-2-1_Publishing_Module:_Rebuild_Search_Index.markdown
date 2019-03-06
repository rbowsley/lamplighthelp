# 27.2.1    Publishing Module: Rebuilding Search Indexes

> When you publish a particular profile or {{work}} record, {{Lamplight}} builds a searchable index from that record

The searchable index is used by the text searches in the Publishing Module, and is updated whenever you edit a published profile or {{work}} record. However, if you change the fields that can be published in {{Lamplight}}'s system administration, these indexes will need to be rebuilt so that the data from the correct fields are included in the index. This is particularly important if you are removing fields that have previously been published.

Depending on the number of records involved, it can take a little while for {{Lamplight}} to rebuild. And because {{Lamplight}} won't know when you've finished making all the changes you want to, you'll need to tell it when you need to rebuild these search indexes.

To do this:
- Go to Admin -> System administration
- Click on "rebuild publishing search index - {{people}} and Orgs" or "rebuilding publishing search index - {{work}}", (which index needs updating will depend on whether you have made changes to profile settings or those for {{work}} records).
- {{Lamplight}} will rebuild the index and give you a confirmation {{message}} when complete. This tells you how many have been updated. 


###### publish module

