# Read-Office-XML-into-PostgreSQL-table
## Import into Postgres directly from SpreadsheetML format w/o CSV use  

![Save workbook as Office XML](https://github.com/stefanov-sm/Read-Office-XML-into-PostgreSQL-table/blob/848070a33e5949484893ec90757830540ff62d0d/saveas.png)

- Checks the risk of data distortion by the CSV generation as it may depend on regional settings.   
- May be ported to other RDBMS that support SQL-standard XMLTABLE.  
- `usage.sql` is a working example that uses `ecb.xlsx` spreadsheet.  

XLS[X] to XML conversion scripts and sample files in [convert](https://github.com/stefanov-sm/Read-Office-XML-into-PostgreSQL-table/tree/main/convert) folder.  
Example CLI usage: `cscript xlsx2xml.wsf <input xls[x] file full name> <output xml file full name>`
