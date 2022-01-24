---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectAppIcon

## SYNOPSIS
Get the icon for specified app or all apps within a scope.

## SYNTAX

```
Get-bConnectAppIcon [[-AppGuid] <String>] [[-Scope] <bConnectIconScope>]
```

## DESCRIPTION
{{ Fill in the Description }}

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AppGuid
Valid GUID of a app.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Scope
Valid scope (App/Inventory).

```yaml
Type: bConnectIconScope
Parameter Sets: (All)
Aliases:
Accepted values: App, Inventory

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### Array of Icon (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
