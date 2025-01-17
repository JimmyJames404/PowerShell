## The *close-note-pad.ps1* Script

This PowerShell script closes the Notepad application gracefully.

## Parameters
```powershell
/home/mf/Repos/PowerShell/Scripts/close-note-pad.ps1 [<CommonParameters>]

[<CommonParameters>]
    This script supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, WarningAction, 
    WarningVariable, OutBuffer, PipelineVariable, and OutVariable.
```

## Example
```powershell
PS> ./close-note-pad

```

## Notes
Author: Markus Fleschutz | License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

## Source Code
```powershell
<#
.SYNOPSIS
	Closes the Notepad app
.DESCRIPTION
	This PowerShell script closes the Notepad application gracefully.
.EXAMPLE
	PS> ./close-note-pad
.LINK
	https://github.com/fleschutz/PowerShell
.NOTES
	Author: Markus Fleschutz | License: CC0
#>

& "$PSScriptRoot/close-program.ps1" "Notepad" "notepad" "notepad"
exit 0 # success
```

*Generated by convert-ps2md.ps1 using the comment-based help of close-note-pad.ps1*
