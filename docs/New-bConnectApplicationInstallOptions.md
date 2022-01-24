---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectApplicationInstallOptions

## SYNOPSIS
Creates a new InstallApplicationOption for Applications.
Empty or filled with given information.

## SYNTAX

```
New-bConnectApplicationInstallOptions [[-RebootBehaviour] <String>] [[-AllowReinstall] <Boolean>]
 [[-UsebBT] <Boolean>] [[-VisibleExecution] <String>] [[-CopyLocally] <Boolean>]
 [[-DisableInputDevices] <Boolean>] [[-DontSetAsInstalled] <Boolean>] [[-Target] <String>]
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

### -RebootBehaviour
Reboot behaviour after installation

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: NoReboot
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowReinstall
If set, reinstallation is allowed

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: True
Accept pipeline input: False
Accept wildcard characters: False
```

### -UsebBT
If set, bBT is supported

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -VisibleExecution
Shows in which cases the execution of this software is visible

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 4
Default value: Silent
Accept pipeline input: False
Accept wildcard characters: False
```

### -CopyLocally
If set, installation files should be copied to local filesystem

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: 5
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableInputDevices
If set, no input devices will be available during installation

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: 6
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -DontSetAsInstalled
If set, this application shouldn't be shown as installed, after installation

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: 7
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Target
Target path variable

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 8
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### InstallApplicationOption (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
