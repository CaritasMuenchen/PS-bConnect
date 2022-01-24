---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# New-bConnectOrgUnitExtension

## SYNOPSIS
Creates a new Extension for OrgUnits.
Empty or filled with given information.

## SYNTAX

```
New-bConnectOrgUnitExtension [[-DIP] <String>] [[-Domain] <String>] [[-LocalAdminPassword] <SecureString>]
 [-EnableDHCP] [[-SubnetMask] <String>] [[-DefaultGateway] <String>] [[-DnsServer] <String>]
 [[-DnsServer2] <String>] [[-DnsDomain] <String>] [[-WinsServer] <String>] [[-WinsServer2] <String>]
 [[-AutoInstallJobs] <String[]>] [[-HardwareProfiles] <String[]>] [-InheritAutoInstallJobs]
 [[-RequestableJobs] <String[]>]
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

### -DIP
Valid DIP or list of DIPs (separated by ";").

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

### -Domain
Valid Windows Domain Name.

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

### -LocalAdminPassword
Local admin password for OU (set during OS-Install)
Must be encrypted with baramundi Cryptor

```yaml
Type: SecureString
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableDHCP
{{ Fill EnableDHCP Description }}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: True
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubnetMask
{{ Fill SubnetMask Description }}

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

### -DefaultGateway
{{ Fill DefaultGateway Description }}

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

### -DnsServer
{{ Fill DnsServer Description }}

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

### -DnsServer2
{{ Fill DnsServer2 Description }}

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

### -DnsDomain
{{ Fill DnsDomain Description }}

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

### -WinsServer
{{ Fill WinsServer Description }}

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

### -WinsServer2
{{ Fill WinsServer2 Description }}

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

### -AutoInstallJobs
Array of valid Job-GUIDs

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 11
Default value: @()
Accept pipeline input: False
Accept wildcard characters: False
```

### -HardwareProfiles
Array of valid HardwareProfile-GUIDs

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 12
Default value: @()
Accept pipeline input: False
Accept wildcard characters: False
```

### -InheritAutoInstallJobs
Array of valid inherited Job-GUIDs

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: True
Accept pipeline input: False
Accept wildcard characters: False
```

### -RequestableJobs
Array of valid Job-GUIDs

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 13
Default value: @()
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### Array of OrgUnit extension (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
