---
external help file: GraphEmailSender-help.xml
Module Name: GraphEmailSender
online version:
schema: 2.0.0
---

# Send-GraphEmail

## SYNOPSIS
{{ Fill in the Synopsis }}

## SYNTAX

```
Send-GraphEmail [-SenderUPN] <MailAddress> [[-Recipients] <MailAddress[]>] [[-CopyRecipients] <MailAddress[]>]
 [[-HidenRecipients] <MailAddress[]>] [-MailSubject] <String> [-MessageBody] <String>
 [[-AttachmentPaths] <String[]>] [[-MessageBodyContentType] <String>] [-Token] <PSObject> [<CommonParameters>]
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

### -AttachmentPaths
{{ Fill AttachmentPaths Description }}

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 6
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CopyRecipients
{{ Fill CopyRecipients Description }}

```yaml
Type: MailAddress[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HidenRecipients
{{ Fill HidenRecipients Description }}

```yaml
Type: MailAddress[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MailSubject
{{ Fill MailSubject Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MessageBody
{{ Fill MessageBody Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MessageBodyContentType
{{ Fill MessageBodyContentType Description }}

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

### -Recipients
{{ Fill Recipients Description }}

```yaml
Type: MailAddress[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SenderUPN
{{ Fill SenderUPN Description }}

```yaml
Type: MailAddress
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Token
{{ Fill Token Description }}

```yaml
Type: PSObject
Parameter Sets: (All)
Aliases:

Required: True
Position: 8
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS
