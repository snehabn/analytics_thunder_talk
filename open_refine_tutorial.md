### Getting started with OpenRefine
* Install 'JAVA RVE'
* Download & Install 'Open Refine'

### Set up Tutorial
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

* __Step 6: Split columns into several columns__
  * (Edit Column --> Split into several columns)

* __Step 7: Custom text transforms__
  * example: `if(cells("Is Winner").value, value + " (winner) ", value)`

* __Step 8: Export the data__
  * TSV, CSV, HTML table, Excel, ODF spreadsheet, etc..
  * For templating, default is json

## Data Cleanup

* __Clustering and Editing Columns in Bulk__
  * Clustering --> cluster the groups and mass edit.
  * (Facet --> Text Facet --> in sidebar, click on 'Cluster')
  *


### Helpful Commands
* `value.replace("to_be_replaced", "replaced_with")`
* `value.startsWith("str")`
* `value[1,n]` --> character range
* `value.substring(index_number)`
