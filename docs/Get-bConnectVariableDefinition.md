---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectVariableDefinition

## SYNOPSIS
Get variable definition.

## SYNTAX

```
Get-bConnectVariableDefinition [[-Id] <String>] [[-Scope] <bConnectVariableScope>] [[-Category] <String>]
 [[-Name] <String>]
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

### -Id
Valid GUID of a VariableDefinition

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
enum bConnectVariableScope.

```yaml
Type: bConnectVariableScope
Parameter Sets: (All)
Aliases:
Accepted values: Device, MobileDevice, OrgUnit, Job, Software, HardwareProfile

Required: False
Position: 2
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
Position: 3
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
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### VariableDefinition (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
