---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectApplicationUninstallUserSettings

## SYNOPSIS
Creates a new UninstallUserSettings for Applications.

## SYNTAX

```
New-bConnectApplicationUninstallUserSettings [[-baramundiDeployScript] <String>] [-ValidForInstallUser]
 [-RunbDSVisible] [-CopyScriptToClient]
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

### -baramundiDeployScript
Path to the deploy script that needs to be executed during uninstallation

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

### -ValidForInstallUser
If set, script will also run for the install user

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

### -RunbDSVisible
If set, bDS will run visible

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

### -CopyScriptToClient
If set, script will be copied to client

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

### UninstallUserSettings (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
