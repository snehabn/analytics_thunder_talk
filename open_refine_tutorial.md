### Getting started
* Install 'JAVA RVE'
* Download & Install 'Open Refine'

### Tutorial
* Step 1: Select/Import a Data Source in the following formats:
** csv, json, from clipboard, from url, from Google Data

* Step 2: Set import options
** (Uncheck split into columns default)
** If no header-lines: set # header-lines to zero

* Step 3: Start filtering your data
** Remove unnecessary lines from data (empty rows, irrelevant titles, etc...)
** (column --> Text-filter --> all drop down --> Edit Rows --> Remove all matching rows --> remove text filter)

* step 4: Transform cell content
** Remove unnecessary content (quotes, styling elements, etc…)
** (Edit cells --> Transform --> [General Refine Expression Language](https://github.com/OpenRefine/OpenRefine/wiki/General-Refine-Expression-Language) `value.replace("'''", "")` --> gives a preview of transformed column )

* Step 5: Add columns based on existing columns
** (Edit column --> Add column based on this column...--> )

### Helpful Commands
*
Create column based on this column
*
