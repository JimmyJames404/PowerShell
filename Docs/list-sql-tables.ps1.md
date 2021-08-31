# Help for list-sql-tables.ps1 PowerShell Script

## Synopsis & Description
```powershell
list-sql-tables.ps1
```

Lists all tables in a SQL server database and exports the list as CSV.
Install-Module InvokeQuery
Run the above command if you do not have this module.

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/list-sql-tables.ps1 [-server] <Object> [-database] <Object> [-username] <Object> [-password] <Object> [<CommonParameters>]
```

```
-server <Object>
    
    Required?                    true
    Position?                    1
    Default value                
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
-database <Object>
    
    Required?                    true
    Position?                    2
    Default value                
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
-username <Object>
    
    Required?                    true
    Position?                    3
    Default value                
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
-password <Object>
    
    Required?                    true
    Position?                    4
    Default value                
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
[<CommonParameters>]
    This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, WarningAction, 
    WarningVariable, OutBuffer, PipelineVariable, and OutVariable.
```

## Example
```powershell
PS>.\list-sql-tables.ps1
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated from comment-based help of list-sql-tables.ps1 by convert-ps2md.ps1*