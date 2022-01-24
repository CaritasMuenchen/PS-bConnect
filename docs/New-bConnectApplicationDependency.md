---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectApplicationDependency

## SYNOPSIS
Creates a new Dependency for Applications.
Empty or filled with given information.

## SYNTAX

```
New-bConnectApplicationDependency [-DependencyId] <String> [-DependencyAppName] <String>
 [-DependencyType] <String> [-ValidForOS] <Array> [<CommonParameters>]
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

### -DependencyId
Guid of Application to use in Dependency

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

### -DependencyAppName
Name of Application to use in Dependency

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DependencyType
Parameter with DependencyType

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ValidForOS
Parameter with ValidForOS

```yaml
Type: Array
Parameter Sets: (All)
Aliases:

Required: True
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Dependency entry (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
