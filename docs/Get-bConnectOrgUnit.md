---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectOrgUnit

## SYNOPSIS
Get specified OrgUnit.

## SYNTAX

```
Get-bConnectOrgUnit [-OrgUnit] <String> [-SubGroups] [<CommonParameters>]
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

### -OrgUnit
Name (wildcards supported) or GUID of the OrgUnit.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubGroups
List subgroups of given OrgUnit.
Only used if parameter "name" is a valid GUID.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Array of OrgUnit (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
