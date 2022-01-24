---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectApplicationUninstallOptions

## SYNOPSIS
Creates a new UninstallApplicationOption for Applications.
Empty or filled with given information.

## SYNTAX

```
New-bConnectApplicationUninstallOptions [[-RebootBehaviour] <String>] [-RemoveUnknownSoftware] [-UsebBT]
 [[-VisibleExecution] <String>] [-CopyLocally] [-DisableInputDevices]
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

### -RemoveUnknownSoftware
If set, removal of not installed software will be started

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

### -UsebBT
If set, bBT is supported

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

### -VisibleExecution
Shows in which cases the execution of this software is visible

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: Silent
Accept pipeline input: False
Accept wildcard characters: False
```

### -CopyLocally
If set, installation files should be copied to local filesystem

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

### -DisableInputDevices
If set, no input devices will be available during installation

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

### InstallApplicationOption (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
