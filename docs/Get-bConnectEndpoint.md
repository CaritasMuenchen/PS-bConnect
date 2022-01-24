---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectEndpoint

## SYNOPSIS
Get specified endpoint or all endpoints in given OrgUnit

## SYNTAX

```
Get-bConnectEndpoint [[-EndpointGuid] <String>] [[-OrgUnitGuid] <String>] [[-DynamicGroupGuid] <String>]
 [[-StaticGroupGuid] <String>] [[-UniversalDynamicGroupGuid] <String>] [[-Username] <String>] [-PublicKey]
 [-InstalledSoftware] [-SnmpData]
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

### -EndpointGuid
Valid GUID of a endpoint

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

### -OrgUnitGuid
Valid GUID of an Orgunit

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

### -DynamicGroupGuid
{{ Fill DynamicGroupGuid Description }}

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

### -StaticGroupGuid
{{ Fill StaticGroupGuid Description }}

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

### -UniversalDynamicGroupGuid
{{ Fill UniversalDynamicGroupGuid Description }}

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

### -Username
Valid Username

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

### -PublicKey
If set, the result contains the associated public keys.

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

### -InstalledSoftware
If set, the result contains the installed software.

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

### -SnmpData
If set, the result contains the associated snmp data.

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

### Array of Endpoint (see bConnect documentation for more details)
## NOTES

## RELATED LINKS
