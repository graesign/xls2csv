# Convert E Mobility - XLS2CSV
* Author Graeham Blank <graeham@gravitee.nl>

### Usage: xls2csv.py [options] infile [outfile]
## Change line 60 to change the heading columns names of the sheets like: Volume to Charge point ID

Example:
./xls2csv.py --delimiter=';' input/Alfen_01_2014_03_2015.xls > output/test4.csv


Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -s SHEETID, --sheet=SHEETID
                        sheet no to convert (0 for all sheets)
  -d DELIMITER, --delimiter=DELIMITER
                        delimiter - csv columns delimiter, 'tab' or 'x09' for
                        tab (comma is default)
  -p SHEETDELIMITER, --sheetdelimiter=SHEETDELIMITER
                        sheets delimiter used to separate sheets, pass '' if
                        you don't want delimiters (default '--------')
  -e ENCODING, --encoding=ENCODING
                        xls file encoding if the CODEPAGE record is missing
