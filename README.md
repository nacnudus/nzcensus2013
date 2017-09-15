# nzcensus2013

The `nzcensus2013` R package contains a single dataset, `nzcensus2013`, of all
the data in the [spreadsheet
file](http://www.stats.govt.nz/Census/2013-census/data-tables/electorate-tables.aspx)
of summary statistics from the 2013 New Zealand Census, published by Statistics
New Zealand.

This package is not associated with the New Zealand government.

The data was extracted from the spreadsheet by using the
[tidyxl](https://nacnudus.github.io/tidyxl) and
[unpivotr](https://nacnudus.github.io/unpivotr) packages, after first converting
the `.xls` file to the `.xlsx` format.  See the script `data-raw/extract.R`.

Other New Zealand dataset by the same author:

* [nzpullover](https://nacnudus.github.io/nzpullover) -- road policing
  statistics, updated quarterly.
* [nzbabynames](https://github.com/nacnudus/nzbabynames) --  the top 100 baby
  names annually since 1954, and annual birth statistics.