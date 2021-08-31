# Help for list-latest-tag.ps1 PowerShell Script

## Synopsis & Description
```powershell
list-latest-tag.ps1 [<repo-dir>]
```

Lists the latest tag on the current branch in a Git repository.

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/list-latest-tag.ps1 [[-RepoDir] <String>] [<CommonParameters>]
```

```
-RepoDir <String>
    
    Required?                    false
    Position?                    1
    Default value                "$PWD"
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
PS>.\list-latest-tag.ps1 C:\MyRepo
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated from comment-based help of list-latest-tag.ps1 by convert-ps2md.ps1*