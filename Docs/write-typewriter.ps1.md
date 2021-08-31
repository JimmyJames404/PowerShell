# Help for write-typewriter.ps1 PowerShell Script

## Synopsis & Description
```powershell
write-typewriter.ps1 [<text>] [<speed>]
```

Writes the given text with the typewriter effect.

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/write-typewriter.ps1 [[-Text] <String>] [[-Speed] <Int32>] [<CommonParameters>]
```

```
-Text <String>
    
    Required?                    false
    Position?                    1
    Default value                Hello World
    -----------
    PowerShell is cross-platform
    PowerShell is open-source
    PowerShell is easy to learn
    PowerShell is fully documented
    
    Thanks for watching
    
    :-)
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
-Speed <Int32>
    
    Required?                    false
    Position?                    2
    Default value                250
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
PS>.\write-typewriter.ps1 "Hello World"
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated from comment-based help of write-typewriter.ps1 by convert-ps2md.ps1*