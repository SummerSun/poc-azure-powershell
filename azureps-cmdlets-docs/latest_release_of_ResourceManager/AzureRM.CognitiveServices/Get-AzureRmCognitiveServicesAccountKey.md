---
external help file: Microsoft.Azure.Commands.Management.CognitiveServices.dll-Help.xml
ms.assetid: 73B1EB7E-568E-44E8-993A-91678B7D8AEE
online version:
schema: 2.0.0
content_git_url: https://github.com/Visual-Studio-China/azure-powershell/blob/preview/src/ResourceManager/CognitiveServices/Commands.Management.CognitiveServices/help/Get-AzureRmCognitiveServicesAccountKey.md
original_content_git_url: https://github.com/Visual-Studio-China/azure-powershell/blob/preview/src/ResourceManager/CognitiveServices/Commands.Management.CognitiveServices/help/Get-AzureRmCognitiveServicesAccountKey.md
---

# Get-AzureRmCognitiveServicesAccountKey

## SYNOPSIS
Gets the API keys for an account.

## SYNTAX

```
Get-AzureRmCognitiveServicesAccountKey [-ResourceGroupName] <String> [-Name] <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmCognitiveServicesAccountKey** cmdlet gets the API keys for a provisioned Cognitive Services account.

A Cognitive Services account has two API keys: Key1 and Key2.
The keys enable interaction with the Cognitive Services account endpoint.

Use New-AzureRmCognitiveServicesAccountKey to regenerate a key.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the account.
This cmdlet gets the keys for this account.

```yaml
Type: String
Parameter Sets: (All)
Aliases: CognitiveServicesAccountName, AccountName

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group the account is assigned to.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.Management.CognitiveServices.Models.PSCognitiveServicesAccountKeys

## NOTES

## RELATED LINKS

[New-AzureRmCognitiveServicesAccountKey](./New-AzureRmCognitiveServicesAccountKey.md)


