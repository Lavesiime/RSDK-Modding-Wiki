# CheckCurrentStageFolder

Reads the name of the current stage's folder.

## Parameters

`checkFolder`

:   The string to match.

## Return Value

Sets `checkResult` to `true` if the current folder's name ends with or matches `checkFolder`; otherwise, it's set to `false`.

!!! note
    In REV02 and earlier, only equality is checked.

## Syntax

```
CheckCurrentStageFolder(string checkFolder)
```

## Examples

```
// Sees if the current stage folder ends with "Zone01"
// Not only would a folder of "Zone01" would pass, but so would "Mission_Zone01" or "DLC_Zone01"
CheckCurrentStageFolder("Zone01")

if checkResult == true
	// The current stage folder ends with "Zone01"
end if
```
