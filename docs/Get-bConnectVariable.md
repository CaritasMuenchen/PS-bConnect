---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectVariable

## SYNOPSIS
Get variables from a object.

## SYNTAX

```
Get-bConnectVariable [-Scope] <bConnectVariableScope> [[-Category] <String>] [[-Name] <String>]
 [[-ObjectGuid] <String>] [<CommonParameters>]
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

### -Scope
enum bConnectVariableScope.

```yaml
Type: bConnectVariableScope
Parameter Sets: (All)
Aliases:
Accepted values: Device, MobileDevice, OrgUnit, Job, Software, HardwareProfile

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Category
Valid variable category.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Valid variable name.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ObjectGuid
Valid GUID of an object.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### ObjectVariables (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
