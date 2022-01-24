---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectEndpoint

## SYNOPSIS
Create a new endpoint.

## SYNTAX

```
New-bConnectEndpoint [-Type] <bConnectEndpointType> [-DisplayName] <String> [[-GroupGuid] <String>]
 [[-PrimaryMAC] <String>] [[-PrimaryIP] <String>] [[-HostName] <String>] [[-Domain] <String>]
 [[-Options] <String>] [[-GuidBootEnvironment] <String>] [[-GuidHardwareProfile] <String>]
 [[-PrimaryUser] <String>] [[-Comments] <String>] [[-Owner] <bConnectEndpointOwner>]
 [[-ComplianceCheckCategory] <bConnectEndpointComplianceCheckCategory>] [[-Mode] <String>]
 [-ExtendedInternetMode] [-WhatIf] [-Confirm] [<CommonParameters>]
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

### -Type
enum bConnectEndpointType.

```yaml
Type: bConnectEndpointType
Parameter Sets: (All)
Aliases:
Accepted values: Unknown, WindowsEndpoint, AndroidEndpoint, iOSEndpoint, MacEndpoint, WindowsPhoneEndpoint, NetworkEndpoint

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
DisplayName of the new endpoint.
This is also used as hostname for Windows-Endpoints.

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

### -GroupGuid
Valid GUID of the target OU (default: "Logical Group").

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: C1A25EC3-4207-4538-B372-8D250C5D7908
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrimaryMAC
guid of "Logical Group" as fallback

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

### -PrimaryIP
{{ Fill PrimaryIP Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HostName
{{ Fill HostName Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 6
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Domain
{{ Fill Domain Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 7
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Options
{{ Fill Options Description }}

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

### -GuidBootEnvironment
{{ Fill GuidBootEnvironment Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 9
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GuidHardwareProfile
{{ Fill GuidHardwareProfile Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 10
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrimaryUser
Primary user of this endpoint.
Mandatory for WindowsPhone-Endpoints.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 11
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Comments
{{ Fill Comments Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 12
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Owner
{{ Fill Owner Description }}

```yaml
Type: bConnectEndpointOwner
Parameter Sets: (All)
Aliases:
Accepted values: Company, Private, Unknown

Required: False
Position: 13
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ComplianceCheckCategory
{{ Fill ComplianceCheckCategory Description }}

```yaml
Type: bConnectEndpointComplianceCheckCategory
Parameter Sets: (All)
Aliases:
Accepted values: Active, Inactive, TemporarilyInactive

Required: False
Position: 14
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Mode
{{ Fill Mode Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 15
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExtendedInternetMode
{{ Fill ExtendedInternetMode Description }}

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

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### NewEndpoint (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
