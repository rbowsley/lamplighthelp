# Lamplight help


The base text for the online Lamplight help system.  This text is then 
built on demand for individual customers, so that it is customised 
to their system:
* their language pack is used, so terms used in the text reflect their
system
* modules that are not in use are greyed out


## Overall process for making changes

To add content to the help manual, you will need to

1. clone this repo (once), or make sure your copy is up to date (frequently, pull)
2. make your changes
3. submit a pull request to the `review` branch
4. once changes have been reviewed, they'll be merged into the `master`

A separate build process will then take the text from here and update
customer help files and downloads.

Please make frequent commits - one commit should only have changes to one
page (file).  Reference issues in the commit message (e.g. "Updated
page on adding work records #123").


## Language pack for translations

The current set of terms that may be used and which should be translated 
are [listed](./language.markdown).  If additional ones are needed, you'll
need to speak to Matt.

Terms to be translated will respect the case, so {{Eval}} will be replaced
by Evaluation, and {{eval}} as evaluation.  Plurals should be outside the 
{{placeholder}}s (which is admittedly tricky for things like {{staff}}s).


## Format of a help manual page

Text of help pages is written in markdown (see the [syntax guide](http://daringfireball.net/projects/markdown/syntax))
and then converted to html.

Pages files are currently named `chapter-section-subsection_Page_title.markdown`.  It
won't matter what they're called, but that seems a reasonable convention to follow.

Help pages should use the following format


    # 12.3.4    Page title.

    > An short paragraph giving a summary of the main content of the page.  Be sure to 
    remember the initial '>'.

    The main text of the help page.  This will need to include terms that
    can be translated, like {{Lamplight}}.

    Just keep writing...  Links to other pages should be inserted as links in the normal
    way [12.3.4  Title of the page linked to](/help/index/v/{{version}}/p/12/3/4),
    but including the {{version}} placeholder (for now - see below).

    Images are inserted like this:
    ![Text describing the image, including {{Lamplight}} placeholders]({{imgpath}}123a.png)
    i.e. as markdown images, but include an {{imgpath}} placeholder (for now, anyway).

    At the end, please put a tag that describes which module the page relates to.

    ###### core|eval|comms|charge|costs|datadirect|library|publish|staff|waiting module


## Images

Images (screenshots) should be added to the img/ directory.  The number of an image 
no longer relates to anything (you can call them anything), but the letter (e.g. 123a.png)
was incremented within a single page of the manual - so 123a.png, 123b.png and 123c.png 
would all be expected to be on the same page.


## Versions

There are currently two versions of the base text for the help manual - v0 and v1.
There could be more, and different customers can use different versions as their
base before it's translated.  Currently, v0 is used for all customers except for
VIP Online, which uses v1.  In principle, though, it'd be possible to add your
own version number and build from there.  

But in short, edit the v0 files.  Also, edit the markdown, not the html which is there
at the moment - that was included for reference following the initial setup of this
github approach to things, but will be removed in due course.

The other kind of version is that version that's actually deployed, and is the number
in the /v/123/ part of the help manual urls and the {{version}} placeholders that
need to be in the urls.

This kind of version should disappear, but we'll need to keep it in links for now.

The other linkey placeholder is the {{imgpath}}, which can also vary for different 
customers to enable use of different image sets.


## Licence 


<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_GB"><img alt="Creative Commons Licence" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Lamplight Database help manual text</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/mattparker/lamplighthelp" property="cc:attributionName" rel="cc:attributionURL">Lamplight Database Systems Limited</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_GB">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.