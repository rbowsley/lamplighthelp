# 32.3.0 Overview of the types of Map available in CodeSets

> There are several types of Report CodeSet Map, depending on the type of data in that field

The types of CodeSet map available are:

### Constant Value Map

A Constant Value map simply replaces data in a column with the same value in every row.  It's the simplest type of map
and can be used to blank out data, or create a column with a reference ID for your organisation.

### Original Data Value Map

An original data value map keeps the data you have, either exactly as it is, or with some fixed text added to the start
or end.  This can be useful if you just need to change the column header, or if you need to add an organisation
prefix or suffix to IDs.

### Date Format Map

Date format maps re-format date fields in the way that you select, so that 28/07/2022 could become '2022-07-28' or
'28th July 2022' or simply 'July'.

### Numeric range Map

Numeric fields can be mapped to ranges: age bands are the most frequent use of this.

### Single Option Map

A single option map will switch drop-down type fields, such as a typical gender field, or {{workarea}}.  You specify
what each option available should be translated to.

### Multi Option Map

A Multi Option map can be used when a data cell can include multiple values in one cell.  Sometimes this maybe because
the data is a multi-select field (e.g. 'Languages spoken'), at other times because the data is combined into a single 
cell (e.g. attendance roles).  The data in the cell will be split up and translated one part at a time.  So
"English, Spanish" might become "EN, SPA", for example.

### Text search Map

A text search map can look for a particular set of phrases, and if it finds it will replace the data in the cell.
For example, a text search map could look for the word 'happy' in the data and just display '+1' if it finds it;
and then look for 'sad' in the data, and just display '-1'.  This can be useful for attendance  types amongst others.


The following pages describe how to set these up in more detail and some of the issues to be aware of with them.


###### codeset module