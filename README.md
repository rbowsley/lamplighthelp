# Lamplight help


The base text for the online Lamplight help system.  This text is then 
built on demand for individual customers, so that it is customised 
to their system:
* their language pack is used, so terms used in the text reflect their
system
* modules that are not in use are greyed out


## Overall process for making changes

To add content to the help manual, you will need to

1. clone this repo (once), or make sure your copy is up to date (pull)
2. make your changes
3. submit a pull request to the `review` branch
4. once changes have been reviewed, they'll be merged into the `master`

A separate build process will then take the text from here and update
customer help files and downloads.


## Language pack for tranlsations

The current set of terms that may be used and which should be translated 
are [listed](./language.markdown).  If additional ones are needed, you'll
need to speak to Matt.

Terms to be translated will respect the case, so {{Eval}} will be replaced
by Evaluation, and {{eval}} as evaluation.  Plurals should be outside the 
{{placeholders}} (which is admittedly tricky for things like {{staff}}s).


## Format of a help manual page

Text of help pages is written in markdown [syntax guide](http://daringfireball.net/projects/markdown/syntax)
and then converted to html.

Help pages should use the following format

    # 12.3.4    Page title

    > An short paragraph giving a summary of the main content of the page.

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
