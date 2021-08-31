# Help for download-dir.ps1 PowerShell Script

## Synopsis & Description
```powershell
download-dir.ps1 [<URL>]
```

Downloads a directory tree from the given URL.

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/download-dir.ps1 [[-URL] <String>] [<CommonParameters>]
```

```
-URL <String>
    
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
PS>.\download-dir.ps1 "https://www.cnn.com"
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated from comment-based help of download-dir.ps1 by convert-ps2md.ps1*