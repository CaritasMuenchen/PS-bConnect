---
external help file: cv-bConnect-help.xml
Module Name: cv-bConnect
online version:
schema: 2.0.0
---

# Get-bConnectJobInstance

## SYNOPSIS
Get specified jobinstance by GUID, all jobinstances of a job or all jobinstances on a endpoint.

## SYNTAX

```
Get-bConnectJobInstance [[-JobInstanceGuid] <String>] [[-JobGuid] <String>] [[-EndpointGuid] <String>]
 [[-Username] <String>]
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

### -JobInstanceGuid
Valid GUID of a jobinstance.

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

### -JobGuid
Valid GUID of a job.

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

### -EndpointGuid
Valid GUID of a endpoint

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

### -Username
Valid Username (in combination with EndpointGuid)

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

### Array of JobInstance (see bConnect documentation for more details).
## NOTES

## RELATED LINKS
