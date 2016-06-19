### Getting started
* Install 'JAVA RVE'
* Download & Install 'Open Refine'

### Tutorial
* __Step 1: Select/Import a Data Source in the following formats:__
  * csv, json, from clipboard, from url, from Google Data

* __Step 2: Set import options__
  * (Uncheck split into columns default)
  * If no header-lines: set # header-lines to zero

* __Step 3: Start filtering your data__
  * Remove unnecessary lines from data (empty rows, irrelevant titles, etc...)
  * (column --> Text-filter --> all drop down --> Edit Rows --> Remove all matching rows --> remove text filter)

* __Step 4: Transform cell content__
  * Remove unnecessary content (quotes, styling elements, etc…)
  * (Edit cells --> Transform --> [General Refine Expression Language](https://github.com/OpenRefine/OpenRefine/wiki/General-Refine-Expression-Language) `value.replace("'''", "")` --> gives a preview of transformed column )

* __Step 5: Add columns based on existing columns__
  * (Edit column --> Add column based on this column...--> )

### Helpful Commands

