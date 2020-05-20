---
external help file: AssistDeploy-help.xml
Module Name: AssistDeploy
online version:
schema: 2.0.0
---

# Test-Json

## SYNOPSIS
Validate json is valid

## SYNTAX

```
Test-Json [-jsonToTest] <PSObject> [<CommonParameters>]
```

## DESCRIPTION
Checks that the keys for the json are as expected.

## EXAMPLES

### EXAMPLE 1
```
$ssisJson = Import-Json -path "C:\Users\SQLTraining\Documents\iscPublish.json"
```

## PARAMETERS

### -jsonToTest
json object.

```yaml
Type: PSObject
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS