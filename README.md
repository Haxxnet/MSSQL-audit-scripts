# MSSQL-audit-scripts

Scripts that can be used when auditing a MSSQL Server.

This script has currently been tested on MSSQL 2012, 2016 and 2019.

````
.\MSSQL_Audit_Script.ps1 -Server "Servername" -Include "CIS" -WindowsAuthentication
````

Then go through the HTML report and check the CIS benchmark controls. 

You may use the provided XLSX file to document your control results.
