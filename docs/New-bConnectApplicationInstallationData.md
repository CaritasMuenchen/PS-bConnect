---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectApplicationInstallationData

## SYNOPSIS
Creates a new InstallationData for Applications.
Empty or filled with given information.

## SYNTAX

```
New-bConnectApplicationInstallationData [[-Command] <String>] [[-Parameter] <String>]
 [[-ResponseFile] <String>] [[-EngineFile] <String>] [[-Options] <PSObject>] [[-UserSettings] <PSObject>]
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

### -Command
Installation command

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

### -Parameter
Parameter for installation command

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

### -ResponseFile
ResponseFile for the installation

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

### -EngineFile
File for installation engine (Engine will be set automatically based on EngineFile; only bDS supported in this PS module)

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

### -Options
InstallApplicationOption object

```yaml
Type: PSObject
Parameter Sets: (All)
Aliases:

Required: False
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserSettings
InstallUserSettings object

```yaml
Type: PSObject
Parameter Sets: (All)
Aliases:

Required: False
Position: 6
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### InstallationData (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
