# Help for add-firewall-rules.ps1 PowerShell Script

## Synopsis & Description
```powershell
add-firewall-rules.ps1 [<path-to-executables>]
```

Adds firewall rules for the given executables (needs administrator rights).

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/add-firewall-rules.ps1 [[-PathToExecutables] <String>] [<CommonParameters>]
```

```
-PathToExecutables <String>
    
    Required?                    false
    Position?                    1
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
PS>.\add-firewall-rules.ps1 C:\MyApp\bin
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated from comment-based help of add-firewall-rules.ps1 by convert-ps2md.ps1*