# 28.0.0 The Publishing Module

> The Publishing Module adds the ability to connect a website or application to Lamplight using your Lamplight API



If you use the Publishing Module you can link information entered in Lamplight to your public website.  For example, you might want:

- A staff directory, pulled from the staffing information in Lamplight.
- A directory of local voluntary organisations (especially for CVSs and the like).
- A searchable directory of local services for people seeking support.
- A ‘what’s on’ listing of forthcoming events.

You choose what records and information to publish, so you are in full control of your data.  You also decide exactly how you want to present it on your website – we just link you to the data.

In addition you can, if you want, accept data into Lamplight.  For example, you can allow people to refer themselves through your website, book on forthcoming events, or update their profile information.

Different organisations use the publishing module in very different ways, and want it to look and feel like the rest of your public-facing website.  The publishing module is designed to enable this: your website uses the Lamplight API to request the information you need, and present it however you want.  To use it you will need a programmer to set up your website to do this: they will need to understand how to request the data, what form it is returned in, how your {{Lamplight}} system is set up, and want you need to achieve.  

Assuming the correct permissions and setup, the types of data that can be manipulated through the API is:

| Record type | View | Edit | Add new |
| :---------  | :---------- | :---------- | :-------- |
| {{Work}}    | Yes (date /time; workarea; summary; description, but not attendance) | Yes - adding attendees | No |
| {{Referral}} | No | No | Yes (accepting referrals via a website) |
| Profile | Yes - name, contact details, custom fields | Yes - name, contact details, custom fields | Yes |
| {{Workarea}} | Yes | No | No |


We’ve set up a whole website, [http://www.lamplight-publishing.co.uk/](http://www.lamplight-publishing.co.uk/), which gives some working examples and documentation to show how it works.  It’s aimed at developers and other technical types to show how to get the data out of Lamplight and on to your website.  It goes into full detail about what can and what cannot be done with the module.  

You will need a developer to add the Lamplight information to your website.  We strongly recommend that you and your developer review the [publishing website](http://www.lamplight-publishing.co.uk/) to confirm that you will be able to achieve what you need to with the module.


###### publish module

