---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectUniversalDynamicGroup

## SYNOPSIS
Get specified Universal Dynamic Group.

## SYNTAX

```
Get-bConnectUniversalDynamicGroup [[-UniversalDynamicGroup] <String>] [[-OrgUnit] <String>] [-IsArgusSynced]
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

### -UniversalDynamicGroup
GUID of the Universal Dynamic Group.

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

### -OrgUnit
Valid GUID of a OrgUnit with Universal Dynamic Groups.

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

### -IsArgusSynced
If true, only return Universal Dynamic Groups that are synced with Argus.

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

## INPUTS

## OUTPUTS

### Array of Universal DynamicGroup (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
