# MSSQL-audit-scripts

PowerShell script to audit MSSQL servers against CIS Benchmark. This script has currently been tested on MSSQL 2012, 2016 and 2019.

````
.\MSSQL_Audit_Script.ps1 -Server "Servername" -Include "CIS" -WindowsAuthentication
````

Then go through the HTML report and check the CIS benchmark controls. 

You may use the provided XLSX file to document your control results.

![image](https://github.com/Haxxnet/MSSQL-audit-scripts/assets/21357789/71c2708f-4a6f-402f-8a47-9e6472eeafd0)

![image](https://github.com/Haxxnet/MSSQL-audit-scripts/assets/21357789/dec569e3-d503-4ed1-855f-922b9201f60d)
